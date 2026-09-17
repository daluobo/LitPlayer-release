# 📱 播播机（LitPlayer）

LitPlayer 是一款采用 Jetpack Compose 声明式 UI 框架，基于 Media3 ExoPlayer 构建，遵循 **Material Design 3** 设计规范的 Android 音视频播放器，界面简洁、交互流畅，完美适配 **Android 手机、平板** 与 **Android TV**，为您提供跨设备的一致观影体验。


## 📲 设备支持

- ✅ Android Phone

- ✅ Android Pad

- ✅ Android TV



## 🚀 功能亮点

### ▶️ 播放支持

- 本地音频、视频播放，midi文件独立播放UI

- 网络流媒体播放（支持 SMB、WebDAV、Ftp、Jellyfin、UPnP 媒体服务器）

- 播放手势操作（双击播放/暂停、滑动快进/快退、音量/亮度手势调节、长按倍速播放等）

- 支持 DLNA媒体投屏


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
自0.6.0版本开始，lite版本与prod版本功能已经基本一致，差别主要在于为兼容低版本的安卓系统引入不同的第三方依赖，如果你的设备系统为8.0及以上，请安装prod版本以获得更好的性能和安全性

|版本类型|Android 最低版本|
|---|---|
|Phone/Pad - lite|6.0|
|Phone/Pad|8.0|
|TV - lite|6.0|
|TV|8.0|


## 📥 下载与安装
- 移动端当前仅提供 arm64-v8a 架构（即 64 位 ARM 设备）。如果您的设备是其他架构（如 32 位 ARM 或 x86），安装后可能无法正常运行。若您需要其他架构的支持，欢迎通过 [Issues](https://github.com/daluobo/LitPlayer-release/issues) 提出需求，我们会根据反馈情况评估后续兼容计划
- TV端 包含了arm64-v8a和armeabi-v7a

[Releases](https://github.com/daluobo/LitPlayer-release/releases/latest)


## 📸 预览

### 移动端

#### 视频
<div style="display: flex;">
<img  alt="home" src="https://github.com/user-attachments/assets/8557df62-3759-425c-adb7-faa7aa9cd8aa" width="24%" />
<img  alt="video list" src="https://github.com/user-attachments/assets/222382a6-0a7d-4883-bed6-79a6f07a4591" width="24%" />
<img  alt="video playing" src="https://github.com/user-attachments/assets/a360dfec-683d-4fc4-b026-c488a3836365" width="24%" />
<img  alt="video playlist" src="https://github.com/user-attachments/assets/2b224868-b6b9-433d-aafa-daf2d7d60f56" width="24%" />
</div>

#### 音频
<div style="display: flex;">
<img  alt="music title" src="https://github.com/user-attachments/assets/7174cb7b-0b06-4492-89e9-4011bf899b26" width="24%" />
<img  alt="music playback" src="https://github.com/user-attachments/assets/d451b0c4-ec70-4a58-8004-2c7e8879d1d7" width="24%" />
<img  alt="midi list" src="https://github.com/user-attachments/assets/b4508a40-53b2-4e8e-a29c-6afb5fe2f360" width="24%" />
<img  alt="midi playback" src="https://github.com/user-attachments/assets/577728d5-8009-4012-82ee-059949b746c5" width="24%" />
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