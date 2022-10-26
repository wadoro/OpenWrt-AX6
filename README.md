**中文** | [上游源代码](https://github.com/P3TERX/Actions-OpenWrt)

# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)


# 维护自用固件
## Redmi AX6
- 使用源码：https://github.com/coolsnowwolf/lede (恢复对ax6的支持)
- 内核：5.10
- 默认IP:192.168.2.1

### 编译插件：
Argon主题、ShadowSocksR Plus+、Nps客户端、阿里云盘WebDAV、KMS服务器、Turbo ACC 网络加速。

---------------------------

# 原作者模版使用方法：

使用 GitHub Actions 构建 OpenWrt 的模板

## 用法
- 单击[Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) 按钮创建一个新的存储库。
- .config使用[Lean's OpenWrt](https://github.com/coolsnowwolf/lede)的 OpenWrt源代码生成文件。（您可以通过工作流文件中的环境变量进行更改。）
- 将文件.config推送到 GitHub 存储库。
- Build OpenWrt在“Actions”页面上选择。
- 单击Run workflow按钮。
- 构建完成后，单击Artifacts-Actions 页面右上角的按钮下载二进制文件。

## 提示
- .config创建文件和构建 OpenWrt 固件可能需要很长时间。因此，在创建存储库以构建您自己的固件之前，您可以通过简单地在 GitHub中搜索Actions-Openwrt来查看其他人是否已经构建了满足您需求的固件。
- 将您构建的固件的一些元信息（例如固件架构和已安装的软件包）添加到您的存储库介绍中，这将节省其他人的时间。


--------------------------------------------------------------------------------------------------------------------------

## Credits

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
