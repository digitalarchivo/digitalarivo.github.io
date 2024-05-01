---
title: "Dust on Crust Part Deux"
author: "Arthur Hayes"
date: 2024-03-08T00:10:23.602+0000
last_modified_at: 2024-03-08T05:26:57.126+0000
categories: ""
tags: ["cryptocurrency","ethereum","bitcoin","trading","investing"]
description: "(Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor…"
image:
  path: /assets/85a4670239d6/0*NGcrulY97fR_hZyj
---

### Dust on Crust Part Deux


![](assets/85a4670239d6/0*NGcrulY97fR_hZyj)


_\(Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor be construed as a recommendation or advice to engage in investment transactions\. \)_

Right on schedule, dust on crust returns to Hokkaido, Japan\. It’s sunny and warm by day, but by night, it’s bone\-chillingly cold\. This weather pattern creates the deplorable snow condition called dust on crust\. Below what appears to be a beautiful slab of untouched power lurks ice and crunchy snow\. Yuck\.

As the transition of winter into spring accelerates, I want to revisit my “ [Dust on Crust](dust-on-crust-300d4b5cf3ec) ’’ essay published one year ago\. In this essay, I proposed how to create a synthetically backed fiat stablecoin that does not owe its existence to the TradFi banking system\. My idea combines long crypto hedged with a short perp swap position, creating a synthetic fiat currency unit\. I named this the Nakadollar because I envisioned using Bitcoin and short XBTUSD perp “perp” swaps as a way to create a synthetic USD\. I closed the essay with a pledge to support a credible team attempting to bring this idea to fruition in any way I could\.

What a difference a year makes\. Guy is the founder of Ethena\. Before working on Ethena, Guy worked at a $60 billion hedge fund investing in special situations across credit, private equity, and real estate\. Guy caught the shitcoin bug during the DeFi summer starting in 2020 and never looked back\. He became inspired to launch his own synthetic dollar after reading “ [Dust on Crust](dust-on-crust-300d4b5cf3ec) ”\. But as all great entrepreneurs do, he wanted to improve upon my initial idea\. Instead of using Bitcoin, he would create a synthetic USD stablecoin that used Ether\. At least to start\.

