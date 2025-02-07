# TON Connect for Developers

:::info
If possible, it is recommended to use the [@tonconnect/ui-react](/develop/dapps/ton-connect/developers#ton-connect-ui-react) kit for your dApps. Only switch to lower levels of the SDK or reimplement your version of the protocol if it is really necessary for your product.
:::

The TON Connect repository contains following main packages:

- [@tonconnect/ui-react](/develop/dapps/ton-connect/developers#ton-connect-ui-react) - TON Connect User Interface (UI) for React applications
- [@tonconnect/ui](/develop/dapps/ton-connect/developers#ton-connect-ui) - TON Connect User Interface (UI)
- [@tonconnect/sdk](/develop/dapps/ton-connect/developers#ton-connect-sdk)  - TON Connect SDK
- [@tonconnect/protocol](/develop/dapps/ton-connect/developers#ton-connect-protocol-models) - TON Connect protocol specifications


## TON Connect UI React

TonConnect UI React is a React UI kit for TonConnect SDK. Use it to connect your app to TON wallets via TonConnect protocol in React apps.

- [GitHub](https://github.com/ton-connect/sdk/tree/main/packages/ui-react)
- [NPM](https://www.npmjs.com/package/@tonconnect/ui-react)
- [TON Connect UI React API Documentation](https://ton-connect.github.io/sdk/modules/_tonconnect_ui_react.html)

* Example of a dApp with @tonconnect/ui-react: [GitHub](https://github.com/ton-connect/demo-dapp-with-react-ui)
* Example of deployed demo-dapp-with-react-ui: [GitHub](https://ton-connect.github.io/demo-dapp-with-react-ui/)

## TON Connect UI

TonConnect UI is a UI kit for TonConnect SDK. Use it to connect your app to TON wallets via TonConnect protocol. It allows you to integrate TonConnect to your app easier using our UI elements such as "connect wallet button", "select wallet dialog" and confirmation modals.

- [GitHub](https://github.com/ton-connect/sdk/tree/main/packages/ui)
- [NPM](https://www.npmjs.com/package/@tonconnect/ui)
- [TON Connect UI API Documentation](https://ton-connect.github.io/sdk/modules/_tonconnect_ui.html)


The TON Connect User Interface (UI) is a framework that allows developers to improve the user experience (UX) for application users. TON Connect can easily be integrated with apps using simple UI elements such as the "connect wallet button", "select wallet dialog" and confirmation modals. Here are three main examples of how TON Connect improves UX in apps:

* Example of app functionality in the dApp browser: [GitHub](https://ton-connect.github.io/demo-dapp/)

* Example of a backend partition of the dApp above: [GitHub](https://github.com/ton-connect/demo-dapp-backend)

* Bridge server using Go: [GitHub](https://github.com/ton-connect/bridge)


This kit will simplify the implementation of TON Connect in apps built for TON Blockchain. Standard frontend frameworks are supported, as well as applications that don’t use predetermined frameworks


## TON Connect SDK

The first of the three frameworks that helps developers integrate TON Connect into their applications is the TON Connect SDK. It is primarily used to connect apps to TON Wallets via the TON Connect protocol.

- [GitHub](https://github.com/ton-connect/sdk/tree/main/packages/sdk)
- [NPM](https://www.npmjs.com/package/@tonconnect/sdk)

## TON Connect protocol models

This package contains protocol requests, protocol responses, event models and encoding and decoding functions. It can be used to integrate TON Connect to wallet apps written in TypeScript. In order to integrate TON Connect into a dApp the [@tonconnect/sdk](https://www.npmjs.com/package/@tonconnect/sdk) should be used.

- [GitHub](https://github.com/ton-connect/sdk/tree/main/packages/protocol)
- [NPM](https://www.npmjs.com/package/@tonconnect/protocol)



## TON Connect Python

Example of checking proof from Ton Connect on Python

https://github.com/disintar/ton-connect-python-proof/blob/master/check_proof.ipynb

## General Questions and Concerns

If any of our developers or community members encounter any additional issues during the implementation of TON Connect 2.0, please contact the [Tonkeeper developer](https://t.me/tonkeeperdev) channel.

If you experience any additional issues, or would like to present a proposal on how to improve TON Connect 2.0, please contact us directly through the appropriate [GitHub directory](https://github.com/ton-connect/).

## See Also

* [Ton Connect Getting started](https://github.com/ton-connect/sdk/tree/main/packages/sdk)
* [Integration Manual](/develop/dapps/ton-connect/integration)