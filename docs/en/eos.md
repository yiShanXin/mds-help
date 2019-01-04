EOS DAPP Development Document

# In-Wallet Web dApp Development

## Scatter API

Math Wallet is compatiable with Scatter API.

Scatter is really universal that could not only be used with Chrome browser on desktop but also could be used directly inside mobile terminal such as Math Wallet with just one set of code. By the way, it would be much easier to debug on desktop during development.

### Scatter API Official Doc

[https://get-scatter.com/docs/dev/getting-started](https://get-scatter.com/docs/dev/getting-started)

### Scatter API Demo Projects

Scatter API Sample developed by Math Wallet Team

[https://github.com/MediShares/scatter-eos-sample](https://github.com/MediShares/scatter-eos-sample)

Sample project for EOS newbie

[https://github.com/ericfish/EOS-Dev-Book](https://github.com/ericfish/EOS-Dev-Book)

### dApps using Scatter API

[DICE](https://betdice.one)

[Chintai](https://eos.chintai.io)

### Scatter API QA

Q. Is it neccessary to distinguish the sactter.js file from wallet or PC side?

A. No, just use 'scatter.min.js'. PC side could run first and then put into Math Wallet and make some mobile adaptation.

Q. How to get more current wallet information, such as orientation / language / fullscreen, etc?

A. We will need math-js-sdk: [https://github.com/MediShares/math-js-sdk](https://github.com/MediShares/math-js-sdk)

## MDS-EOSJS API

Developed based on jQuery, easy to pick up, only for Math Wallet.

It is easy to use and the MathWallet team has provided the sample includes complete front-end part. (limited to MathWallet environment)

Repo of API and sample:

[https://github.com/MediShares/mds-eosjs](https://github.com/MediShares/mds-eosjs)

# Native/Web dApp Development

## SimpleWallet API

If your DAPP is based on native development or browser based, you could open MathWallet to sign your transaction through SimpleWallet protocol or use Math Wallet to scan and authorize.

MathWallet SimpleWallet Protocol supports:

1 Native APP can open MathWallet to sign your transaction

2 Web APP can open MathWallet to sign your transaction

This protocol is already used by EOS Knight, Newdex, WhaleEX etc.

To use this API, please read the API doc:

[https://github.com/MediShares/SimpleWallet](https://github.com/MediShares/SimpleWallet)

Note: transferReq.blockchain please use 'eosio'

### SimpleWallet API Demo Projects

SDK example developed by Math Wallet team:

iOS – [https://github.com/MediShares/MathWalletSDK-iOS](https://github.com/MediShares/MathWalletSDK-iOS)

Android – [https://github.com/MediShares/MathWalletSDK-Android](https://github.com/MediShares/MathWalletSDK-Android)

### dApps using SimpleWallet API

[EOS Knights](http://eosknights.io)

[WhaleEX](https://whaleex.com)

# Scan QRCode API

MathWallet supports scan QRcode to login and sign transaction based on SimpleWallet protocol.

To use this API, please read the API doc:

[https://github.com/MediShares/SimpleWallet](https://github.com/MediShares/SimpleWallet)

Newdex web version is using this API for login.