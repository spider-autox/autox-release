📹 AutoX – Cross-Platform Video Automation Toolkit
AutoX is a powerful automation tool designed for content creators and social media teams. It allows you to automatically download videos from major platforms like Douyin (TikTok China), YouTube, TikTok Global, Bilibili, etc., and repost/publish them with one click to multiple platforms including:

TikTok · Facebook · Twitter · YouTube · Xiaohongshu · Kuaishou · Bilibili · Douyin and more.

<p align="center"> <img src="/assets/qrcode.jpg" width="400" /> </p>
📦 Installation Guide
✅ Download the Latest Version
👉 Download AutoX v1.3.0

✅ Install Google Chrome (Required)
AutoX uses Chrome for automation. Make sure it is installed:

🔗 Download Chrome

🖥️ Windows
Download AutoX_windows.zip

Unzip it to any folder

Run AutoX.exe

🍎 macOS (with extra steps)
Download the correct version based on your chip:

Intel Mac: AutoX_Mac_Intel.zip

Apple Silicon (M1/M2/M3): AutoX_Mac.zip

Open Terminal and run the following command (modify path accordingly):

bash
复制
编辑
xattr -rd com.apple.quarantine /Users/xxx/Downloads/AutoX.app
This step removes macOS quarantine protection and allows the app to launch.

🚀 Core Features
🔐 Account Login & Status Check
AutoX does not store your account credentials. Login status is maintained by the browser itself. You can check login by clicking the "Check Login Status" button — AutoX will launch separate browser windows for each platform.



📥 TikTok (Douyin) Video Migration
Easily migrate videos from Douyin to platforms like YouTube, Bilibili, and more.

Steps:

Paste your Douyin user profile link (supports multiple lines).

Choose a time range for the videos you want to migrate.

Optionally enable silent publishing (headless mode).

Set your platform login cookies (see cookie-helper for instructions).

Choose target platforms and accounts to start migration.

🌐 Multi-Platform Video Publishing
Publish videos to multiple platforms with a single click:



YouTube, Twitter, Facebook, Bilibili, Xiaohongshu, TikTok, and more supported

Requires each platform to be logged in via Chrome

🎬 Video Processing Toolkit


Key Features:
Intro/Outro Insertion: Seamless splicing using FFmpeg

Watermarking: Text/image, dynamic, multi-position support

Keyframe Replacement: Modify I-frames to bypass duplicate detection

Video Metadata Extraction: Get bitrate, resolution, format, etc.

⚙️ Advanced Configurations
Batch Processing: Add watermarks, convert formats, analyze multiple videos

Performance Optimization: Hardware acceleration (GPU), multithreading, low-memory mode

Custom Presets: YAML-based templates for format, codec, resolution, watermark styles

📝 Platform Publishing Best Practices
Platform	Format	Resolution	Notes
TikTok/Douyin	MP4	1080×1920 (portrait)	Short-form, vertical
YouTube	MP4	1920×1080 (landscape)	Long-form supported
Bilibili	MP4	1080p+	4K also supported

📌 Important Notes
Make sure FFmpeg is installed on your system

Chrome is required for automation

Always check login status before publishing

For macOS users: remove quarantine tag before first run

📣 Join the Community
Have questions or feature requests?
Submit an Issue or scan to join our user group:

<p align="center"> <img src="/assets/qrcode.jpg" width="400" /> </p>