Guy chose Ether because the Ethereum network offered a native yield\. To provide security and process transactions, Ethereum network validators are paid a small amount of ETH for each block directly by the protocol\. This is what I will refer to as the ETH staking yield\. Additionally, because Ether is now a deflationary currency, there is a fundamental reason why ETH/USD forwards, futures, and perp swaps trade at a persistent premium to spot\. Short perp swap holders can capture this premium\. Combining physical staked ETH plus a short ETH/USD perp swap position creates a high\-yielding synthetic USD\. Staked [Ethena USD](https://www.ethena.fi/) \(sUSDe\) currently yields approximately >50% per annum as of this week\.

A great idea is nothing without a team that can execute\. Guy named his synthetic dollar Ethena and assembled a rockstar team to quickly and safely launch the protocol\. Maelstrom became a founding advisor in May of 2023, and in exchange we received governance tokens\. I have worked with a number of high\-quality teams in the past, and the folks at Ethena get shit done without cutting corners\. Fast forward twelve months, and Ethena’s stablecoin USDe is live with a [circulation approaching one billion units](https://defillama.com/stablecoins) after only 3 weeks live on mainnet \(TVL of $1 billion; 1 USDe = 1 USD\) \.

Let me ditch the knee pads so I can honestly discuss the future of Ethena and stablecoins\. I believe that Ethena can eclipse Tether as the largest stablecoin\. It will take many years for this prophecy to manifest itself\. However, I want to explain why Tether is the best and worst business in crypto\. It is the best because it is probably the most profitable financial intermediary per employee across TradFi and crypto\. It is the worst because Tether exists at the pleasure of its poorer TradFi banking partners\. Banks’ jealousy and the problems Tether creates for the guardians of Pax Americana’s financial system could instantly spell the end for Tether\.

_For all those misguided Tether FUDsters, I want to be crystal clear\. Tether is not a financial fraud, nor is Tether lying about its reserves\. Also, I have the utmost respect for those who founded and operate Tether\. But with all due respect, Ethena is going to rock Tether\._

This essay will be divided into two parts\. First, I will explain why the US Federal Reserve \(Fed\), the US Treasury, and large politically connected US banks wish to destroy Tether\. Second, I will go deep into Ethena\. I will give a brief overview of how Ethena is constructed, how it maintains its USD peg and its risk factors\. Finally, I will offer a valuation model for Ethena’s governance token\.

After reading this essay, you will understand why I believe Ethena is the crypto ecosystem’s best shot at providing a synthetic USD that rides on a public blockchain\.

_Note: Physically backed fiat stablecoins are coins where the issuer holds fiat in a bank account i\.e\. Tether, Circle, First Digital \(cough cough … Binance\) etc\. Synthetically backed fiat stablecoins are coins where the issuer holds crypto hedged with a short derivative i\.e\. Ethena\._
### Green with Envy

Tether \(symbol: USDT\) is the largest stablecoin measured by tokens in circulation\. 1 USDT = 1 USD\. USDT is sent between wallets on various public blockchains like Ethereum\. To maintain the peg, Tether holds 1 USD in a bank account for each unit of USDT in circulation\.

Without a USD bank account, Tether cannot perform its functions of creating USDT, custody of USD backing USDT, and redemption of USDT\.

**Creation:** Without a bank account, there is no way to create USDT because there is nowhere a trader can send their USD\.

**Custody of USD:** Without a bank account there is nowhere to hold the USD backing USDT\.

**Redemption of USDT:** Without a bank account, there is no way to redeem USDT because there is no bank account from which to send USD to the redeemer\.

Having a bank account is not enough to ensure success because not all banks are created equal\. There are thousands of banks worldwide that can accept USD deposits, but only certain banks have a master account at the Fed\. Any bank that wishes to clear USD through the Fed to fulfill its obligations as a USD correspondent bank must hold a master account\. The Fed retains complete discretion over which banks are granted master accounts\.

I will quickly explain how correspondent banking works\.

There are three banks: A, B, and C\. Banks A and B are based in two non\-US jurisdictions\. Bank C is a US bank with a master account\. Banks A and B would like the ability to move USD around the fiat financial system\. They each apply to use Bank C as their correspondent bank\. Bank C evaluates the banks’ client bases and approves them\.

Bank A needs to send $1,000 to Bank B\. The flow of funds is $1,000 moves from Bank A’s account at Bank C into Bank B’s account at Bank C\.

Let’s change the example slightly and add Bank D who is also a US bank with a master account\. Bank A uses Bank C as a correspondent bank, but Bank B uses Bank D as a correspondent bank\. Now, what happens when Bank A wants to send $1,000 to Bank B? The flow of funds is Bank C transfers $1,000 from its account at the Fed to Bank D’s account at the Fed\. Bank D finally credits Bank B’s account with $1,000\.

Typically, banks outside of the US use a correspondent bank to wire USD globally\. That is because USD must be cleared directly through the Fed once it moves between jurisdictions\.

I have been in crypto since 2013, and more often than not, the crypto exchange’s bank where you deposit fiat is not a US\-domiciled bank, which means it relies on a US bank with a master account to process fiat deposits and withdrawals\. These smaller non\-US banks are hungry for deposits and bank crypto companies because they can charge high fees and pay nothing for the deposits\. Globally, Banks are usually desperate for cheap USD funding because the USD is the global reserve currency\. However, these smaller foreign banks must interact with their correspondent bank to process deposits and withdrawals of dollars outside of their domicile\. While the correspondent banks tolerate these fiat flows tied to crypto businesses, for whatever reason, sometimes certain crypto clients are offboarded from the smaller banks at the behest of the correspondent bank\. If the smaller bank doesn’t comply, they lose their correspondent banking relationship along with the ability to move dollars internationally\. A bank that loses the ability to move dollars is a dead bank walking\. Therefore, smaller banks will always ditch crypto clients if asked to by their correspondent bank\.

This correspondent banking sojourn is essential when we analyse the strength of Tether’s banking partners\.

_Tether Banking Partners:_

_Britannia Bank & Trust_ 
_Cantor Fitzgerald_

_Capital Union_

_Ansbacher_

_Deltec Bank and Trust_

Of the five banks listed, only one, Cantor Fitzgerald, is a US\-domiciled bank\. However, none of the five banks have a [Fed master account\.](https://www.federalreserve.gov/paymentsystems/master-account-and-services-database-existing-access.htm) Cantor Fitzgerald is a Primary Dealer who helps the Fed implement open market operations like buying and selling bonds\. Tether’s ability to transfer and hold USD is completely at the whim of fickle correspondent banks\. Given the size of Tether’s US Treasury bills portfolio, I assume their partnership with Cantor is critical to continued access to that market\.

If any of these banking CEOs didn’t negotiate an equity stake in Tether in exchange for providing banking services, they are fools\. You will understand why when I present Tether’s revenue per employee metric later\.

That covers why Tether’s banking partners are sub\-optimal\. Next, I want to unpack why the Fed doesn’t like Tether’s business model and why, at a fundamental level, it has nothing to do with crypto and everything to do with how the USD money markets function\.
### Fully Reserved Banking

Tether, when viewed through a TradFi lens, is a fully reserved bank, also called a narrow bank\. A fully reserved bank takes deposits without loaning them out\. The only service it offers is that of wiring money to and fro\. It pays little to no interest on deposits as depositors face no risk\. If all depositors simultaneously requested their money back, the bank could meet this request instantly\. Hence, the name — fully reserved\. Contrast this to a fractionally reserved bank, where the loan book size is larger than the deposit base\. If all depositors simultaneously request their money back from a fractionally reserved bank, the bank goes under\. Fractionally reserved banks pay interest to attract deposits, but depositors face risk\.

Tether is essentially a fully reserved USD bank that provides USD transaction services powered by public blockchains\. That’s it\. No loans, no funny stuff\.

The Fed doesn’t like fully reserved banks not because of who their clients are but rather due to what these banks do with their deposits\. To understand why the Fed detests the fully reserved banking model, I have to discuss the mechanics of quantitative easing \(QE\) and its implications\.

Banks failed during the 2008 Great Financial Crisis because they did not have enough reserves to cover losses on dodgy mortgages\. Reserves are the funds banks place at the Fed\. The Fed monitors the size of banking reserves against the aggregate outstanding loans\. After 2008, the Fed ensured banks would never be short of reserves\. The Fed did this by conducting QE\.

QE is the process by which the Fed buys bonds from banks and credits them with reserves held at the Fed\. The Fed conducted trillions of dollars\-worth of QE bond purchases, swelling banking reserve balances\. Hooray\!

QE wasn’t as insanely inflationary in an obvious way as the COVID stimulus checks were because banking reserves stayed at the Fed\. The COVID stimmies were handed directly to the populace to spend as they pleased\. If the banks had instead lent out these reserves, inflation post\-2008 would have instantly risen because the money would be in the hands of businesses and individuals\.

Fractional banks exist to make loans; if they don’t make loans, they don’t make money\. Therefore, fractional reserve banks, all else being equal, would prefer to lend out their reserves to paying customers rather than leave them at the Fed\. The Fed had a problem\. How do they ensure the banking system has near\-infinite reserves without creating inflation? The Fed chose to pay a “bribe” to the banking industry, not to lend\.

Bribing the banks required the Fed to pay interest on the banking system’s excess reserves\. To calculate the magnitude of the bribe, multiply the total banking reserves held at the Fed by the Interest on Reserve Balances \(IORB\) \. IORB must hover between the lower and upper bound of the Fed Funds rate\. Read my essay “ [Kite or Board](https://cryptohayes.substack.com/p/kite-or-board) ’’ to understand why\.

Lending is risky\. Borrowers default\. Banks would rather earn risk\-free interest income from the Fed than lend to the private sector and suffer possible losses\. Therefore, the banking system’s outstanding loans didn’t grow at the same pace as the Fed’s balance sheet as QE progressed\. Success, however, ain’t cheap\. When Fed Funds was 0% to 0\.25%, the bribe didn’t cost much\. But now, with Fed Funds at 5\.25% to 5\.50%, that IORB bribe costs the Fed of billions of dollars per year\.

The Fed maintains “high” policy rates to slay inflation; however, due to the higher cost of the IORB, the Fed became unprofitable\. The US Treasury and, by extension, the American public are directly funding the Fed’s bribe to banks via the IORB program\. When the Fed makes money, it remits those payments to the US Treasury\. When the Fed loses money, the US Treasury borrows money and funnels it to the Fed to cover its losses\.

QE solved the problem of insufficient banking reserves\. The Fed now wants to reduce the amount of banking reserves to slay inflation\. Enter Quantitative Tightening \(QT\) \.

QT is when the Fed sells bonds to the banking system paid for with reserves held at the Fed\. Where QE increases banking reserves, QT reduces them\. As banking reserves fall, the cost of the IORB bribe does as well\. Obviously, the Fed would not be pleased if banking reserves rose at the same time it is paying high rates due to IORB\.

The fully reserved banking model operates at cross purposes with the Fed’s stated goals\. A fully reserved bank doesn’t make loans, which means 100% of deposits are deposited with the Fed as reserves\. If the Fed started granting fully reserved banking licences to banks doing business similar to Tether, it would exacerbate the central bank’s losses\.

Tether isn’t a US\-licensed bank, so it can’t deposit directly with the Fed and earn IORB\. But Tether can stuff cash in money market funds, which can access the Reverse Repo Program \(RRP\) \. The RRP is similar to the IORB in that the Fed must pay an interest rate between the lower and upper bound of Fed Funds in order to dictate precisely where short\-end rates trade\. Treasury bills \(T\-bills\), which are less than one\-year maturity zero coupon bonds, trade at a yield slightly higher than the RRP’s rate\. Therefore, while Tether is not a bank, its deposits are invested in instruments that require the Fed and US Treasury to pay interest\. Tether has nearly $81 billion invested in money market funds and T\-bills\. Tether is arbing the Fed\. And the Fed no likey\.

Tether arbs the Fed because Tether pays 0% on USDT balances but earns approximately the upper bound of the Fed Funds rate\. This is Tether’s net interest margin \(NIM\) \. As you can imagine, Tether is overjoyed that the Fed is raising rates, as NIM went from basically 0% to close to 6% in under 18 months \(March 2022 to September 2023\) \.

Tether is not the only stablecoin issuer arbing the Fed\. Circle \(symbol: USDC\) and all the other stablecoins that accept USD and issue tokens are doing the same thing\.

If banks drop Tether for some reason, the Fed will do nothing to help\. In fact, Fed governors will cheese bigger than Sam Bankman\-Fried’s chubby during a non\-conjugal visit from Tiffany Fong\.

What about Bad Gurl Yellen? Does her Treasury department have any beef with Tether?
### Tether’s Too Big

US Treasury Secretary Janet Yellen needs a well\-functioning US Treasury bond market\. This allows her to borrow the money necessary to pay for the multi\-trillion\-dollar annual government deficit\. The size of the US Treasury market alongside fiscal deficits ballooned post\-2008\. The larger it grows, the more fragile it becomes\.


![](assets/85a4670239d6/0*Q5pu1MODWHOIzVU-)


This chart from the US Government Securities Liquidity Index clearly shows declining US Treasury market liquidity since COVID \(a higher number means worse liquidity conditions\) \. It takes a smaller amount of selling to upset the market\. By upsetting the market, I mean a quick fall in bond prices or a rise in yields\.

Tether is now one of the [22 largest holders of US Treasury debt](https://cointelegraph.com/news/tether-s-ardoino-says-it-s-now-one-of-top-buyers-of-us-treasury-bills-holds-72-5b) \. If Tether had to quickly sell down its holdings for whatever reason, it could cause chaos for global bond markets\. I say global because all fiat debt instruments in some way, shape, or form are priced off of the US Treasury curve\.

If Tether’s banking partners booted Tether, Yellen might intervene in the following ways:
1. Maybe she would stipulate that Tether be given a reasonable time to remain a client so that it wasn’t forced to sell its assets to meet redemption requests quickly\.
2. Maybe she would freeze Tether’s assets so that it couldn’t sell anything until she felt the market could absorb Tether’s holdings\.


But what Yellen certainly won’t do is help Tether find another long\-term banking partner\. The growth of Tether and similar stablecoins that service the crypto market creates risk for the US Treasury market\.

Maybe if Tether decided to buy the bonds that no one wants, which are long\-dated >10\-year maturity bonds, instead of short\-dated bills, which everyone wants, Yellen might be on their side\. But why would Tether take that sort of duration risk to earn LESS money than is on offer via shorter maturity T\-bills? This is due to the inversion of the yield curve \(long\-end rates lower than short\-end rates\) \.

The most powerful arms of the Pax Americana financial apparatus would rather Tether not exist\. And none of this has anything to do with crypto\.
### Tether’s Too Rich

The talented analysts at Maelstrom created the following speculative balance sheet and income statement for Tether\. They used a combination of Tether’s public disclosures and their judgement to create this\.


![](assets/85a4670239d6/0*kShaJw-EI-HKcw2c)



![](assets/85a4670239d6/0*7exL_g2WqwHcRPdx)



![](assets/85a4670239d6/0*A1DkcsgCn9d0z-0d)


Below is a table of the eight Too Big to Fail \(TBTF\) banks that run the Pax Americana economic and political system and their FY2023 net income\.


![](assets/85a4670239d6/0*eMWLdgPG_Q6DHYZa)


_Cantor Fitzgerald is not a bank but a Primary Dealer and trading house\. There are only [23 Primary Dealer banks](https://www.newyorkfed.org/markets/primarydealers.html) \. Therefore, in the Total Deposits column, that number for Cantor represents the value of its balance sheet’s assets\. I obtained an estimate of Cantor’s Net Income and Total Workforce from [Zippia](https://www.zippia.com/cantor-fitzgerald-careers-17957/revenue/#) \._

Tether made $62 million per employee\. No other bank on the list comes even close\. Tether’s profitability is another example of how crypto will affect the largest transfer of wealth in human civilised history\.

Why don’t any of these TBTF banks offer a competing fiat\-pegged stablecoin? Tether makes more per employee than every one of these banks, but without these banks and others like them, Tether can’t exist\.

Instead of demanding the de\-banking of Tether, maybe one of these banks could purchase Tether\. But why would they do that? It certainly wouldn’t be for the tech\. The code to deploy a smart contract Tether clone is already on the fucking internet due to the transparency of public blockchains\.

If I were the CEO of a US bank enabling Tether’s existence, I would immediately debank them and offer a competing product\. The first US bank to offer a stablecoin would quickly capture the market\. As a user, holding JPMorgan coin is less risky than Tether\. The former is a liability of a Too Big to Fail Bank, which is, in essence, a liability of the empire\. The latter is the liability of a private company despised by the entire US banking system and its regulators\.

I have no reason to believe a US bank is plotting to overthrow Tether\. But it would be trivial to do so\. Why is Tether, owned by crypto muppets hanging out in the Bahamas, whose existence depends 100% on US banking system access, allowed to earn more than Jamie Dimon in a few trading days? Things that make you go, hmm…\. \.

As the crypto bull market advances, stocks with any tangential crypto business lines will pump\. A US bank whose stock is slumping due to the market freaking out about bad Commercial Real Estate loans could get a valuation boost by entering the crypto stablecoin market\. That might be all the incentive needed for a US bank to finally directly compete with Tether, Circle etc\.

If Circle’s IPO goes well, expect a challenge from the banking system\. Stablecoin businesses, like Circle and Tether, should trade at a discount to earnings because they have no competitive moat\. The fact that Circle can entertain an IPO is a comedy in its own right\.
### Ain’t No Mountain Higher…

I just explained why the US banking system destroying Tether would be easier than beating Caroline Ellison in a maths Olympiad\. But why should we, as the crypto ecosystem, create a different type of fiat\-pegged stablecoin?

Thanks to Tether, we know that the crypto capital markets desire a fiat\-pegged stablecoin\. The problem is that banks provide a shitty service because there is no competition for them to be better\. Using Tether, anyone with an internet connection has access to USD payments 24/7\.

There are two main issues with Tether:
1. Users don’t receive any cut of Tether’s NIM\.
2. Tether can be shut down overnight by the US banking system even if it does everything by the book\.


To be fair, users of any currency usually don’t share in the seigniorage revenue\. Holding physical cash dollar bills does not entitle you to the Fed’s profits … but definitely to its losses\. Therefore, holders of USDT shouldn’t expect to receive any of Tether’s NIM\. The one user base that should be compensated, however, is crypto exchanges\.

Tether’s primary use case is a funding currency used for crypto trading\. Tether also offers a near\-instantaneous way to move fiat between trading venues\. Exchanges as venues for crypto trading give Tether utility, and they get nothing in return\. There isn’t a Tether governance token that can be purchased that provides the holder with a claim on the NIM\. Unless an exchange somehow acquired equity in Tether’s early days, there is no way to share in Tether’s success\. This isn’t a sob story on why Tether should hand out money to exchanges\. Instead, this motivates exchanges to support a stablecoin issuer that passes on most of the NIM to the holders and offers exchanges a chance to purchase governance tokens at a cheap valuation early on in the issuer’s development\.

Very simply, if one wanted to have a shot at overtaking Tether, one must pay a majority of the NIM to stablecoin holders and sell cheap governance tokens to exchanges\. This is how you vampire squid attack physical fiat\-backed stablecoins\.

Ethena followed this playbook to the letter\. Holders of USDe can stake it directly with Ethena and earn a majority of the NIM\. The major exchanges all invested into Ethena in early fundraising rounds\. Ethena has Binance Labs, Bybit via Mirana, OKX Ventures, Deribit, Gemini, and Kraken as exchange partner investors on the cap table\.

In terms of the market share those exchanges represent, they cover roughly 90% of ETH’s open interest on major exchanges\.
### How Does it Work?

Ethena is a synthetically backed fiat crypto dollar\.

ETH = Ether

stETH = Lido Staked ETH derivative

ETH = stETH

ETH = stETH = $10,000

ETH/USD perp swap Contract Value = $1 worth of ETH or stETH = 1 / ETH or stETH USD value
#### The Peg

USDe is the stablecoin issued by Ethena that aims to be pegged to 1:1 with the USD\.

Ethena onboards various authorised participants \(AP\) \. APs are allowed to mint and burn USDe at the 1:1 USD ratio\.
#### Minting:

Currently, stETH Lido, Mantle mETH, Binance WBETH, and ETH are accepted\. Ethena then automatically sells an ETH/USD perp swap to lock the USD value of that ETH or ETH LSD\. The protocol then mints an equivalent amount of USDe that matches the USD value of the short perp hedge\.

Example:
1. AP deposits 1 stETH, which is worth $10,000\.
2. Ethena sells 10,000 ETH/USD perp swap contracts = $10,000 / $1 Contract Value\.
3. AP receives 10,000 USDe because Ethena sold 10,000 ETH/USD perp swap contracts\.

#### Burning:

To burn USDe, an AP deposits USDe with Ethena\. Ethena then automatically covers a portion of its short ETH/USD perp swap position which unlocks a certain amount of USD value\. The protocol will then burn the USDe, and return a certain amount of ETH or ETH LSD based on the total amount of unlocked USD\-value less execution fees\.

Example:
1. AP deposits 10,000 USDe\.
2. Ethena buys back 10,000 ETH/USD perp swap contracts = $10,000 / $1 Contract Value
3. AP receives 1 stETH = 10,000 \* $1 / $10,000 stETH/USD less execution fees


To understand why, initially USDe should trade at a slight premium to USD on stablecoin trading platforms such as Curve, I will explain why users want to hold USDe\.
#### USDe Yield

The combination of the ETH staking yield and the ETH/USD perp swap funding equates to a high synthetic USD yield\. To earn this yield, USDe holders stake it directly on the Ethena app\. It takes less than a minute to start earning yield\.

Because sUSDe’s yield of approximately 30% at the time of publishing is very high; users who are already holding USD stablecoins that yield much less will switch into sUSDe\. This provides buy\-side pressure and will push up USDe’s price in Curve pools\. When USDe trades at a large enough premium, APs will step in and arbitrage the difference\.


![](assets/85a4670239d6/0*c97ZSgG5tAqahEpN)


_As you can see sUSDe \(staked USDe\) yields considerably more than sDAI \(staked DAI\) and \-month US Treasury bills\. [Source: Ethena](https://app.ethena.fi/dashboards/yields)_

Imagine: 1 USDe = 2 USDT\. If the AP can create 1 USDe with 1 USDT worth of ETH or stETH, they can earn a riskless 1 USD profit\. Here is the process:
1. Wire USD to an exchange\.
2. Sell 1 USD for ETH or stETH\.
3. Deposit ETH or stETH on the Ethena app and receive 1 USDe\.
4. Deposit USDe on Curve and sell it for 2 USDT\.
5. Sell 2 USDT for 2 USD on the exchange and withdraw the USD to a bank account\.


If users believe Ethena is safe and the yield is real, USDT in circulation will fall, and USDe in circulation will rise in this hypothetical example\.
#### Terra USD \(UST\) Yield

Too many folks in crypto believe Ethena will fail in the same way UST did\. UST was the stablecoin attached to the Terra/Luna ecosystem\. Anchor, a decentralised money market protocol in the Terra ecosystem, offered those staking UST a 20% annual yield\. People can deposit UST and then Anchor would loan that deposit to a borrower\.

Any stablecoin issuer must convince users why they should switch from, usually Tether, into a new product\. A high yield is what prompts the switch\.

UST was backed by Luna, and Bitcoin which was purchased by selling Luna\. Luna was the ecosystem’s governance token\. The foundation owned a large chunk of Luna\. Due to the high price of Luna, the foundation sold Luna for UST to pay high UST interest rates\. The interest rate wasn’t paid in physical USD, but rather you earned more UST tokens\. While UST maintained its 1:1 peg with the USD, the market believed if it held more UST it held more USD as well\.

As the UST total value locked of Anchor grew, its UST interest expense grew as well\. It became unsustainable for the foundation to continue selling Luna to subsidise Anchor’s UST rewards\. The yield came only from the market’s belief that Luna should be worth billions of dollars\.

When Luna started to fall in price, the algorithmic stablecoin death spiral began\. Due to how Luna was minted and burned to keep the UST peg 1:1 with the USD, it became harder to maintain UST’s dollar peg as Luna fell in value\. Once the peg broke violently, all that UST interest accumulated on Anchor became worthless\.
#### Ethena Yield

USDe generates yield in a completely different fashion than UST\. Ethena holds two assets that generate yield\.

_Staked ETH:_

ETH is staked using liquid staking derivatives such as Lido \(stETH\) \. stETH earns the ETH staking yield\. ETH is deposited on Lido\. Lido runs validation nodes capitalised with ETH deposits, and remits the ETH paid by the Ethereum network to stETH holders\.

_Perp Swaps:_

A perp swap is a continuous strip of short\-dated futures contracts\. Most perp swaps’ funding rates reset every 8 hours\. The funding rate is based on the premium or discount of the perp vs\. spot\. If during the previous 8 hours, the perp traded at a 1% premium vs\. spot, the funding rate will be \+1% for the next period\. If the funding rate is positive, longs pay shorts; and the reverse is true if the rate is negative\.

Ethena holds short perp swap positions to lock in the USD value of the staked ETH it holds\. Therefore, if funding is positive Ethena earns interest income\. If it is negative, it pays interest\. Obviously as an USDe holder, we want to be confident that Ethena will receive interest rather than pay it\. The question is why should ETH/USD trade at a premium on a forward basis?

Ether is now a deflationary currency\. The USD is an inflationary currency\. If in the future there is less ETH but more USD, then ETH/USD should trade at a higher exchange on a forward basis\. That means any leveraged forward derivative such as a perp swap should trade at a premium to the spot\. Funding should for the most part be positive, which means Ethena receives interest\. The data backs this up\.


![](assets/85a4670239d6/1*PnHpRXVQdx2TVf5DSqIQIA.png)


What would cause Ether to flip from a deflationary to an inflationary currency? If Ethereum’s network usage plummeted, much less ETH gas would be burned each block\. In that case, the Ether block rewards would be greater than Ether gas burned\.

What would cause the USD to flip from an inflationary to a deflationary currency? US Politicians need to stop spending a fuck ton of money to get re\-elected\. The Fed must reduce its balance sheet to zero\. This would cause a severe contraction in the circulation of USD credit money\.

I don’t believe either flippening is likely to occur; therefore, it is reasonable to expect a positive funding rate over most periods for the foreseeable future\.

_USDe is not UST\._

The combination of ETH staking yield and the positive perp swap funding is what generates USDe’s yield\. The yield is not based on the value of Ethena’s governance token\. USDe and UST generate yield in entirely different ways\.
### Ethena Risks
#### Wrap it Up\!

Ethena has exchange counterparty risk\. Ethena is not decentralised, nor is it trying to be\. Ethena holds short perp swap positions on derivative centralised exchanges \(CEX\) \. If these CEXs for any number of reasons are unable to pay out profits on swap positions or are not able to return deposited collateral, Ethena will suffer a loss of capital\. Ethena attempts to mitigate direct exchange counterparty risk by placing funds on third\-party custodians such as:


![](assets/85a4670239d6/0*JV9VJlCYhpIwgKXm)


Tether’s counterparty risk is with TradFi banks\. Ethena’s counterparty risk is with derivative CEXs and crypto custodians\.

The CEXs are investors in Ethena and have a vested interest in not getting hacked and ensuring proper payouts on their derivatives\. Derivative CEXs are the most profitable crypto companies, and they want to stay that way\. Fucking your customers isn’t good business\. As Ethena grows, derivative open interest grows which increases fee income for CEXs\. All incentives are aligned\. CEXs want Ethena to do well\.

Tether’s product helps the crypto capital markets function\. Crypto exists party to disintermediate TradFi banks\. TradFi banks want crypto to fail\. Banking Tether from a fundamental perspective hastens the demise of TradFi\. Incentives are not aligned\. TradFi banks don’t want Tether to do well and neither do their regulators\.

Ethena is For Us, By Us, aka FUBU\.

Tether is For Us, By Them, aka FUBAR\.
#### LSD Smart Contract and Slashing Risk

Ethena holds ETH LSDs\. It is exposed to smart contract risk\. For example, something could go wrong with Lido that renders the stETH worthless\. Also, there is the risk of slashing\. Slashing occurs when an Ethereum node network validator violates certain rules\. As a penalty, the ETH capital held by a validator is reduced, aka slashed\.
#### Negative Funding

As I mentioned earlier, the perp swap funding rate could go negative for a prolonged period of time\. The funding rate could go so negative that the net asset value of Ethena’s assets is below the amount of issued USDe\. Then USDe would break the peg on the downside\.
#### Ethena Smart Contract Risk

Just like Tether, Ethena runs smart contracts on public blockchains\. There could be a bug in the code that causes unexpected behaviour that ultimately results in losses for USDe holders\. Usually, hackers attempt to mint a fuck ton of a stablecoin for free, then trade it for another crypto on platforms such as Uniswap or Curve\. That causes the peg to break as the stablecoin’s supply increases without an equal increase in assets backing the stablecoin\.

However, Ethena smart contracts are relatively simple, with most of their complexity sitting in the offchain engineering\. The onchain mint/redeem contract only has approximately 600 lines of code and only approved participants can interact with the most sensitive contract onchain, which helps reduce this risk blocking malicious unknown counterparties interacting with it\.
#### Growth Limits

The circulating supply of USDe can only grow as large as the total open interest of ETH futures and perp swap contracts on exchanges\. The circulating supply of physically backed fiat stablecoins is approx\. $130 billion\. The total open interest for ETH on all exchanges on which Ethena trades is approx\. $8\.5 billion and approx\. $12bn on all exchanges, as well as a further $31bn of open interest on BTC contracts that Ethena can utlilize once they decide to onboard BTC as collateral\. With about $43bn of combined BTC & ETH open interest it is impossible for Ethena, given current market conditions, to take the number one spot\. Whilst Ethena is starting with ETH, BTC and SOL are trivially easy to add to their system, it is simply a matter of sequencing\.

While the above is true, remember I said Ethena will be crowned King in many years’ time\. As crypto grows as an asset class, the total open interest will grow exponentially\. Some believe crypto as an asset class will reach $10 trillion this cycle\. At that level, it is not absurd that open interest on ETH perps could top $1 trillion, given that Ether is the second largest crypto by fiat market cap\.

Ethena will grow as crypto grows\.
#### Insurance Fund

The insurance fund is there to mitigate the financial losses due to some of the risks outlined above\. If the funding rate turns negative or the synthetic dollar depegs, the funds will act as a bidder in the open market for USDe\. The fund is composed of stablecoins \(USDT and USDC\), stETH, and USDe/USD LP positions\. Currently, the insurance fund is capitalised by funds from the Ethena Labs fundraising rounds, and a portion of yield generated by USDe that is not staked\. In the future, the funds will be capitalised by a long\-term take rate on yield as circulating supply of USDe grows\. The insurance fund is at $16M at the time of writing\.

Neither USDT nor USDe is without risk\. The risks however are different\. Tether and Ethena could ultimately fail, but for different reasons\.
#### Tokens Bitch\!

As people come to believe that the USDe yield isn’t fugazi, USDe in circulation will grow\.

The next step is owning a piece of the kingdom\. That is where the forthcoming Ethena governance token comes into play\.
### Valuing Ethena

Ethena, like any issuer of a currency, lives and dies on seigniorage\. That is the difference between what it costs to create money vs\. what real goods money can buy\. I want to present a simple model to value Ethena based on these seigniorage revenues\. For those who might purchase Ethena governance tokens in the coming months, it behoves you to at least attempt to construct a model to value the protocol\.

Any USDe issued can be staked and earn the ETH staking plus perp funding yield\. As of right now, Ethena distributes the yield generated by assets backing sUSDe, while the yield generated by assets backing unstaked USDe are sent to the insurance fund after this shard campaign this income will go to the protocol\. I estimated that the long\-term split will be 80% of protocol generated yield accrues to staked USDe \(sUSDe\), while 20% of generated yield accrues to the Ethena protocol\.

_Ethena Protocol Annual Revenue = Total Yield \* \(1–80% \* \(1 — sUSDe Supply / USDe Supply\) \)_

If 100% of USDe is staked, i\.e\. sUSDe Supply = USDe Supply:

_Ethena Protocol Annual Revenue = Total Yield \* 20%_

_Total Yield = USDe Supply \* \(ETH Staking Yield \+ ETH Perp Swap Funding\)_

The ETH Staking Yield and ETH Perp Swap Funding are variable interest rates\. Recent history can guide us to what’s possible in the future\.

ETH Staking Yield — I assume a 4% PA yield\.


![](assets/85a4670239d6/0*HUvg8ndV9u51Sk6x)


ETH Perp Swap Funding — I assume 20% PA\.


![](assets/85a4670239d6/0*U4v92aPANf3yC5fy)


% Staked — [Currently, only 28% of USDe is staked](https://dune.com/noxiousq/ethena-usde) \. I expect that to rise over time\. I will assume 50% will be staked in the future\.

The key part of this model is what Fully Diluted Valuation \(FDV\) to revenue multiple should be used\. This is always a guessing game, but I will present some future paths based on comparable DeFi stablecoin projects\.


![](assets/85a4670239d6/1*JpWqstLrKCB7b2vo_JdVCw.png)


Using these multiples as a guide\-post, I created the following potential Ethena FDV\.


![](assets/85a4670239d6/1*aG3y7zCqbYVvCPx6gZeeFw.png)


_The horizontal axis is the USDe supply in billions\. The vertical axis is the FDV/Rev multiple\._

Ondo is the newest and hottest kid on the stablecoin block\. At a roughly $6 billion FDV on only $9 million of revenue, it trades at a 630x multiple\. Woowzers\! Can Ethena be valued at similar heights?

Ethena’s $820 million of assets generated a 67% yield this week\. Extrapolating that out for a year given a 50% sUSDe to USDe supply ratio, Ethena’s annualised revenue is ~$300 million\. Using an Ondo like valuation leads to an FDV of $189 billion\. Does this mean Ethena’s FDV will approach $200 billion at launch? No\. But it does mean that the market will pay up big for future Ethena revenues\.

Yachtzee\! \!
### The Story

If you remember nothing else from this essay, remember this:

Ethena is For Us, By Us, aka FUBU\.

Tether is For Us, By Them, aka FUBAR\.

It is your decision whether to long or short USDe or the eventual Ethena governance token\. I hope that this essay contextualises Ethena’s mission and why it is important to crypto’s success\.

With that I bid you adieu as I must focus on not destroying my thighs while shredding this crusty snow\.



_[Post](https://cryptohayes.medium.com/dust-on-crust-part-deux-85a4670239d6) converted from Medium by [ZMediumToMarkdown](https://github.com/ZhgChgLi/ZMediumToMarkdown)._
