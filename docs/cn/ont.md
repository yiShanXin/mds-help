本体 DAPP 开发文档

# 钱包内 H5 DAPP 开发

## dAPI

麦子钱包兼容 ONT 的 dAPI 进行支付和合约调用的签名操作

### dAPI API 官方文档

[https://dev-docs.ont.io/#/docs-en/dApi/00-overview](https://dev-docs.ont.io/#/docs-en/dApi/00-overview)

### 使用 dAPI 接口的应用

[ONTBET](https://ont.bet/)

[HyperDragons Go!](https://hyd-go.alfakingdom.com/)

# Native DAPP 开发

## SimpleWallet 协议

您可以通过麦子钱包定制版 SimpleWallet 协议进行：

Native APP 跳转麦子钱包支付或合约签名。

协议标准请查看：

[https://github.com/MediShares/SimpleWallet](https://github.com/MediShares/SimpleWallet)

注意：transferReq.blockchain 参数请传 ont

### SimpleWallet API 开发示例

麦子钱包团队开发了一套APP端调起麦子钱包进行支付的示例代码：

iOS – [https://github.com/MediShares/MathWalletSDK-iOS](https://github.com/MediShares/MathWalletSDK-iOS)

Android – [https://github.com/MediShares/MathWalletSDK-Android](https://github.com/MediShares/MathWalletSDK-Android)

# 网页 DAPP 打开麦子钱包支付

支持手机浏览器网页通过链接的形式打开麦子钱包进行支付和合约签名。接口基于 SimpleWallet 协议麦子拓展版本：

[https://github.com/MediShares/SimpleWallet](https://github.com/MediShares/SimpleWallet)

示例DEMO和代码：

[http://developer.mathwallet.org/sample12/](http://developer.mathwallet.org/sample12/)

[https://github.com/MediShares/mds-eosjs/tree/master/eos/sample12](https://github.com/MediShares/mds-eosjs/tree/master/eos/sample12)