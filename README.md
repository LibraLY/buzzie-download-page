# Buzzie 下载页面

这是 Buzzie 财务助手应用的下载页面，设计美观、响应式，适用于展示和分发 Android 和 iOS 应用。

## 部署说明

1. 将整个 `buzzie-download-page` 文件夹上传到您的 Web 服务器
2. 确保将 Android APK 文件命名为 `buzzie.apk` 并放置在 `downloads` 目录中
3. 确保将 iOS IPA 文件命名为 `buzzie.ipa` 并放置在 `downloads` 目录中
4. 访问网站根目录下的 `index.html` 文件

## 自定义指南

- 颜色主题：编辑 `css/style.css` 文件中的 `:root` 部分，修改颜色变量
- Logo：替换 `assets/logo.svg` 文件
- 应用截图：替换 `assets/app-preview.png` 文件
- 商店图标：替换 `assets/google-play.png` 和 `assets/app-store.png` 文件
- 二维码：替换 `assets/android-qr.svg` 和 `assets/ios-qr.svg` 文件
- 背景：替换 `assets/background.svg` 文件
- 功能图标：替换 `assets/feature-1.svg`、`assets/feature-2.svg`、`assets/feature-3.svg` 文件

## 文件结构

```
buzzie-download-page/
├── assets/           # 图片和图标资源
├── css/              # 样式表
├── downloads/        # 应用下载文件
├── js/               # JavaScript 文件
├── index.html        # 主页面
└── README.md         # 说明文档
```

## 需要创建的占位图像

需要创建以下占位图像文件：
- `assets/app-preview.png`：应用预览截图
- `assets/google-play.png`：Google Play 商店图标
- `assets/app-store.png`：App Store 图标

## 技术栈

- HTML5
- CSS3（响应式设计）
- 纯 JavaScript（无依赖） 