# Alan 本地补丁

日期：2026-10-24。此分支用于备份 MaiBot 本机已使用的源码补丁，原作者与许可证保持不变。

- 上游：https://github.com/ZhaoCang-QWQ/doubao-tts
- 安装基线：`1ed5987169ae42f9e039048d8db7a3b9bceb00f2`
- 补丁分支：`alan-local`（以实际安装版本为基线，避免同时升级宿主或插件）
- 改动：增加语音情境、停顿标点与可选口语改写配置。
- 配置与数据：不上传真实运行配置、密钥、QQ 名单、聊天记录、数据库、音频、参考图库或备份文件。配置模板仅保留通用示例。
- 安装：`git clone --branch alan-local https://github.com/touching-fishfish/maibot-doubao-tts.git`，再按原 README 配置自己的服务。
- 验证：Python 源码、JSON 与 TOML 解析及凭据模式扫描；写真插件另运行现有离线测试。未发送 QQ 消息或调用付费生图/语音服务。
