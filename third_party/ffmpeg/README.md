# FFmpeg SDK 放置说明

此目录用于存放构建 Chromaprint 所需的 FFmpeg SDK。

- Windows x64 版本请放入 `third_party/ffmpeg/win64/`，包含 `include/` 与 `.lib/.dll`。
- macOS Universal 版本请放入 `third_party/ffmpeg/macos/`，包含 `include/` 与 `.dylib/.a`。

GitHub Actions 构建会使用这里的内容来定位 FFmpeg 头文件与库文件。

