# 📱 LitPlayer

[中文介绍](https://github.com/daluobo/LitPlayer-release/blob/main/README_CN.md)

LitPlayer is an Android meida player built with the Jetpack Compose declarative UI framework, based on Media3 ExoPlayer, and following the **Material Design 3** specification. It features a clean interface, smooth interactions, and is perfectly adapted for **Android phones, tablets**, and **Android TV**, providing a consistent viewing experience across devices.


## 📲 Device Support

- ✅ Android Phone

- ✅ Android Pad

- ✅ Android TV



## 🚀 Key Features

### ▶️ Playback Support

- Local audio、video playback，Standalone MIDI player interface

- Network streaming playback (supports SMB, WebDAV, Ftp, Jellyfin、UPnP media servers)

- Playback gestures (double-tap to play/pause, swipe to seek forward/backward, volume/brightness gesture adjustment, long press for speed playback, etc.)

- Supports DLNA media casting


### 🎨 Subtitles & Audio Tracks

- Supports multiple audio and subtitle track switching

- Full compatibility with **ASS special effects subtitles**

- External subtitle support with customizable subtitle styles

- Audio-only playback mode to save battery by disabling video rendering


### 🔄 Cross-Device Sync

- Supports synchronizing playback data between mobile devices and Android TV via Bluetooth


### 🎨 Interface & Theme

- Bilingual UI (Chinese/English)

- RGB colorful themes for personalized visual experience



## 📊 Version & Feature Adaptation
Starting from version 0.6.0, the lite version and prod version basically have the same features. The main difference is that the lite version includes different third-party dependencies to support older Android systems. If your device runs Android 8.0 or above, please install the prod version for better performance and security.

|Version Type|Minimum Android Version|
|---|---|
|Phone/Pad - lite|6.0|
|Phone/Pad|8.0|
|TV - lite|7.0|
|TV|8.0|


## 📥 Download & Installation

- The mobile version currently only supports the arm64-v8a architecture (i.e., 64-bit ARM devices). If your device uses a different architecture (such as 32-bit ARM or x86), it may not run properly after installation. If you need support for other architectures, please feel free to submit your requests via [Issues](https://github.com/daluobo/LitPlayer-release/issues). We will evaluate the feedback and consider future compatibility plans accordingly.

- The TV version includes both arm64-v8a and armeabi-v7a builds.


[Releases](https://github.com/daluobo/LitPlayer-release/releases/latest)


## 📸 Preview

### Mobile Version

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

### TV Version

<div style="display: flex;">
    <img alt="tv_home" src="https://github.com/user-attachments/assets/1982e04d-c760-4b53-9a68-cbef8979e8b9" width="48%" />
    <img alt="tv_library_1" src="https://github.com/user-attachments/assets/77426930-a604-46f6-8c5d-bb136197bbf9" width="48%" />
</div>
<div style="display: flex;">
    <img alt="tv_library_2" src="https://github.com/user-attachments/assets/ff81bede-ba12-4167-b463-342454d2333d" width="48%" />
    <img alt="tv_playback" src="https://github.com/user-attachments/assets/bf54a24d-bac7-4979-9b83-b9392c506c47" width="48%" />
</div>
