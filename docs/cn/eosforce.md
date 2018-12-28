EOS原力 DAPP 开发文档

# H5 DAPP 开发

## Scatter API（推荐）

麦子钱包兼容基于 Scatter 接口开发的 DAPP，您只需要做一些移动端适配即可

Scatter接口的优点是通用性好，除了移动端在麦子钱包内直接使用，桌面端可以配合Scatter Chrome浏览器使用，一套代码即可，另外开发时在桌面端比较容易调试。

### Scatter API 官方文档

[https://get-scatter.com/docs/dev/getting-started](https://get-scatter.com/docs/dev/getting-started)

### Scatter API 开发示例

麦子钱包团队开发的 Scatter API 开发示例

[https://github.com/MediShares/scatter-eos-sample](https://github.com/MediShares/scatter-eos-sample)

如果您是 EOS 和 DAPP 新手，您可以通过这个代码仓库入门

[https://github.com/ericfish/EOS-Dev-Book](https://github.com/ericfish/EOS-Dev-Book)

### Scatter API 相关问题

Q: 钱包和PC端引入的 scatter.js 文件需要区分一下吗？

不需要，使用Scatter官方的 scatter.min.js 即可，PC端可以运行后，放到麦子钱包即可运行，做下移动端页面适配即可

Q: 如何在 DAPP 页面获取钱包信息、全屏、打开微信、横屏、当前语言等信息和操作？

可以通过 math-js-sdk: [https://github.com/MediShares/math-js-sdk](https://github.com/MediShares/math-js-sdk)

## MDS-EOSForceJS API

麦子钱包定制版 API，由麦子钱包团队基于 jQuery 开发。

它的优点是学习成本很低，而且麦子团队的sample连前端页面都帮你做好了。当然它只能用于麦子钱包环境内。

mds-eosforcejs 接口和sample可以查看下面的代码仓库，目前已经在麦子钱包上线的《小协议》等都是基于这个API开发的

[https://github.com/MediShares/mds-eosforcejs](https://github.com/MediShares/mds-eosforcejs)

# Native DAPP 开发

## SIMPLEWALLET 协议

如果您的DAPP是基于Native开发，您可以通过SimpleWallet协议跳转麦子钱包或者由麦子钱包扫描二维码或者跳转进行授权。

目前 EOS骑士、鲸交所、Newdex、SpiderStore 等 Native APP 已经使用麦子所提供的 SIMPLEWALLET 协议接口。

协议标准请查看：

[https://github.com/MediShares/SimpleWallet](https://github.com/MediShares/SimpleWallet)

注意：transferReq.blockchain 参数请传 eosforce

麦子钱包团队开发了一套APP端调起麦子钱包进行支付的示例代码：

iOS – [https://github.com/MediShares/MathWalletSDK-iOS](https://github.com/MediShares/MathWalletSDK-iOS)

Android – [https://github.com/MediShares/MathWalletSDK-Android](https://github.com/MediShares/MathWalletSDK-Android)

