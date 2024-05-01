---
title: "Shapella’s Show"
author: "Arthur Hayes"
date: 2023-04-11T23:01:50.136+0000
last_modified_at: 2023-04-12T07:54:19.032+0000
categories: "Entrepreneurship Handbook"
tags: ["ethereum","cryptocurrency","trading","bitcoin","cryptohandbook"]
description: "(Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor…"
image:
  path: /assets/e63d52378f7/0*0bJHXRqSPDFe-6LL
---

### Shapella’s Show

_\(Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor be construed as a recommendation or advice to engage in investment transactions\. \)_


![](assets/e63d52378f7/0*0bJHXRqSPDFe-6LL)


As y’all know, I don’t fuck for free\. While I love disseminating knowledge about macro and crypto for free on this blog, I gotta eat too\. Bubbly water in the clerb ain’t cheap\. In December of last year, I launched my crypto family office, [Maelstrom](https://maelstrom.fund) \. I hired BitMEX’s former head of corporate development, [Akshat Vaidya](https://hk.linkedin.com/in/akshatvaidya) , to run around the world looking for worthy crypto projects to invest in\. Our goal is to invest in early stage projects that will deliver excess returns over just holding Bitcoin and Ether\.

Moving forward, every once in a while, Akshat will grace readers with a thinkpiece on a crypto vertical that he is very excited about\. Obviously, we are shilling our bags, but we’re also trying to educate the market on why the problems these projects are trying to solve are important to the goal of furthering decentralisation\. Ultimately, we want to help power the teams that will completely destroy — \*ahem\* I mean, offer an alternative — to the parasitic, rancid TradFi financial system\.

The below think piece speaks about the overall movement to decentralise validators of the Ethereum network\. This space is super exciting, and I expressed a bullish view on the Ethereum Merge via increasing the percentage of Ether in my portfolio and purchasing LIDO \(the governance token of Lido Finance\) \. In the back of my mind, though, I always worried that Lido was not sufficiently decentralised, and that once the market started caring about this, the coin would tank\. After Akshat invested in Obol and ether\.fi and explained his rationale for doing so, I knew it was time to dump my Lido position, which I did recently\. Read on to understand our thought process in more detail\.
### Shapella’s Show: ETH Staking’s Coming Shake\-Up

**_By: Akshat Vaidya, Head of Investments @ Maelstrom_**


![](assets/e63d52378f7/0*aGmGighjEDmP-aOG)


“Not your keys, not your crypto” has been the industry’s motto for as long as I’ve been in this space\. But time and time again, traders, customers, and even founders and name\-brand fund managers continue to fuck this up\. Far too many keep repeating the same mistake again and again, cycle after cycle, of giving up control of their private keys — resulting in billions of dollars’ worth of lost or stolen funds \(from Mt\. Gox to FTX, and [everything in between](https://www.hedgewithcrypto.com/cryptocurrency-exchange-hacks/) \) \.

Prior to DeFi Summer \(circa 2020\), clients typically lost funds on poorly managed or outright fraudulent CeFi exchanges\. But in 2021–2022, this issue reared its head in a new way — with a number of so\-called “decentralized” \(but still ultimately custodial\) cross\-chain bridges [compromised, to the tune of $2\.5B](https://twitter.com/tokenterminal/status/1582376876143968256/photo/1) \(e\.g\., the $586MM BNB Bridge exploit\) \. Once again, individuals that voluntarily gave third\-parties access to their private keys got rekt, and were reminded once more that “code is law\.”

Giving up access to our private keys — to either centralized or “decentralized” entities — is **not** a compromise any of us should have to make, given infrastructure capabilities inherent to blockchains\. **Yet here we are in 2023, playing with fire all over again in our collective thirst for easy ETH staking rewards\.**

Post\-DeFi Summer, we have come to expect yield on our crypto — particularly on our ETH, and even more so now given recent Fed rate hikes\. However, since setting up a validator is still hard _\[if you’re working on elegant solutions to help bring down technical barriers to solo\-staking, [ping me](https://twitter.com/akshat_hk) \]_ , customers have found themselves forced to make a false choice between using staking services that are dangerously custodial in nature, and simply letting their ETH sit idle\. Worryingly, [too many](https://pro.nansen.ai/eth2-deposit-contract) have chosen the former, entrusting their private keys to the likes of **1\)** **fully centralized** services like Coinbase, Kraken and Binance; and **2\)** **proto\-decentralized** ETH liquid staking derivative \(“LSD”\) protocols like Lido Finance\. To be fair, these custodial projects have served as important steppingstones towards the trustless, decentralized future of ETH staking\. However, they also prioritized speed\-to\-market at the expense of exposing stakers to potentially substantial operator, regulatory and security counterparty risks\.

**Fortunately, that false choice ends starting now\.** The Shanghai\-Cappella \(“Shapella”\) upgrade, set to take hold in the next 24 hours, will allow stakers to withdraw staked ETH for the first time \(at a rate of 0\.4% of total staked ETH per day\) \. [18 million\+ ETH](https://etherscan.io/address/0x00000000219ab540356cbb839cbe05303d7705fa) \(~15% of all ETH in circulation, worth tens of billions of dollars\) is about to be unshackled from the previously mentioned risk\-prone, custodial staking business models of the past\. These incumbents have the most to lose in terms of their existing market share of staked ETH, and possibly the least to gain from the tens of millions of forthcoming ETH about to be staked over the coming years\. And of these incumbents, Lido — the largest and first proto\-decentralized LSD protocol — might be the biggest \(slowly\) ticking time bomb of them all\.

Let’s unpack how Shapella might pave the pathway for Lido’s ETH staking dominance to crack\.

Lido, which accounts for ~75% of all ETH locked in LSD protocols, and ~30% of staked ETH overall, is essentially built upon stakers’ faith in the trustworthiness of node operators:
- Stakers deposit ETH with no contribution from node operators _\(unlike Rocketpool’s model, where node operators contribute 16 of the 32 ETH for each validator\)_ ;
- Node operators, not stakers, generate keys _\( [including both BLS private keys, as well as validator keys](https://docs.lido.fi/guides/node-operator-manual/) \)_ , and execute the staked ETH:ETH redemption process **_on a voluntary basis_** _;_
- The implication being, that stakers do not hold a direct claim on either their ETH or staking rewards, but only over a pool of hypothetical assets generated by the protocol itself \(analogous to the business model of cross\-chain bridge Wormhole, [hacked last year for ~$321MM of its own similarly hypothetical ETH\-derived asset](https://cointelegraph.com/news/wormhole-token-bridge-loses-321m-in-largest-hack-so-far-in-2022) \) \.


To be clear — Lido works because node operators choose to play ball\. Period\.

If node operators, for whatever reason, are unwilling or unable to exit their validators in order to give you “your” ETH or “your” staking rewards, you’ve got a problem\. Of course, there are meaningful steps Lido has taken to mitigate the risk that a major event — such as a hack compromising validator keys, or regulatory/legal action preventing node operators from releasing ETH — spirals out into a market panic\. _\[…At least by design\. Lido’s entire redemption process will only be tested live, at scale, for the first time starting April 12th after Shapella, since it’s thus far been a one\-way street\]_ \. But regardless, ultimately node operators can simply refuse to exit, effectively rendering “your” staked ETH illiquid and inaccessible for a period of time, with limited downside risks borne by node operators\.

**TL;DR: Lido’s revenue model \(and that of its node operators\) depends on you not only giving up your private keys, but also bearing the majority of the risk\. All for just…4–6% yield on your precious asset\. Sound familiar?**

**Fortunately, this is a risk none of us need to take anymore\.**

Lido was architected well before we knew what we do now — i\.e\., that [withdrawal credentials sitting on the execution layer is not enough to make an LSD protocol non\-custodial](https://ethresear.ch/t/withdrawal-credentials-exits-based-on-a-generalized-message-bus/12516/6) \. We now know that it is not possible to simply create a smart contract\-controlled redemption mechanism as a workaround\. So, what if we could do it all over again post\-Shapella? Knowing what we know now, how would we design Ethereum staking services that are both _non\-custodial_ and _still scalable_ ?

We launched Maelstrom, the family office of BitMEX co\-founder Arthur Hayes, in December 2022, amidst the wreckage of numerous collapsed custodial business models, to invest in projects fixing what went wrong\. We are backing teams committed to delivering on the full potential of blockchain — a scalable, privacy\-enhancing, decentralized, non\-custodial and interoperable stack of infrastructure capable of unleashing new trillion\-dollar markets across various use cases\.

To that end, we are starting with primitives, and investing in ETH staking infrastructure projects that **1\)** compete directly with the two risk\-prone custodial business models described above \(both fully centralized and proto\-decentralized\); and **2\)** those that are complementary with these same legacy incumbents to help them \(as well as new entrants\) further decentralize\.
- Maelstrom’s debut investment was in an early mover in that second category, a project that isn’t competing with either the Lidos or the Coinbases of the world, but rather tooling them to eliminate single points of failure\. [Obol Labs](https://twitter.com/ObolNetwork) , an investment we closed in January this year, is helping solo\-stakers as well as fully centralized, proto\-decentralized and genuinely non\-custodial _\[see next bullet\]_ services alike further decentralize\. Obol’s distributed validator technology \(“DVT”\) middleware allows validator keys to be “split” among multiple node operators, effectively creating a “multi\-sig” validator that can be run simultaneously across a collection of machines\. These multi\-validators still “speak” as one to the Beacon chain, avoiding penalties or slashing, while improving redundancy, security, and decentralization across the ETH staking space\. More [here](https://docs.obol.tech/) \.
- [ether\.fi](https://twitter.com/ether_fi) , on the other hand, is our first investment in a project aiming to bring about a stepwise evolution from the legacy custodial models of both Lido and Coinbase\. ether\.fi is building one of the first **genuinely non\-custodial, delegated staking services for Ethereum** \(and other PoS networks in the future\) \. In a post\-Shapella world, where stakers are able to freely bounce from staking service to staking service to chase the highest yield, ether\.fi circumvents the impending race to the bottom by competing on something other than just APY\. With ether\.fi, stakers generate and control their own keys throughout the staking process from creation to redemption, and can exit validators to claim their ETH back at any time, preventing node operator malfeasance\. I\.e\., “your keys, your crypto\.” ether\.fi’s non\-custodial model reduces risks for all parties, including node operators who will no longer be required to keep wallets connected or rely on a trusted middle party for coordination\. More on the mechanics [here](https://etherfi.gitbook.io/etherfi/) \.


Maelstrom is building a long\-term investment portfolio of infrastructure companies that will serve as the foundation of our trustless, decentralized future\. Giving up your private keys is **not** a compromise you need to make in order to participate in any decentralized ecosystem\. The existing, legacy players in ETH staking — be they centralized or proto\-decentralized — had prioritized speed\-to\-market during this past crypto Summer\. But storm clouds are swirling over these incumbents, as new projects offering trustless, truly non\-custodial ETH staking solutions are being built and scaled this Winter\. And with today’s Shappela upgrade, the shackles are finally coming off\.



_[Post](https://ehandbook.com/shapellas-show-e63d52378f7) converted from Medium by [ZMediumToMarkdown](https://github.com/ZhgChgLi/ZMediumToMarkdown)._
