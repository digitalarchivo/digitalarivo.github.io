---
title: "Luna Brothers, Inc."
author: "Arthur Hayes"
date: 2022-05-12T23:02:30.715+0000
last_modified_at: 2022-05-13T14:04:46.757+0000
categories: "Entrepreneurship Handbook"
tags: ["cryptocurrency","ethereum","bitcoin","defi","cryptohandbook"]
description: "(Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor…"
image:
  path: /assets/712ec5abe199/0*HV-0xKRbcfjqR7l6
---

### Luna Brothers, Inc\.

\( _Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor be construed as a recommendation or advice to engage in investment transactions\._ \)


![](assets/712ec5abe199/0*HV-0xKRbcfjqR7l6)


There is shockingly little that we as humans can actually control about our existence in this universe\. Even so, we as a civilization spend an inordinate amount of energy bringing calm and stasis to a volatile earth\. Just the act of regulating temperature both upwards and downwards inside our dwellings and workplaces requires the consumption of a vast amount of energy\.

Because we instinctively understand that we are but reeds blowing randomly in the wind, humans confer immense power upon those individuals and institutions that offer the siren song of tranquillity\. Our politicians tell us they have a plan, our corporate chieftains chart the path forward to future profitability, and we follow in hopes that yesterday, today, and tomorrow will exhibit the same qualities\. But the universe throws unexpected haymakers time and time again, and the best laid plans of our leaders tend to fall woefully short\. But what can we do, but try and try again?

And just as our civic society projects calm, the money that powers civilisation must appear stable as well\. Fiat currencies are designed for slow depreciation over time\. Humans cannot fathom the loss of purchasing power over decades or centuries when juxtaposed with stable purchasing power measured over the course of days, weeks, and months\. We are attuned to believe that a dollar, euro, yen, etc\. today will buy the same amount of energy tomorrow\.

Bitcoin and the crypto movement it spawned act with extreme pathos, just as the rest of the universe does\. Lord Satoshi is a usurper at heart, and their love and wrath produce the externality of price volatility vs\. fiat currencies and pure energy itself\. While the Lord’s disciples proclaim to accept this volatility with unwavering faith, we are but humans — and sometimes, we stray from the golden path\. During difficult times, the golden calf of stablecoins present themselves to us, and it’s easy to find ourselves swayed by their sweet melodies — but many fail to recognise that they are fundamentally incompatible with the financial world we wish to create\.

Many ask me for my opinion on this or that stablecoin\. The recent volatility surrounding the 1 USD peg of Terra’s USD stablecoin, UST, has prompted me to begin what will be a series of essays on stablecoins and Central Bank Digital Currencies \(CDBC\) \. These two concepts are interlinked with the fundamental nature of a debt\-based, fractional banking system that dominates the global financial system\.

This essay will explore the broad categories of blockchain\-enabled stablecoins — including fiat\-asset\-backed, overcollateralised\-crypto, algorithmic, and Bitcoin\-backed stablecoins\. And while there’s no silver bullet solution yet, the final section of this essay will touch on my opinion on the best of the not\-entirely\-adequate ways we can currently marry the two incompatible systems: a Bitcoin\-backed, USD\-pegged stablecoin that is also an ERC\-20 / Ethereum Virtual Machine \(EVM\) compatible asset\.

In this time of heightened downside market volatility, the only solace is our breath\. Our actions and thoughts are not fully controllable, but we must breathe in and out slowly, methodically, and mindfully\. Only then can we faithfully bring forth the Lord’s good word\.

_“We Fremen have a saying: ‘God created Arrakis to train the faithful\.’ One cannot go against the word of God\.”_

_\- Paul Atreides, ‘Dune’_
### **Fiat Pegged Stables**

As I explained in [I Still Can’t Draw A Line](i-still-cant-draw-a-line-7d136d73e5ff) , banks are a public utility that operate the fiat value transfer network\. They help individuals and organisations conduct commerce\. Prior to the Bitcoin blockchain, banks were the only trusted intermediaries who could also perform these functions\. But even with Bitcoin in the picture, banks remain far and away the most popular intermediary, which has enabled certain banks to engage in reckless conduct — because they believe the government can print money to nominally bail them out for their imprudent practices\.

Banks charge a very substantial tax in terms of time and expense to move value between participants\. Given that we now have access to near\-instantaneous and free means of encrypted communications \(thanks, internet\! \), there is no reason why we must pay so much money and waste so much time paying one another\.

