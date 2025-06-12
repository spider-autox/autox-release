
# Social Media Content Assistant

A powerful tool designed for social media content creators. Seamlessly migrate and publish videos across multiple platforms with one click. Features include:

- One-click video migration  
- Multi-platform publishing (Douyin, Kuaishou, YouTube, Xiaohongshu, Bilibili, Meipai, etc.)  
- Douyin video downloads
- YouTube \tiktok video downloads


Join our user community for support and updates!

<p align="center">    
<img src="/assets/qrcode.jpg" width="400" />
</p>

---

## 📦 Installation Guide (Required)

### Download

✅ [Download AutoX v1.2.0](https://github.com/spider-ios/autox-release/releases/tag/v1.2.0)

### ✅ Chrome Browser Required

AutoX relies on Chrome for automation. Please ensure Chrome is installed on your system.  
✅ [Download Chrome](https://www.google.cn/chrome/)

---

### ✅ For Windows Users

📌 **Download [AutoX_windows.zip](https://github.com/spider-ios/autox-release/releases/tag/v1.2.0)**  
Unzip to any folder and double-click `AutoX.exe` to start.

---

### ✅ For macOS Users (Important Setup Required)

Download the appropriate version and unzip it to any location.

#### 🔹 Intel-based Macs

📌 **Download [AutoX_Mac_Intel.zip](https://github.com/spider-ios/autox-release/releases/tag/v1.2.0)**  
Open the **Terminal** and run:

```bash
xattr -rd com.apple.quarantine /Users/xxx/Downloads/AutoX.app
```

#### 🔹 Apple Silicon (M1/M2/M3)

📌 **Download [AutoX_Mac.zip](https://github.com/spider-ios/autox-release/releases/tag/v1.2.0)**  
Open the **Terminal** and run:

```bash
xattr -d com.apple.quarantine /Users/xxx/Downloads/AutoX.app
```

📝 *macOS automatically flags apps downloaded from the internet as “quarantined.” You must remove this tag to launch the app.*

---

## 🚀 Getting Started

### 🔷 Main Dashboard Overview

> ![Main UI](/assets/main.png)

---

### 📝 Account Management

> ![Account Page](/assets/account.png)

- The default port is **8633**; no configuration is needed in most cases.
- **Single Account** per platform: no setup needed.  
- **Multiple Accounts**: assign different ports to each account to ensure smooth publishing.

### ✅ Platform Login Status

AutoX **does not collect your login credentials**. Login sessions are maintained by your browser.

Click **“Check Login Status”** in the app. A browser window will open for each platform. Verify that you’re logged in—if not, please log in manually.

![Login Check](/assets/check_status.jpg)

Note: This browser instance is separate from your regular browser and doesn’t share cookies or history.

Once logged in, your session will persist unless the cache is cleared or you remain inactive for too long.

---

### 📥 Douyin Video Migration

> ![Douyin Migration](/assets/moving.png)

#### 🔐 Login Before Use

Before migrating, ensure you're logged into your destination platforms (e.g., YouTube, Xiaohongshu).

Steps:
- Click **“Check Login Status”**  
- Log in using the opened Chrome window  
- Session remains valid until expired or manually logged out  

> Example:  
> ![Login Check](/assets/check_status.jpg)  

#### 📌 How to Use

1. **Enter Douyin profile URLs**  
   Currently supports **user profile URLs only**, multiple URLs allowed (one per line).  
   Example:  
   `https://www.douyin.com/user/MS4wLjABAAAAgfJr...`

2. **Select the time range of videos to publish**

3. **Enable Silent Publishing (optional)**  
   Publishing runs in the background without opening the browser.

4. **Set Cookie (optional)**  
   [See Cookie Guide](./cookie-helper/README.md)

   > Visual guide:  
   > ![Step 1](/assets/cookie1.png)  
   > ![Step 2](/assets/cookie2.png)  
   > ![Step 3](/assets/cookie3.png)  
   > ![Step 4](/assets/cookie4.png)  

5. **Select platforms and accounts to begin migration**  
   > ![Account Selection](/assets/account1.png)

---

### 🌐 Multi-Platform Publishing

> ![Publish UI](/assets/publish.png)

#### 🔐 Login Instructions

- Log in for each platform before publishing.
- Use **“Open Browser”** to log in to platforms like YouTube, Xiaohongshu, Bilibili, etc.
- AutoX uses an isolated Chrome instance for secure automation.

---

Need help? Submit an issue on GitHub!  
Join the community to connect with other users:

<p align="center">    
<img src="/assets/qrcode.jpg" width="400" />
</p>
