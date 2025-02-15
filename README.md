<h1 align="center">
<img src="https://imgur.com/a/79LVoCh.png" alt="Pandacoin" width="300"/>
<br/><br/>
Pandacoin Core [PANDA, ⱣDC]
</h1>

Select language: EN | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | [FR](./README_fr_FR.md) | [JA](./README_ja_JP.md) | [DE](./README_de_DE.md)

Pandacoin is a community focused cryptocurrency created by one of the original Dogecoin shibes from 2013. It was created for one purpose, to create a new and fun community just like the original Dogecoin community.

Unlike all iterations before it, Pandacoin is a layer 1 coin. This means there are no liquidity pools to drain, no blacklisting wallets, and no confusing smart contracts. Pandacoin is a simple blockchain.

The Pandacoin Core software allows anyone to operate a node in the Pandacoin blockchain networks and uses the Scrypt hashing method for Proof of Work. It is adapted from Dogecoin Core, Bitcoin Core, and other cryptocurrencies.

For information about the default fees used on the Pandacoin network, please
refer to the [fee recommendation](doc/fee-recommendation.md).

**Website:** [pandacoinfnd.org](https://pandacoinfnd.org)

## Dogecoin Differences

Pandacoin is a fork of Dogecoin. For the sake of familiarity, we will attempt to keep Pandacoin similar to Dogecoin.

Changes:

* Addresses start with `Pdc` instead of `D`
* BIPS features will start block 1000
* AuxPow starts at block 42,000 (Chain ID: 63)
* GUI themed for Pepecoin

## Usage 💻

To start your journey with Pandacoin Core, see the [installation guide](INSTALL.md) and the [getting started](doc/getting-started.md) tutorial.

The JSON-RPC API provided by Pandacoin Core is self-documenting and can be browsed with `pandacoin-cli help`, while detailed information for each command can be viewed with `pandacoin-cli help <command>`. Alternatively, see the [Bitcoin Core documentation](https://developer.bitcoin.org/reference/rpc/) - which implement a similar protocol - to get a browsable version.

### Ports

Pandacoin Core by default uses port `33874` for peer-to-peer communication that
is needed to synchronize the "mainnet" blockchain and stay informed of new
transactions and blocks. Additionally, a JSONRPC port can be opened, which
defaults to port `33873` for mainnet nodes. It is strongly recommended to not
expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   33874 |   44874 |   18444 |
| RPC      |   33873 |   44873 |   18332 |

## Ongoing development 💻

Pepecoin Core is an open source and community driven software. The development
process is open and publicly visible; anyone can see, discuss and work on the
software.

Main development resources:

* [GitHub Projects](https://github.com/pandacoinppc/pandacoin/projects) is used to
  follow planned and in-progress work for upcoming releases.
* [GitHub Discussion](https://github.com/pandacoinppc/pandacoin/discussions) is used
  to discuss features, planned and unplanned, related to both the development of
  the Pandacoin Core software, the underlying protocols and the PANDA asset.
* [PandacoinDev subreddit](https://www.reddit.com/r/ subreddit](https://www.reddit.com/r//)indev/)

### Version strategy
Version numbers are following ```major.minor.patch``` semantics.

### Branches
There are 3 types of branches in this repository:

- **master:** Stable, contains the latest version of the latest *major.minor* release.
- **maintenance:** Stable, contains the latest version of previous releases, which are still under active maintenance. Format: ```<version>-maint```
- **development:** Unstable, contains new code for planned releases. Format: ```<version>-dev```

*Master and maintenance branches are exclusively mutable by release. Planned*
*releases will always have a development branch and pull requests should be*
*submitted against those. Maintenance branches are there for **bug fixes only,***
*please submit new features against the development branch with the highest version.*

## Contributing 🤝

If you find a bug or experience issues with this software, please report it
using the [issue system](https://github.com/pandacoinpdc/pandacoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Please see [the contribution guide](CONTRIBUTING.md) to see how you can
participate in the development of Pepecoin Core. There are often
[topics seeking help](https://github.com/pandacoinpdc/pandacoin/labels/help%20wanted)
where your contributions will have high impact and get very appreciation.

## Communities 🐸

You can join the communities on different social media.
To see what's going on, meet people & discuss, find the latest meme, learn
about Pepecoin, give or ask for help, to share your project.

Here are some places to visit:

* [r/Pandacoin](https://www.reddit.com/r//)
* [Discord](https:///discord)
* [Telegram](https://t.me/PandacoinGroup)
* [Twitter/X](https://twitter.com/Pandacoinfnd)

## Frequently Asked Questions ❓

Do you have a question regarding Pepecoin? An answer is perhaps already in the [FAQ](doc/FAQ.md) or the [Q&A section](https://github.com/pandacoinpdc/pandacoin/discussions/categories/q-a) of the discussion board!

## License ⚖️
Pepecoin Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)
