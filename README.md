# RVC Studio

Windows 桌面变声工作室：Qt 界面、后台加载、明确的音频路由，以及内嵌的完整 RVC 音频/训练工作室。

## 下载源码

本仓库以源码压缩包保存完整项目，目录结构保留在压缩包内：

**[下载 RVC-Studio-source.zip](RVC-Studio-source.zip)**

解压后阅读其中的 `README.md`，按说明安装 Python 3.12、项目依赖及 PySide6，准备所需模型后运行 `go-realtime_gui.bat`。`build-desktop.ps1` 可生成无控制台的 EXE 启动器。

该文件是源码备份，不是完整安装包：不包含 Python/CUDA 运行时、FFmpeg、模型权重、索引、录音、日志或个人配置。

## 保留的功能

- 实时变声、输入监听、音调/声线、索引混合、响度、双向降噪。
- 声卡 API、独占 WASAPI、采样率、PM/RMVPE/FCPE、缓冲及延迟参数。
- 实时电平与耗时、后台模型加载、设备明确绑定、模型复用。
- 原 WebUI 的离线转换、分离、训练、特征提取、索引及模型工具。

## 许可与来源

基于 [RVC WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)，保留 [MIT 许可](LICENSE) 与压缩包内第三方声明。模型及音频素材须另行获得使用权。

源码包包含安装、构建、开发及贡献说明。未验证所有模型的音质和完整训练流程。