The Bitcoin blockchain created a competing peer\-to\-peer payments system with low time and monetary costs\. The problem for many is that the native asset Bitcoin is extremely volatile when benchmarked against fiat currencies and energy \(i\.e\., a barrel of oil\) \. To address this, the folks at Tether created the first USD\-pegged stablecoin using the Omni smart contract protocol built on top of Bitcoin\.

Tether created a new category of digital assets riding on a public blockchain that were backed 1:1 by fiat assets held in a banking institution, which we now call fiat\-backed stablecoins\. In the wake of Tether \(also known as USDT\) and USDC, a variety of other fiat\-backed stablecoins sprouted up, and the fiat assets under custody \(AUC\) held by each project ballooned as interest in these coins grew\. Currently, USDT and USDC combined have over $100 billion of fiat AUC\.

Because there are no real farm\-to\-table Bitcoin economies, we still pay for most things in USD or another fiat currency\. And because the traditional means of sending and receiving fiat are so costly and convoluted, the ability to bypass the expensive banking payments system and send each other fiat value instantaneously for a low cost is extremely valuable\. I would rather send someone USDT or USDC any day than attempt to navigate the byzantine and expensive global fiat banking payments system\.

The fundamental issue with this class of stablecoins is that it requires a willing bank to hold the fiat assets that back the token\. Not a single Satoshi or Wei of stablecoin transaction fees ends up in the pockets of a banker, but there is a cost to the bank to hold these vast sums of fiat assets\. As we know, the destruction of the time value of money by central bankers completely shattered the lending business model of commercial banks — making it a curious policy for them to agree to hold billions of dollars for protocols that aim to disintermediate them, with no identifiable upside\.

Fiat\-backed stablecoins want to use the storage facilities of banks, but pay them nothing for it\. That to me is a strategy that, at scale, will not survive\. A few billion isn’t going to cause a stink, but expecting commercial banks to allow the AUC of fiat backed stablecoins to reach into the trillions of dollars is pure folly\.

