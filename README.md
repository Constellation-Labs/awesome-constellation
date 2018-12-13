
[comment]: <The target audience for this list is mainly be github visiting types, i.e. developers.> 
[comment]: <Provide links with information, not explanations and not advertisment.>

<p align="center"><img src="https://i.imgur.com/FjE9pdz.png"></p>
<p align="center">:scroll:The curated resource list.</p>

[comment]: <No title header atm., as the logo functions as a title.>

### Table of Contents (short version)

[comment]: <First level content overview (i.e. ## markup headers)>

- :two_hearts:[Community](#community)
- :computer:[Development](#development)
- :microscope:[Research](#research)
- :moneybag:[The DAG Token](#the-dag-token)
- :art:[Design](#design)
- :milky_way:[About Constellation](#about-constellation)
- :loudspeaker:[Media](#merchandise)

### Wait, there's more ...

This repository provides links to information within the Constellation ecosystem, the primary target audience being software developers and community contributors. 
As of today (October 2018), our core focus is on developing the protocol. To deep dive into the reference implementation, check out the docs.
If you want to understand how Constellation fits into the crypto space at large, the wiki might be the place to start. 

* [constellation/docs](https://github.com/Constellation-Labs/constellation/tree/dev/docs)
* [constellation/wiki](https://github.com/Constellation-Labs/constellation/wiki)

[comment]: <Note that we link to the development branch here, which is updated more often.>

## Table of Contents

[comment]: <First and second level content overview (i.e. ## and ### markup headers)>

- :two_hearts:[Community](#community)
- :computer:[Development](#development)
	* [Guidelines](#guidelines)
	* [Code Base](#code-base)
	* [Documentation](#documentation)
	* [Tutorials](#tutorials)
	* [SDK](#sdk)
	* [Ledger Bootstrap Files](#ledger-bootstrap-files)
	* [Network monitoring](#network-monitoring)
	* [Languages](#languages)
- :microscope:[Research](#research)
- :moneybag:[The DAG Token](#the-dag-token)
	* [Explorers](#explorers)
	* [Exchanges](#exchanges)
	* [Employees](#employees)
	* [Business](#business)
	* [Orion Community Portal](#orion-community-portal)
- :art:[Design](#design)
	* [Visual Identity](#visual-identity)
 	* [Merchandise](#merchandise)
- :milky_way:[About Constellation](#about-constellation)
	* [Employees](#employees)
 	* [Business](#business)
- :loudspeaker:[Media](#media)
	* [Article and news Outlets](#article-and-news-outlets)

[comment]: <Make sure to fix all the links if you change a section header below!>
	
---

## Community

[comment]: <Listed roughly in order of relevance.>

Our static knowledge, news and discussion outlet is the 
[community portal **Orion**](https://orion.constellationlabs.io/accounts/login/?next=/)
discourse forum. Join our 
[discord](https://discordapp.com/invite/KMSmXbV) 
server for a chat. 

  <a href="https://discordapp.com/invite/KMSmXbV">
	  <img src="https://img.shields.io/badge/chat-discord-brightgreen.svg"/>
  </a>


Please also have a look at the 
[guidelines](https://github.com/Constellation-Labs/constellation/wiki/Contribution-guidelines) 
for contributions and troubleshooting, bug reports, support, etc.

- [Orion](https://orion.constellationlabs.io/accounts/login/?next=/)
- [Discord](https://discordapp.com/invite/KMSmXbV)
- [Reddit](https://www.reddit.com/r/constellation)
- Telegram: [**Community**](https://t.me/constellationcommunity)
| [**Traders**](https://t.me/constellationtrader)
| [Airdrop Info](https://t.me/constellationcommunityairdrop)
| [Brasilian](https://t.me/constellationbrasil)
| [Russian](https://t.me/Constellation_Russian)
| [Korean](https://t.me/constellationcommunity_KOR)


---

## Development

[comment]: <The following is why we ended up on github in the first place!>

### Guidelines

For standards on code style, reporting troubleshooting and issues, pull requests and so on, check out
[/wiki/Contribution-guidelines](https://github.com/Constellation-Labs/constellation/wiki/Contribution-guidelines).

### Code Base

[comment]: <Listed in order of current relevance and what's being worked on.>

- [github root](https://github.com/Constellation-Labs) - Official public Constellation repositories.
- [constellation](https://github.com/Constellation-Labs/constellation) - Core reference implementation in [Scala](https://www.scala-lang.org/).

### Running a node

For now we onboard people to our private testnet that apply [in the form on this Orion thread](https://community.constellationlabs.io/t/launch-and-operate-an-inaugural-constellation-testnet-node/891) 

You find the documentation down below and more is coming, as well as more support for terraform and docker.

If you have questions, ask in the #testnet chat on [Discord](https://discordapp.com/invite/KMSmXbV). The node-operators discuss know-how and hotfixes in #node-operators.

#### Minimal specs

```haskell
    CPU::      2-core minimum.
    Memory:    3 GB or higher
    Disk:      50-200 GB available.
    Software:  Java 8.x
```
Make sure the relevant ports are open / not firewalled. 

### Documentation

- [Documentation web page](https://constellation-labs.github.io/constellation/)
	* [running-a-node](https://constellation-labs.github.io/constellation/running-a-node/)
- [constellation/docs](https://github.com/Constellation-Labs/constellation/tree/dev/docs)
	* [architecture](https://github.com/Constellation-Labs/constellation/blob/developer/nikolaj/add-docs/docs/architecture.md)
	* [build-instructions](https://github.com/Constellation-Labs/constellation/blob/developer/nikolaj/add-docs/docs/build-instructions.md)
	* ...
- [constellation/wiki](https://github.com/Constellation-Labs/constellation/wiki)
	* [Constellation Glossary](https://github.com/Constellation-Labs/constellation/wiki/Constellation-Glossary)
	* [Roadmap](https://github.com/Constellation-Labs/constellation/wiki/Roadmap)
	* [Discussion and comparison against other projects](https://github.com/Constellation-Labs/constellation/wiki/Comparisons-to-other-protocols)
	* [Recommended reading](https://github.com/Constellation-Labs/constellation/wiki/Recommended-Reading)
	* [FAQ](https://github.com/Constellation-Labs/constellation/wiki/FAQ)
	* [Code contribution guidelines](https://github.com/Constellation-Labs/constellation/wiki/contribution-guidelines)

#### Build Instructions

- [constellation/dev/docs/build-instructions.md](https://github.com/Constellation-Labs/constellation/blob/dev/docs/build-instructions.md)

#### Software dependencies

- [constellation/dev/docs/software-dependencies.md](https://github.com/Constellation-Labs/constellation/blob/dev/docs/software-dependencies.md)

Beyond the core implementation of the protocol, possible requirements include

- [docker](https://www.docker.com/) - see also [Wikipedia](https://en.wikipedia.org/wiki/Docker_(software))
- [vagrant](https://www.vagrantup.com/) - see also [Wikipedia](https://en.wikipedia.org/wiki/Vagrant_(software))

### Tutorials

#### Third Party
- [Circleci](https://circleci.com/) - for our [continuous integration](https://en.wikipedia.org/wiki/Continuous_integration)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) - formatting for files like this
- [github emojis](https://gist.github.com/rxaviers/7360908) 

### Ledger Bootstrap Files

#### Mainnet

We're currently running on a testnet. 
If you want to take part during this phase, [register here](https://docs.google.com/forms/d/e/1FAIpQLSeYZVXBu2zbiAwk6IDofHkxswurM-lxmzCaY_lMXytD1NCMXw/viewform?_hsenc=p2ANqtz-_cQXKsV4sWNaOpbmtqMuoNnENd8wgEBpYkEv2Wun-xYBd4iEPUfzFHcN1gCItLKnGaFM3tZJtR1FJSO6paUmLpMEoBeA&_hsmi=67965834) to run a node.

#### Testnet

- (tbd) - dd/mm/yyyy
- (tbd) - dd/mm/yyyy

### dApps

#### List of decentralized applications on Constellation

##### On Testnet

(tbd.)

##### On Mainnet

We're currently running on a testnet.

### Network Monitoring

- You may check out the [testnet visualizer](https://testnet.constellationlabs.io/)
- See also the blockpost [blog/tps-benchmarking](https://constellationlabs.io/blog/index.php/network-stability-update/)
- For the Etheruem token, see [explorers](#explorers)

#### Code Examples

(tbd)

### SDK

(tbd)

### Languages

#### Scala

- [Scala | Wikipedia](https://en.wikipedia.org/wiki/Scala_(programming_language))
- [Scala | Official website](https://www.scala-lang.org/)
- [Akka | Docs](https://akka.io/docs/) - Actor model supporting concurrent computing

(todo: Kotlin section, Javascript section,...)

---

## Research

For literature resources, a Constellation and technical comparisons and reviews of other projects in the space, check out the wiki

- [/constellation/wiki/Recommended-Reading](https://github.com/Constellation-Labs/constellation/wiki/Recommended-Reading)
- [/constellation/wiki/FAQ](https://github.com/Constellation-Labs/constellation/wiki/FAQ)
- [/constellation/wiki/Comparisons-to-other-protocols](https://github.com/Constellation-Labs/constellation/wiki/Comparisons-to-other-protocols)

---

## The DAG Token

DAG is currently an ERC-20 token on the 
[Ethereum](https://www.ethereum.org/) 
blockchain and, as such, supported by various Ethereum wallets. You'll find support on the #support channel on the 
[discord](https://discordapp.com/) 
server. Total supply is 4b of which about 1b is circulating some over 2b will be rewarded to validators as well as contributions and project. Lots of information about the token has been posted on the 
[official blog](https://constellationlabs.io/blog/) 
on the official homepage. 

### Wallets

- [Metamask](https://metamask.io) - Browser plugin wallet
- [MyEtherWallet](http://myetherwallet.com/) - Browser wallet

MyEtherWallet tutorial:

- [How to ... add DAG to MyEtherWallet | Orion](https://community.constellationlabs.io/t/adding-dag-to-myetherwallet-mew/1892)

### Explorers

The Ethereum contract hash is `0xA8258AbC8f2811dd48EccD209db68F25E3E34667`.

- [DAG token tracker | Etherscan](https://etherscan.io/token/0xa8258abc8f2811dd48eccd209db68f25e3e34667)
- [DAG contract | Etherscan](https://etherscan.io/address/0xa8258abc8f2811dd48eccd209db68f25e3e34667)

### Exchanges

- [Kucoin | DAG-BTC](https://www.kucoin.com/#/trade.pro/DAG-BTC)
- [Kucoin | DAG-ETH](https://www.kucoin.com/#/trade.pro/DAG-ETH)
- [HitBit | DAG-BTC](https://hitbtc.com/DAG-to-BTC)
- [HitBit | DAG-ETH](https://hitbtc.com/DAG-to-BTC)
- also Hotbit, IDEX, DEx.top, Bilaxy, etc.

See the *Markets tab* on [coinmarketcap.com](https://coinmarketcap.com/currencies/constellation/#markets).

### Tokenomics
- [blog/tokenomics-update](https://constellationlabs.io/blog/index.php/tokenomics-update/)

### Airdrop

As noted in the 
[Community section](#community), 
be aware that there is a 
[Telegram for Airdrops](https://t.me/constellationcommunityairdrop). 

---

## Design

### Visual Identity

The 
[visual-identity](https://github.com/Constellation-Labs/visual-identity)
repository holds hundrets of graphics material for the Constellation brand. See e.g. the
[/logo](https://github.com/Constellation-Labs/visual-identity/tree/master/logo) 
folder. Here is 
[a video](https://community.constellationlabs.io/t/a-video-analyzing-and-quickly-scripting-the-constellation-logo-using-python/1942)
explaining the specification of the latter.

### Merchandise

If you look for basic branded items, the [cryptothings](https://cryptothings.store/product-category/constellation/) store sells some.

---

## About Constellation

- [Official website](https://constellationlabs.io/) - for information about our roadmap, our team, the newsletter and more
- [Link list | linktr](https://linktr.ee/constellation_labs) - for blogs and announcements.

For a broad motivation of the project, check out the
[/whitepaper_v1 (business, 2018)](https://github.com/Constellation-Labs/whitepaper_v1).

### Employees

[Brion](https://www.linkedin.com/in/brionhickey/),
[Gina](https://www.linkedin.com/in/ginarubino/),
[Giovanni](https://www.linkedin.com/in/giovannigastelum/),
[James](https://www.linkedin.com/in/james-markotic/),
[Mathias](https://www.linkedin.com/in/mathias-goldmann-711a85110/) (Finance, see [introduction video](https://youtu.be/kDI3IKtEmb8))
[Preston](https://www.linkedin.com/in/prestonparris/) (Dev.),
[Ryle](https://www.linkedin.com/in/ryle-goehausen-27bb5876/) (VP of Eng.),
[Tyler](https://www.linkedin.com/in/tylerprete/) (Dev.),
[Wyatt](https://www.linkedin.com/in/wlmeldmanfloch/) (CTO),
[Zac](https://www.linkedin.com/in/zac-russell-62b2a923/), 
as well as 
[Mr Diggles](https://www.linkedin.com/in/mrdiggles/),
[scarpulla11](https://www.linkedin.com/in/scarpulla11/), ...

### Business

#### Strategy

* [cbinsights on edge computing](www.cbinsights.com/research/what-is-edge-computing/)

(tbd: consensus-as-a-service)

#### Partners

* [Hyperledger](https://www.hyperledger.org/members)
* [MOBI](https://www.dlt.mobi/)

---

## Media

### Article and news Outlets

For video and text material from the source, see

- [Official blog](https://constellationlabs.io/blog/)
- [YouTube](https://www.youtube.com/channel/UChMBV4al3p_iO4bnfzcIzVQ)
- [Medium](https://medium.com/constellationlabs)

and then the open community section above, e.g. with 
[Reddit](https://www.reddit.com/r/constellation). 
Beyond that, there's 
[LinkedIn](https://www.linkedin.com/company/constellation-labs/),
[Twitter](https://twitter.com/conste11ation),
[Facebook](https://www.facebook.com/Conste11ation),
[Instagram](https://www.instagram.com/constellation_labs),
[Quora](https://www.quora.com/profile/Constellation-Labs-1), 
etc.

---

<p align="center">
	:two_hearts: We wholeheartedly welcome projects, designs, corrections and so forth. If you have an aha!-moment, consider creating a short write-up or tutorial to be credited here. See also the Guidelines section.
</p>

<p align="center">
	The layout of this file was drawn from the <a href="http://cityofzion.io/">CoZ</a> open source developer community.
</p>
