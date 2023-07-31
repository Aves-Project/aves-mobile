Source code forked from https://github.com/walleth/walleth, refactored and adapted for Aves chain.
Api level changed from 30 to 31.






# AvesWallet

Native Android Ethereum wallet.

# Features

## Hardware Wallet Support

 * [TREZOR](https://trezor.io) Support via USB-OTG - model 1 and model T are supported
 * [KeyCard](https://keycard.status.im) 
 * [KeepKey](https://shapeshift.com/keepkey)

## other Account types
 
 * Watch only
 * PIN protected
 * Password protected
 * Burner style accounts
 * Key Import ( JSON UTC, RAW and Mnemonics)

## Networks (Chains)
 * main, görli, rinkeby, ropsten, kovan, POA, sokol, ETC, xDAI, ...
 * load all chains from [chainid.network](https://chainId.network)
 * [DappNode](https://dappnode.io) support
 * Testnets with direct link to faucets (on görli and ropsten even auto-fill of address)
 * one flavor contains go-ethereum light client

## UI
 * Day/Night mode (Dark mode)
 * display information about Security of the phone
 * [Sourcify](https://sourcify.dev) support
 * display function calls when available from https://github.com/ethereum-lists/4bytes (fallback if contracts are not verified on Sourcify)
 * Keys on your device under your control
 * Tokens (your own ERC-20 compatible or predefined like DAI, Unicorn, OMG, SNT, ZRC, GNO, ..) - add your own in the app or on [https://github.com/ethereum-lists/tokens](https://github.com/ethereum-lists/tokens) so everyone can use it
 * display value in fiat like EUR, NZD, USD, .. or MakerDAO DAI

## Standards
 - ERC-67 / ERC-681 / ERC-1328 URLs (e.g. scanned from QR-Code or via intent)
 - ERC-55 Checksums
 * EIP712 signing
 * EIP155 Transactions

## Other
 - [WalletConnect](https://walletconnect.org) 1.0 Support
 - Offline signing (compatible to Parity signing flow)


 
License
=======

GPL