Fiat\-backed stablecoins will not be the payments solution that powers Web3 or a truly decentralised global economy\. They will not be allowed to grow big enough to properly service the world of internet\-connected entities that require fast, cheap, and secure digital payments\. [We saw this incongruity in action when the Federal Reserve prohibited Silvergate Bank from being the warehouse of Facebook’s Diem stablecoin](https://www.euromoney.com/article/29on3b1o0cnmyjv4aaha8/capital-markets/meta-finds-a-bad-moment-to-get-out-of-stablecoins) \. Had Diem launched, it instantaneously would have been one of the largest circulating currencies globally due to Facebook’s user base\. It would have competed directly with various banking\-rail\-enabled fiat currencies, and that was not allowed to happen\.

This fundamental issue was not lost on the crypto industry\. The next iteration of stablecoins was a series of projects that overcollateralised major cryptos in order to peg fiat value\.
### **Overcollateralised Crypto\-Backed Stables**

Put very simply, this class of stablecoins allows participants to mint a pegged fiat token in exchange for crypto collateral\. The most successful stablecoin of this type is MakerDAO\.

MakerDAO has two currencies\. Maker \(MKR\) is the token that governs the system\. It is akin to a share in a bank, but a bank that aims to have assets greater than liabilities\. The assets are various mega\-cap cryptos like Bitcoin and Ether, which are pledged to create the pegged USD token, DAI\.

**_1 DAI = 1 USD_**

You borrow DAI from MakerDAO in exchange for a certain amount of crypto collateral\. Because the price of the crypto collateral can decline in USD value, Maker will programmatically liquidate pledged collateral to satisfy the DAI loan\. This is done transparently on the Ethereum blockchain\. Therefore, it is possible to calculate the levels at which Maker must force liquidate positions\.


![](assets/712ec5abe199/0*68sdJalMQwpfP6DJ)


This is a chart of the percentage deviation of DAI vs\. its 1 USD peg\. A reading of 0% means that DAI held its peg perfectly\. As you can see, Maker does a good job holding its peg\.

The system is robust in that it has survived various price crashes of Bitcoin and Ether, with its DAI token still maintaining close to a 1 USD value in the open market\. The downside of this system is that it is overcollateralised\. It actually removes liquidity from the crypto capital markets in exchange for the stability of a pegged fiat asset\. As we know, stasis and calm are expensive, and volatility is free\.

MakerDAO and other overcollateralised stablecoins when taken to their f\(x\): maxima completely drain liquidity and collateral from the broader ecosystem\. Maker token holders can choose to introduce riskiness into the business model in return for greater income via lending out idle pledged collateral\. However, this introduces credit risk into the system\. Who are the credible borrowers that can reliably pay a positive interest rate in crypto terms, and what collateral do they pledge? Is that collateral pristine?

The benefit of fiat fractional banking is that the system can grow exponentially without draining all money good collateral from the economy\. These overcollateralised stablecoins fill a very important niche, but they will always be niche for the fundamental reasons described above\.

The next iteration of stablecoins aims to completely remove the link to any “hard” collateral, and are backed by nothing more than fancy algorithmic minting and burning schemes\. In theory, these algorithmic stablecoins could scale to meet the needs of a global decentralised economy\.
### **The Algorithm**

The stated goal of these stablecoins is to create a pegged asset with less than 1:1 crypto or fiat collateral\. Usually the goal is to use zero outside “hard” collateral to back the pegged stablecoin\.

Given Terra is the topic du jour, I will explain the mechanics of algo stablecoins using LUNA and UST as an example\.

LUNA is the governance token of the Terra ecosystem\.

UST is a stablecoin pegged to $1, and its “assets” are just LUNA tokens in circulation\.

Here is how the peg works:

**Expansion:** if 1 UST = 1\.01 USD, then UST is overvalued vs\. its peg\. In this situation, the protocol allows LUNA holders to swap 1 USD worth of LUNA for 1 UST\. The LUNA is burned or taken out of circulation, UST is minted or brought into circulation\. Given 1 UST = 1\.01 USD, traders earn a 0\.01 USD profit\. This acts as a procyclical amplifier of the price of LUNA because its supply decreases\.

**Contraction \(where we are right now\):** if 1 UST = 0\.99 USD then UST is undervalued vs\. its peg\. In this situation, the protocol allows UST holders to swap 1 UST for 1 USD worth of LUNA\. Given that you can buy 1 UST for 0\.99 USD and exchange for 1 USD worth of LUNA, you profit 0\.01 USD\. UST is burned, and LUNA is minted\. This acts as a procyclical amplifier of the downward price movement of LUNA because its supply increases on the way down\. The big problem is that investors who now have newly minted LUNA will decide its better to sell it immediately rather than holding it in hopes the price pumps\. That is why there is constant sell pressure on LUNA when UST trades at a substantial discount to its peg\.

LUNA is perceived to be more valuable the more UST is used in commerce across the Web3 decentralised economy\. This mint and burn mechanism is great on the way up, or when UST is growing in popularity, but if UST can’t hold its peg on the downside the death spiral can begin with LUNA being minted ad infinitum in an attempt to bring UST back to parity with its peg\.

All algo stablecoins feature some sort of mint / burn interplay between the governance token and the pegged stablecoin\. And all of these protocols have the same issue of how to entice people to prop up the peg when the pegged stable trades at a significant discount to the fiat peg\.

Just about every algorithmic stablecoin has failed spectacularly due to the death spiral phenomenon\. If the price of the governance token declines, then the governance token asset backing the pegged token is not viewed as credible by the market\. At that point, the participants begin dumping their pegged token AND the governance token\. Once the spiral begins, it is very expensive and difficult to restore confidence to the market\. And then it’s goblin town\.

The death spiral is no joke\. This is a complete confidence game\. It’s a confidence game akin to the current debt\-based fractional banking system; however, this game does not have governments who can coerce usage of the system with the threat of mortal violence\.

Supposedly profit\-seeking humans should, in theory, be willing to part with good collateral to save the algorithmic protocol for phat profits denominated in the recently\-created\-from\-thin\-air governance token\. That’s the assumption, at least\.


![](assets/712ec5abe199/0*tqqL6Z0eMx_uqRdt)


This is a chart of the percentage deviation of UST vs\. its $1 peg\. As with MakerDAO, 0% means that the peg is rock solid\. As you can see, everything was fine until it wasn’t\. UST continues to trade at a substantial discount to its peg\.

Again, many have tried, but most have failed or are in the process of failing\. That isn’t to say this model cannot work, at least for a period of time\. I happen to own some governance tokens of a particular algorithmic stablecoin project\. They are currently profitable at the protocol level, which makes them attractive\. This protocol has a similar construction to Terra, but accepts other “harder” collateral to back its pegged stable in addition to its governance token\.

Theoretically, this model — akin to fractional banking — can scale to meet the needs of a decentralised Web3 economy, but it will require near\-perfect design and execution\.
### **Bitcoin\-Backed Stablecoins**

The only laudable goal of stablecoins is to allow a fiat\-pegged token to ride on a public blockchain\. This has actual usefulness until such time as true farm\-to\-table Bitcoin economics arrive\. Therefore, let’s attempt to make the best of a fundamentally flawed premise\.

The most pristine crypto collateral is Bitcoin\. How can we transform Bitcoin at a 1:1 USD value ratio into a hard\-to\-break pegged USD stablecoin?

A variety of the top crypto derivatives exchanges offer inverse style perpetual swap and futures contracts\. These derivatives contracts have an underlying of BTC/USD, but are margined in BTC\. That means profit, loss, and margin are denominated in Bitcoin, while the quoted price is in USD\.

I shall hold your hand while we engage in some maths — I know it’s hard for your TikTok\-corrupted noggins\.

Each derivatives contract is worth 1 USD of Bitcoin at any price\.

**_Contract Value Bitcoin Value = \[$1 / BTC Price\] \* \# of Contracts_**

If BTC/USD is $1, then the contract is worth 1 BTC\. If BTC/USD is $10, then the contract is worth 0\.1 BTC\.

Now let’s synthetically create $100 using BTC and short derivatives contracts\.

Assume that BTC/USD = $100\.

What are 100 contracts or $100 worth in BTC at a BTC/USD price of $100?

**_\[$1 / $100\] \* $100 = 1 BTC_**

Intuitively, that should make sense\.

100 synthetic dollars: 1 BTC \+ 100 short derivatives contracts

If the price of Bitcoin goes to infinity, the value of the short derivatives contract in Bitcoin terms approaches a limit of 0\. Let’s show that with a larger but less than infinite BTC/USD price\.

Assume the price of Bitcoin rises to $200\.

What’s the value of our derivatives contracts?

**_\[$1 / $200\] \* $100 = 0\.5 BTC_**

Therefore, our unrealised loss is 0\.5 BTC\. If we subtract our unrealised 0\.5 BTC loss from our 1 BTC of pledged collateral, we now have a net balance of 0\.5 BTC\. But at a new BTC/USD price of $200, 0\.5 BTC still equals $100\. Therefore, we still have 100 synthetic USD, even as the price of Bitcoin rose and caused unrealised losses on our derivatives position\. In fact, it is mathematically impossible for this position to be liquidated on the upside\.

The first fundamental flaw with this system occurs when the price of BTC/USD approaches 0\. As the price approaches zero, the contract value becomes greater than all Bitcoin that will ever be in existence — making it impossible for the short side to ever pay you back in Bitcoin terms\.

Here is the maths\.

Assume the price of Bitcoin falls to $1\.

What’s the value of our derivatives contracts?

**_\[$1 / $1\] \* $100 = 100 BTC_**

Our unrealised gain is 99 BTC\. If we sum that unrealised gain with the initial 1 BTC collateral, we arrive at a total balance of 100 BTC\. At a price of $1,100 BTC equals $100\. Therefore, our 100 synthetic USD peg still holds\. However, notice how a 99% drop in the price of Bitcoin generated a 100x gain in the contract’s Bitcoin value\. This is the definition of negative convexity, and shows how this peg breaks as the Bitcoin price approaches 0\.

The reason I disregard this scenario is because if Bitcoin goes to zero, the whole system ceases to exist\. At that point, there is no more public blockchain in existence capable of transferring value, as miners will not spend pure energy to upkeep a system where the native token is worthless\. If you are concerned this is a real possibility, just continue using the fiat banking rails — there is no need to experiment with something potentially cheaper and faster\.

Now, we must introduce some centralisation, which brings in a whole other set of issues to this design\. The only places where these inverse contracts trade in sufficient size to accommodate a Bitcoin\-backed stablecoin that can service the current ecosystem occur on centralised exchanges \(CEXs\) \.

The first point of centralisation is the creation and redemption process\.

**The Creation Process:**
1. Send BTC to the foundation\.
2. The foundation pledges BTC on one or more CEXs, and sells inverse derivatives contracts in order to create sUSD, which is synthetic USD\.
3. The foundation issues an sUSD token that rides on a public blockchain\. For ease of use, I suggest creating an ERC\-20 asset\.


The foundation must create an account with one or more CEXs in order to trade these derivatives\. The BTC collateral is not kept with the foundation, and instead now resides on the CEX itself\.

**The Redemption Process:**
1. Send sUSD to the foundation\.
2. The foundation buys back short inverse derivative contracts on one or more CEXs, and then burns sUSD\.
3. The foundation withdraws the net BTC collateral and returns it to the redeemer\.


There are two issues with this process\. First, the CEX \(for whatever reason\) might not be able to return all the BTC collateral entrusted to it\. Second, the CEX must collect margin from the losers\. For the purposes of this project, when the BTC price falls, the project’s derivatives are in profit\. If the price falls too far, too fast, the CEX will not have enough margin from the longs to pay out\. That is where various socialised loss mechanisms come into place\. TL;DR, we cannot assume that if the BTC price falls, the project will receive all the BTC profit it is due\.

**Setup**

The foundation needs to raise funds for development of the project\. The biggest need for funds is a general sink fund to cover exchange counterparty risk\. Governance tokens must initially be sold in exchange for Bitcoin\. This Bitcoin is earmarked for situations where the CEX does not pay out as expected\. Obviously, this sink fund is not inexhaustible, but it will create some confidence that the 1 USD peg can be maintained if a CEX pays back less than it should\.

The next step is determining how the protocol earns revenue\. There are two sources of income:
1. The protocol will charge a fee for every creation and redemption\.
2. The protocol will earn the natural positive basis of the derivatives contract vs\. the underlying spot value\. Let me explain\.


The Fed’s \(and most other major central banks’\) stated policy is to inflate their currency by 2% each year\. In fact, since 1913 — the year the Fed was established — the USD has lost over 90% of its purchasing power when indexed against the CPI basket\.

BTC has a fixed supply\. As the denominator \(USD\) grows in value, the numerator \(BTC\) stands still\. That means that we should always ascribe a higher value to the future value of the BTC/USD exchange rate than the spot value\. Therefore, at a fundamental level, the contango \(futures price > spot\) or funding rate \(on perpetual swaps\) should be positive — which means income for those who short these inverse derivatives contracts\.

One might counter that US Treasury bonds pay a positive nominal yield, and there are no risk\-free instruments nominally priced in Bitcoin — making it incorrect to assume that the USD will depreciate vs\. Bitcoin over the long run\. While that is true, as I and many others have written, negative real rates \(i\.e\., when the nominal risk\-free treasury rate is below the GDP growth rate\) are the only way mathematically that America can nominally pay back debt holders\.

One other option is to increase the population growth rate well above 2% a year, which requires couples to eschew contraception and other family planning methods en masse\. According to the US Census Bureau, the population growth rate in 2021 was 0\.1%\. If you exclude immigration, the rate would have been negative\.

The final option is to discover some new amazing energy transformation technology that vastly reduces the cost of energy per dollar of economic activity\. Both of these alternative solutions appear unlikely to materialise any time soon\.

The long Bitcoin vs\. short inverse derivatives contract should earn a positive yield year after year\. Therefore, the larger the float of sUSD, the more Bitcoin held in custody vs\. short derivatives contracts, which results in a large compounded stream of interest income\. This provides a phat pool of moneys that governance token holders have agency over\.
### **Perfection is Impossible**

The act of creating a fiat\-pegged stablecoin that rides on a public blockchain cannot be done without many compromises\. It is up to the users of the relevant solutions to determine whether the compromises are worth the goal of allowing fiat to ride on a public blockchain faster and cheaper than on banker\-controlled centralised payment networks\.

Of the four options presented, I prefer a Bitcoin and derivatives\-backed stablecoin the most, followed by an overcollateralised crypto\-backed one\. However, each of these solutions immobilises crypto into large pools\. The problem, as I mentioned in [The Doom Loop](the-doom-loop-161a42bbcd50) , is that these public networks need assets to move between parties in order to generate transaction fees that pay for the upkeep of the network\. HOLDing is toxic in the long run\. Therefore, let us not become complacent, but continue to strive to create farm\-to\-table Bitcoin economies\.
### **Will Terra / UST Survive?**

Terra is currently in the deepest darkest depths of the death spiral\. Please read this [Tweet thread](https://twitter.com/stablekwon/status/1524331183261163520?t=ekR3J0ZTh_W3zOU2pRERxw&s=19) from the founder Do Kwon and let it sink in that what is currently happening is completely by design\. The protocol is working as it should, the fact that people are surprised at what is happening means they did not properly read the whitepaper\. The Luna\-tics also didn’t question hard enough where that 20% UST yield came from on Anchor\.

The spiral ceases when the UST marketcap equals that of LUNA\. If left to do its thang, the protocol will find that marketcap equilibrium\. The question then becomes what is that final resting marketcap\. And most importantly, when fresh LUNA is created by arbitrageurs buying cheap UST, who will buy that LUNA? Why would you buy LUNA from those selling it when you know there is billions of dollars of LUNA sell pressure created programmatically as long as UST < $1\.

Even if LUNA and UST survive this episode, in the long run there must be some genius protocol changes effected to bolster market confidence that the marketcap of LUNA will always exceed the UST float\. I have no idea how to accomplish this\. That’s why I shall just LARP\. This fundamental issue has been highlighted by many — check out this article by [Dr\. Clements](http://www.wakeforestlawreview.com/2021/10/built-to-fail-the-inherent-fragility-of-algorithmic-stablecoins/) for a more detailed discussion\.


![](assets/712ec5abe199/0*YK-gFnjxaTOo6CAH)


This is a chart of \[UST Marketcap — LUNA Marketcap\] \. The system is healthy when this value is <$0\. The spike upwards means that UST must be burned and LUNA issued to bring the UST back in line with its peg\.

Algorithmic stablecoins are not much different than fiat debt\-backed currencies, save for one crucial factor\. Terra and others like it cannot force anyone to use UST at any price\. They must convince the market with their fancy designs that the governance tokens backing the protocol will have a non\-zero value that rises more quickly over time than the amount of fiat\-pegged tokens issued\. However, a government can always force, ultimately at the point of a gun, its citizens to use its currency\. Therefore, there is always built\-in demand for fiat, even if everyone knows the “assets” backing such a currency are worth less than the currency in circulation\.

The other casualty is a whole class of investors who yelled “Yip, Yip, Hooray\!” for DeFi due to their enthusiasm for Terra\. Now these investors will be busy repairing their balance sheets, and not dip buying Bitcoin and Ether as they resume their downward trajectory\.
### **Recess**

Y’all remember that thing where kids used to play outside with other kids …

_Red Rover, Red Rover_

_This Meltdown Ain’t Over …_

During a proper meltdown, the market seeks out those indiscriminate sellers and forces their hands\. This week’s plunge was accentuated by the forced selling of all Luna Foundation Bitcoin in order to defend the UST:USD peg\. As always, they still failed to defend the peg\. That’s how all pegs fail in the face of the entropy of the universe\.

I dutifully sold my Bitcoin $30,000 and Ether $2,500 June puts\. I mainly trade because I enjoy it\. I made no alterations to my structurally long crypto positions even though in fiat terms they are losing “value”\. If anything, I’m evaluating the various altcoins I own and increasing exposure\.

I did not expect the market to trade through these levels so quickly\. This meltdown happened less than one week after the Fed raised rates to the expected 50bps\. Let me repeat the pertinent fact that the market **EXPECTED** a 50bps hike, and still puked afterwards\. This market cannot handle rising nominal rates\. It astounds me that anyone can believe long duration risk assets at all\-time\-high price multiples will not succumb to rising nominal rates\.

US CPI for April came in at 8\.3% YoY, which is lower than the previous reading of 8\.5% YoY\. 8\.3% is still too hot to handle, and the Fed in firefighter mode can’t abandon their quixotic quest against inflation\. A June 50bps hike is the expectation, and this will continue the destruction of long\-duration risky assets\.

The crypto capital markets now must determine who is overexposed to anything Terra\-related\. Any service offering above average yields that is believed to have any exposure to this melodrama will experience swift outflows\. And given that most people never read how any of these protocols actually work in distress scenarios, it will be a sell first, read later exercise\. This will continue to weigh on all crypto assets as all investors lose confidence and would rather suck their thumb, clutch their safety blanket, and hold fiat cash\.

The crypto capital markets must be allowed time to heal after the blood letting concludes\. Therefore, it is asinine to attempt to fathom legitimate price targets\. But I shall say this– given my macro view about the inevitability of more money being printed, I will close my eyes and trust the Lord\.

Therefore, I am a buyer at Bitcoin $20,000 and Ether $1,300\. These levels roughly correspond to the all\-time highs of each asset during the 2017/18 bull market\.

We know not who amongst us cavorted with the Devil but proclaimed fealty to the Lord\. Therefore steal yourself away from the “Buy” and “Sell” buttons, and let the dust settle\. All will be made clear to the faithful in due course\.



_[Post](https://ehandbook.com/luna-brothers-inc-712ec5abe199) converted from Medium by [ZMediumToMarkdown](https://github.com/ZhgChgLi/ZMediumToMarkdown)._
