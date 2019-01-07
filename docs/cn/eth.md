以太坊 DAPP 开发文档

# 钱包内 H5 DAPP 开发

## Web3 API

麦子钱包兼容 ETH 的 web3 API，并提供与 metamask 同样功能

### Web3 API 官方文档

[https://github.com/ethereum/wiki/wiki/JavaScript-API](https://github.com/ethereum/wiki/wiki/JavaScript-API)

### Web3 API 开发示例

麦子钱包团队开发的 Web3 API 开发示例和测试方法

[https://github.com/MediShares/mds-ethjs](https://github.com/MediShares/mds-ethjs)

### 使用 Web3 接口的应用

[Fomo3D](http://exitscam.me/)

[CryptoKitties](https://www.cryptokitties.co/)

# Native DAPP 开发

## SimpleWallet 协议

您可以通过麦子钱包定制版 SimpleWallet 协议进行：

Native APP 跳转麦子钱包支付或合约签名。

协议标准请查看：

[https://github.com/MediShares/SimpleWallet](https://github.com/MediShares/SimpleWallet)

注意：transferReq.blockchain 参数请传 ethereum

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

