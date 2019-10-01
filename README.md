[![Build Status](https://dev.azure.com/mimblewimble/grin-wallet/_apis/build/status/mimblewimble.bitgrin-wallet?branchName=master)](https://dev.azure.com/mimblewimble/grin-wallet/_build/latest?definitionId=3&branchName=master)
[![Coverage Status](https://img.shields.io/codecov/c/github/mimblewimble/grin-wallet/master.svg)](https://codecov.io/gh/mimblewimble/grin-wallet)
[![Chat](https://img.shields.io/gitter/room/grin_community/Lobby.svg)](https://gitter.im/grin_community/Lobby)
[![Support](https://img.shields.io/badge/support-on%20gitter-brightgreen.svg)](https://gitter.im/grin_community/support)
[![Documentation Wiki](https://img.shields.io/badge/doc-wiki-blue.svg)](https://github.com/mimblewimble/docs/wiki)
[![Release Version](https://img.shields.io/github/release/mimblewimble/grin-wallet.svg)](https://github.com/mimblewimble/grin-wallet/releases)
[![License](https://img.shields.io/github/license/mimblewimble/grin-wallet.svg)](https://github.com/mimblewimble/grin-wallet/blob/master/LICENSE)

# Bitgrin Wallet

This is the reference implementation of [Bitgrin's](https://github.com/bitgrin/bitgrin-wallet) wallet. It consists of 2 major pieces:

* The Bitgrin Wallet APIs, which are intended for use by Bitgrin community wallet developers. The wallet APIs can be directly linked into other projects or invoked via a JSON-RPC interface.

* A reference command-line wallet, which provides a baseline wallet for Bitgrin and demonstrates how the wallet APIs should be called.

# Installation
```
curl -sLO https://github.com/bitgrin/bitgrin-wallet/releases/download/v2.0.2/bitgrin-wallet_2.0.2_amd64.deb && sudo dpkg -i bitgrin-wallet_2.0.2_amd64.deb && rm bitgrin-wallet_2.0.2_amd64.deb
```

# Usage

To use the command-line wallet, we recommend using the latest release from the [Releases page](https://github.com/mimblewimble/grin-wallet/releases). There are distributions for Linux, MacOS and Windows.

Full documentation outlining how to use the command line wallet can be found on [Grin's Wiki](https://github.com/mimblewimble/docs/wiki/Wallet-User-Guide)

# License

Apache License v2.0

