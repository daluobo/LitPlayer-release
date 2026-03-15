# 📱 播播机（LitPlayer）

LitPlayer 是一款采用 Jetpack Compose 声明式 UI 框架，基于 Media3 ExoPlayer 构建，遵循 **Material Design 3** 设计规范的 Android 音视频播放器，界面简洁、交互流畅，完美适配 **Android 手机、平板** 与 **Android TV**，为您提供跨设备的一致观影体验。


## 📲 设备支持

- ✅ Android Phone

- ✅ Android Pad

- ✅ Android TV



## 🚀 功能亮点

### ▶️ 播放支持

- 本地音频、视频播放

- 网络流媒体播放（支持 SMB、WebDAV、Ftp、Jellyfin、UPnP 媒体服务器）

- 播放手势操作（双击播放/暂停、滑动快进/快退、音量/亮度手势调节、长按倍速播放等）


### 🎨 字幕与音轨

- 支持多音轨与多字幕轨切换

- 完美兼容 **ASS 特效字幕**

- 外挂字幕支持，字幕样式可自定义

- 音频分流播放，可关闭视频渲染以节省电量


### 🔄 跨设备同步

- 支持通过蓝牙在移动设备与 Android TV 之间同步播放数据


### 🎨 界面与主题

- 中英双语 UI

- RGB 炫彩主题，个性化视觉体验



## 📊 版本与功能适配

|版本类型|Android 最低版本|UPnP 媒体服务器|
|---|---|---|
|Phone/Pad - lite|6.0|❌ 不支持|
|Phone/Pad|8.0|✅ 支持|
|TV - lite|7.0|❌ 不支持|
|TV|8.0|✅ 支持|


## 📥 下载与安装
- 移动端当前仅提供 arm64-v8a 架构（即 64 位 ARM 设备）。如果您的设备是其他架构（如 32 位 ARM 或 x86），安装后可能无法正常运行。若您需要其他架构的支持，欢迎通过 [Issues](https://github.com/daluobo/LitPlayer-release/issues) 提出需求，我们会根据反馈情况评估后续兼容计划
- TV端 包含了arm64-v8a和armeabi-v7a

[Releases](https://github.com/daluobo/LitPlayer-release/releases/latest)


## 📸 预览

### 移动端

#### 视频
<div style="display: flex;">
<img  alt="home" src="https://github.com/user-attachments/assets/516af00b-a3f7-4398-98a2-08ca685ebf1e" width="24%" />
<img  alt="video list" src="https://github.com/user-attachments/assets/47cb43c2-2f9f-4b51-b130-c8e9a8e4be6f" width="24%" />
<img  alt="video playing" src="https://github.com/user-attachments/assets/a360dfec-683d-4fc4-b026-c488a3836365" width="24%" />
<img  alt="video playlist" src="https://github.com/user-attachments/assets/15474f11-8d58-4369-8ccd-2180cf735189" width="24%" />
</div>

#### 音频
<div style="display: flex;">
<img  alt="audio title" src="https://github.com/user-attachments/assets/e839a9cd-386b-4cab-b4eb-87aa10b82e53" width="24%" />
<img  alt="audio album" src="https://github.com/user-attachments/assets/fd6c80f3-7b09-4e48-96cd-958036dae3dc" width="24%" />
<img  alt="video playing" src="https://github.com/user-attachments/assets/6870e602-5979-4344-a424-6b66bffe07af" width="24%" />
<img  alt="audio playlist" src="https://github.com/user-attachments/assets/38530aec-85c8-4825-a858-ac2acb32591d" width="24%" />
</div>

### TV端
<div style="display: flex;">
<img alt="tv_home" src="https://github.com/user-attachments/assets/1982e04d-c760-4b53-9a68-cbef8979e8b9" width="48%" />
<img alt="tv_library_1" src="https://github.com/user-attachments/assets/77426930-a604-46f6-8c5d-bb136197bbf9" width="48%" />

</div>
<div style="display: flex;">
<img alt="tv_library_2" src="https://github.com/user-attachments/assets/ff81bede-ba12-4167-b463-342454d2333d" width="48%" />
<img alt="tv_playback" src="https://github.com/user-attachments/assets/bf54a24d-bac7-4979-9b83-b9392c506c47" width="48%" />
</div>