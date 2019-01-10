# More Q&A

Q. How to know whether the address is opened by the dapp browser of Math Wallet ?

If there’s “MdsApp” in useragent, then it is visited by the browser of Math Wallet.

Q. How to get more current wallet information, such as orientation / language / fullscreen, etc?

We will need math-js-sdk: [https://github.com/MediShares/math-js-sdk](https://github.com/MediShares/math-js-sdk)

Q. How to debug a dApp within Math Wallet?

Please read: [http://blog.medishares.org/?p=1248](http://blog.medishares.org/?p=1248)

Q. Does Math Wallet support testnet chain environment and account?

No, we do not support testnet.


Q. How to open a dApp in landscape screen orientation?

There are 2 ways:

1 Math Wallet team can help you config your dApp opened in landscape mode by default, you just need to inform us.

2 You can use math-js-sdk: [https://github.com/MediShares/math-js-sdk](https://github.com/MediShares/math-js-sdk), issue the orientation() function.

Q. How to open a dApp in full screen mode?

You can use math-js-sdk: [https://github.com/MediShares/math-js-sdk](https://github.com/MediShares/math-js-sdk), issue the fullScreen(1) function.
And we suggest you add a 'Close' button in your dApp, which need to issue fullScreen(0) or close() function.
