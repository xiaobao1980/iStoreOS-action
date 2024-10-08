# 使用 GitHub Actions 编译 istoreos 固件
该仓库使用 GitHub Actions 自动化编译 istoreos 固件的过程。目前支持 rk33xx 和 rk35xx 设备，后续将加入对 x86 设备的支持。

# 功能特点
自动化构建：利用 GitHub Actions 自动编译支持设备的固件。
多设备支持：初期支持 rk33xx 和 rk35xx 设备，未来将加入对 x86 设备的支持。
可定制配置：轻松修改配置以满足您的需求。
支持的设备
rk33xx
rk35xx
x86（即将支持）

# Text版本测试
Tesx版本加入adguardhome、openclash、mosdns等插件，如需使用请在Releases选择带test尾标的相应固件下载

# 快速开始
要开始使用此仓库，请按照以下步骤操作：

1. Fork 仓库：点击页面右上角的 “Fork” 按钮，将此仓库复制到您的 GitHub 账户。
2. 配置构建：编辑 .config 文件，或使用默认配置来选择您的目标设备。
3. 启用 GitHub Actions：确保在您的 Fork 仓库中启用 GitHub Actions。
4. 启动构建：手动触发构建，或推送更改到您的仓库以启动构建过程。

# 未来计划
x86 设备支持：我们计划在不久的将来扩展对 x86 设备的支持。
增强自定义功能：提供更多选项以便于构建的自定义和优化。

# 致谢
特别感谢 istoreos 官方团队提供的源码，使得本项目的开发和自动化编译成为可能。

# 贡献
欢迎贡献！如果您有任何建议或改进，欢迎提出 Issue 或提交 Pull Request 来增强本仓库的功能。

# 许可证
该项目采用 MIT 许可证进行许可，详见 LICENSE 文件。

