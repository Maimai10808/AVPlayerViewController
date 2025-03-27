# AVPlayerViewController

# 🎬 TikTokClone - SwiftUI Video Player Demo

A simple SwiftUI demo mimicking a TikTok-style video feed using `AVPlayer` and `AVPlayerViewController`, wrapped with `UIViewControllerRepresentable`.

---

## 🚀 Features

- ✅ Custom AVPlayer integration with SwiftUI
- ✅ Fullscreen video playback with `resizeAspectFill`
- ✅ Auto-play support
- ✅ Picture-in-picture enabled
- ✅ No playback controls (clean, immersive experience)
- ✅ Lightweight and easy to customize

---

## 🛠 Tech Stack

- Swift
- SwiftUI
- UIKit (`AVPlayerViewController`)
- Xcode

---

## 📦 How It Works

- `CustomVideoPlayer` is a SwiftUI-compatible wrapper for `AVPlayerViewController`
- Videos are loaded from HTTP URLs
- App Transport Security (ATS) exception is configured in `Info.plist` to allow non-HTTPS video streaming

---

## 📄 Setup

1. Clone the repo
   ```bash
   git clone https://github.com/your-username/TikTokClone.git

## 📌 ATS Configuration

If your videos don’t play, make sure to allow HTTP content in Info.plist:
```
<key>NSAppTransportSecurity</key>
<dict>
    <key>NSExceptionDomains</key>
    <dict>
        <key>commondatastorage.googleapis.com</key>
        <dict>
            <key>NSIncludesSubdomains</key>
            <true/>
            <key>NSExceptionAllowsInsecureHTTPLoads</key>
            <true/>
        </dict>
    </dict>
</dict>
```
⸻
🇨🇳 TikTokClone - 基于 SwiftUI 的短视频播放器 Demo

一个模仿 TikTok 风格的视频播放 Demo，使用 SwiftUI 与原生 AVPlayerViewController 播放远程视频资源。

⸻

🚀 功能亮点
	•	✅ SwiftUI 集成 AVPlayer
	•	✅ 视频铺满全屏播放（resizeAspectFill）
	•	✅ 自动播放
	•	✅ 支持画中画
	•	✅ 无播放控制条（沉浸式体验）
	•	✅ 结构简洁，方便拓展

⸻

🛠 技术栈
	•	Swift
	•	SwiftUI
	•	UIKit（AVPlayerViewController）
	•	Xcode

⸻

📦 项目原理
	•	封装 UIKit 的 AVPlayerViewController 为 SwiftUI 组件
	•	视频通过远程 HTTP 链接加载
	•	为了允许加载非 HTTPS 视频，需配置 ATS（App Transport Security）

 ## 📌 ATS 设置（重要）

如果你的视频播放失败，请在 Info.plist 中添加如下配置：
```
<key>NSAppTransportSecurity</key>
<dict>
    <key>NSExceptionDomains</key>
    <dict>
        <key>commondatastorage.googleapis.com</key>
        <dict>
            <key>NSIncludesSubdomains</key>
            <true/>
            <key>NSExceptionAllowsInsecureHTTPLoads</key>
            <true/>
        </dict>
    </dict>
</dict>
```


   

