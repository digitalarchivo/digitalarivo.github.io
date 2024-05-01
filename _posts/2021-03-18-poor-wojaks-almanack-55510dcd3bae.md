<<<<<<< HEAD
---
title: "Poor Wojak’s Almanack"
author: "Arthur Hayes"
date: 2021-03-18T22:01:15.200+0000
last_modified_at: 2021-03-18
categories: "Hayes"
tags: ["hayes,"blog"]
description: "(Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor…"
---

### Poor Wojak’s Almanack

_\(Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor be construed as a recommendation or advice to engage in investment transactions\. \)_


![](assets/55510dcd3bae/0*XTXnFAsICvQchcFS)


I became an avid cyclist after the onset of COVID\. I try to ride twice a week for 40–60km\. Given the popularity of cycling with Boomers, you might think it’s a nightclub for uncles on the public bike paths circa 5am — but it’s a high stakes affair\. My top speed hit on a sprint so far is 52 km/h; one wrong move and it’s game over\.

But aside from exercise, my cycling also gives me some much\-needed fresh air to do some of my best thinking\. My cycling buddy happens to be a crypto agrarian as well\. On a recent ride, we got into a risk management discussion about the types of risk Decentralised Finance \(“DeFi”\) “farmers” \(aka liquidity miners\) undertake when putting up their capital\. Based on our conversations, I’ve outlined below a quick history on why farming is popular, and a conceptual framework that evaluates the risk undertaken by crypto peasants\.

**Farmville**

DeFi is an ecosystem of projects that aim to provide financial services to the digital world without the need for centralised financial services providers, such as banks\. For example, many DeFi projects allow people to easily borrow directly from other individuals, who lend out their money in exchange for rewards that are built into the network\. This has massive implications for the future of lending: no credit check, personal data, or bank account is required\. Everyone can participate, and the lending terms are enforced by smart contracts that cannot be tampered with– removing the need for a trustworthy middleman\.

An example of a centralized intermediary is a bank\. In my August 2020 piece [Dreams of a Peasant](https://blog.bitmex.com/dreams-of-a-peasant/) , I spoke about how the DeFi ecosystem is building proto\-banks for humanity’s digital existence\. As a concept, I am fully on board with eventually replacing all banking and financial services with open\-source code\. The ecosystem is nowhere close to fully living up to those ideals, but I am betting that this future will eventually come to fruition\.

Ownership of the projects is open to all, and is based on providing a useful service to the network\. Given many DeFi projects focus on some sort of borrowing, lending, or asset swapping, these projects need lenders and market makers that provide liquidity\. In order to reward people for lending out their assets the projects mint, per a published schedule, a native token and distribute those tokens to all lenders, typically proportionate to the percent of the total lending pool their funds represent\. These tokens each represent a percentage of ownership of the project\. If the project is useful, these native tokens or governance tokens will have a non\-zero value\. In some cases, the tokens may even represent the right to receive a proportional percentage of fees enacted by the platform — e\.g\., receiving a portion of the trading fees charged by a decentralised exchange whose tokens you hold\.

Eventually, these tokens will also give tokenholders the ability to vote on how the protocol operates and is governed\. Imagine a DeFi bank where the tokenholders get to vote on interest rate loan spreads, and the types of collateral that can be lent against\. Or imagine a decentralised asset exchange \(e\.g\., Uniswap, Sushiswap, 1inch, etc\. \) whose tokenholders vote on trading fee rates\.

Below is a hypothetical example of a truncated lifecycle of farming a DeFi protocol’s native token\. Let’s assume this is a simple protocol that allows borrowers to deposit Ether \(ETH\) and borrow a fiat stablecoin Tether \(USDT\) \.
1. The protocol launches, and would like to offer USDT loans collateralised by ETH\.
2. The protocol’s governance token is called CORN\. 1,000 CORN will be distributed every day for the next 1,000 days\. 75% of the daily CORN tokens will be distributed to lenders proportional to the percentage of the USDT lending pool they represent\. 25% of the daily CORN tokens will be distributed to borrowers based on their percentage of daily ETH borrowed\. Something very important to know: you cannot buy CORN directly from the protocol\. You must participate to earn CORN\. Once there are CORN in circulation, you may purchase CORN in the secondary market from willing sellers\.
3. Therefore, even when you borrow or lend on the CORN farm, you are rewarded with ownership in the protocol\. Imagine if you received shares in your Too Big To Fail bank whenever you paid your overdraft fees, or when you paid 20% in fees to cash your government stimmie check because you are too poor to be a profitable client with a real bank account\. My mother recounted that this stimmie cashing situation played out in a blighted section of the inner city\. A line formed down the block, during the previous height of COVID, consisting of poor citizens who had no bank account, weren’t wearing masks, and paid $200 of fees to cash a $1,200 government check\. Disgraceful\.
4. As a lender of USDT, you connect your browser’s Ethereum network wallet to the CORN web3 site \(a popular wallet is Metamask\) \. You approve the connection, and then elect to stake — i\.e\., allow CORN to lend out your USDT\. CORN will pay you an interest rate in USDT by collecting ETH interest from the borrower, and converting it using a Decentralised Exchange \(DEX\), such as Uniswap, to convert ETH into USDT at the prevailing exchange rate\. All this is done programmatically\.
5. If you are a borrower, you again connect your wallet to the CORN platform in the browser\. Instead of staking USDT, you stake ETH as collateral and then borrow USDT and pay a continuous rate of interest in ETH terms\. To repay the loan and receive your ETH collateral back, you send the USDT you owe to the CORN protocol\. The CORN protocol will enforce a minimum leverage ratio based on the external price of ETH/USDT\. If, as a borrower, you breach the minimum level, the ETH you put up as collateral is programmatically sold on a DEX\.
6. As long as you are lending or borrowing, meaning you have USDT and/or ETH staked on CORN, you are continuously being credited with CORN tokens\. The CORN token represents a fraction of ownership of the CORN network, giving its holders voting power to change the CORN protocol and terms of operation, as well as a percentage of interest fees charged to borrowers\. The CORN token has a value determined by the marketplace based on the above traits and can be sold on the secondary market for that price\. To find the appropriate price you could construct a discounted cash flow \(DCF\) model that forecasts total value locked\-up \(TVL\) and uses an assumption on the type of fee income for CORN that will generate\. Plug in a discount factor, and boom — you have a “fair value” for the CORN token\. This is why TVL is the most important statistic for any DeFi project\. The more TVL, the larger the assumed future fee pool, the higher the token price trades\.


Because the market is currently so bullish on the future disruption DeFi projects will cause, their tokens are trading at very high non\-zero nominal values\. Therefore, even if the interest rates are not attractive to potential lenders in and of themselves, the opportunity to generate a token that rises exponentially in price still entices users to stake\.

The act of staking in order to accumulate platform governance tokens that hopefully appreciate in value is the essence of farming\. When you compute the all\-in annual percentage yield \(APY\), the return on your crypto capital dwarfs what you can earn in the centralized “free\-market” interest rate markets of traditional finance\. That sounds amazing, but there are significant risks undertaken by staking on DeFi protocols\.

**Skin in the Game**

Understanding these risks — which are largely tied to how secure the code of these DeFi platforms is — is critically important, as there are a few ways in which you could be at risk of losing some or all of your staked capital\.

While the code for all DeFi protocols is open sourced, most users do not read it\. And many \(like myself\) do not possess the requisite knowledge to discover malicious or poorly\-written code because we don’t understand it\. Even if you wanted to do extensive code review, the speed at which projects accumulate TVL and appreciate in price punishes those slow to the draw\. While you are stumbling through the github, the returns are diminishing\. That is chiefly because the number of tokens distributed remains static, so each lender receives fewer tokens as the number of lenders and TVL increases — diminishing the APY\. Therefore, ape\-ing into contracts without doing any technical due diligence is common and extremely profitable if you are an early mover\.

The more reputable projects will commission a smart\-contract security review by an audit firm\. Quantstamp, Hacken and Trail of Bits are a few of the industry leaders\. However, there is so much interest in this space and so few qualified auditors that obtaining an audit from a reputable firm is almost impossible without a connection to the heads of those firms\.

Here are a few of the common ways to suffer principal loss\.

**Backdoor Hack**

The protocol developers code a backdoor that allows them to drain the contract\(s\) of any staked assets\. This is usually referred to as an exit scam, and the assets are irretrievable\.

**Locked Contract**

The protocol developers coded the contract in such a way that a certain series of actions lock the contract and render all assets inside inaccessible\. A number of high\-profile projects have succumbed to this deficiency\.

**Economic Exploit**

The code as written \(either intentionally or unintentionally\) can be manipulated such that an uneconomic activity is undertaken by the protocol which drains assets from the contract\(s\) \. A common exploit for collateralised lending platforms is a flash loan attack\. [Hacking Distributed](https://hackingdistributed.com/2020/03/11/flash-loans/) wrote an excellent post detailing the many ways flash loans can be used to conduct arbitrage and economically exploit DeFi protocols\.

Backdoor hacks and locked contracts usually result in a 100% loss of staked capital\. Economic exploits usually result in a partial but substantial loss of staked capital\.

As a farmer, you must model the probability that a particular protocol may be hacked and you could lose some or all of your capital\. Given you cannot purchase the token at inception either in the primary or secondary market, the only way to obtain the asset is to stake and place capital at risk\. For the duration that you farm, you are subject to hacking risk\.

The second risk is that because your income is in governance token, the price at which you finally decide to sell it determines your return on capital\. If the platform experiences an unexpected negative event, the token price will decline sharply — thus eviscerating your return\.

However, there are two sound strategies to risk manage your farm and protect your returns\.

**Multiple Crops**

Like any good farmer, you should have multiple crops\. Spreading your capital amongst many different projects reduces your per\-project risk\. This strategy assumes that you have no ability to discern which projects are more or less likely to experience a negative event\. You go fast and hard and jump on any new hot project\. Ape in, collect tokens, and liquidate the tokens continuously to crystallise your profits\. Speed, breadth of tokens, and a high\-risk tolerance are your differentiators\.

Assume you believe that the probability that an event occurs with a 100% loss severity within one month is 30% for any given project\. If you invest in ten projects equally, in one month, 30% of your capital will be lost\. Therefore, your blended APY across the ten projects should be 30% per month just to break even on an expected value basis\. This is just a hypothetical example; I don’t have any empirical evidence that shows the actual statistics\. I’m sure someone reading this might have that data and be willing to share it with you for a nominal fee\.

If the internet veggie you farm has a pumping token price but does not attract TVL quickly you probably should find greener pastures\. You can make a survivorship bias assumption\. That is, the longer the project has been in existence with a large and increasing TVL, the less likely it is to experience a loss event\. Or if there is an event, the percentage severity will be lower\. This is a useful heuristic, but a past devoid of volatility does not necessarily imply a similarly tepid future\.

**Tech Due Diligence**

If you have the rare ability to quickly read and analyse DeFi code, then you have a distinct advantage\. The ability to concentrate capital into ideas with conviction is how you generate outsized returns\. Technical competence allows you to be extremely selective on which projects to farm\. In return, you cannot only farm, but also buy the token itself in the secondary market to double up\.

This is hard to do well\. There are simply too many projects for the limited number of competent security auditors to provide deep and thorough analysis on all of them\. Assessing the vulnerability of projects to the three major risk buckets described above is also difficult to do well\. The biggest issue is that with hundreds to billions of USD worth of TVL on the line, the incentive for malicious actors is significant relative to the amount of effort, time, and expense investors are willing to expend before aping into a project\.

In the Default world, farmers who have the best technology have the best yields\. Internet veggie farming is similar — however, on the electron enabled farm, technology comes in the guise of the ability to lean on competent technical talent to assess the risk of capital loss\.

**Farm or Buy**

This is a crucial decision and depends on multiple factors\. In order to procure the governance token in question, you can either participate by risking your principal and staking, or by purchasing the token in the secondary market\.

The best projects endeavor to distribute as few tokens as possible onto the secondary markets\. That assures significant participation in the form of farming or placing capital at risk for punters to accumulate tokens\. This also results in the recycling of the little supply that is available on the secondary market many times between a few hands and the creation of a positive reflexive feedback loop that results in … MOON\.

If you want to get in early, it is almost essential that you farm\. Farming risks include:
1. Your principal staked is 100% at risk\. A loss event could mean a complete loss of capital\.
2. The tokens distributed have delta price risk which includes an element of platform credit event risk\. If the project is hacked, the token price will fall along with the TVL\. If you do not sell your tokens as you receive them, then your achieved APY will also decline on any loss event\.


Assume you have 100,000 DAI that you stake on a farm — let’s call it Lilipad — which produces LILI tokens\.

You get in as soon as the contract is deployed\. Note: for best results you probably need a bot scanning the Ethereum blockchain monitoring when new contracts get deployed and if they have immediate TVL — especially given rewards are usually proportional to your % of the TVL\. If you are a large % of a small TVL you receive more tokens than if you are a small % of a large TVL\.

The TVL goes from 1 million DAI to 100 million DAI in a week\. Therefore your % of the TVL goes from 10% to 0\.10%; however, the project still only emits 10,000 LILI per day\.

If the price of LILI/DAI goes up 100x in line with the TVL, that is ideal\. Your risk profile and APY have not changed as the project becomes more outwardly successful\.

If the price of LILI goes up less than 100x, then you are taking more risk for less return\. To a nefarious locust, the larger the farm :: TVL, the more edible food\. Therefore your risk of principal losses increases alongside the TVL\. Is your risk 100x greater in line with the TVL? Probably not\. But it is definitely increasing in a non\-linear fashion\.

When you farm, your capital does not increase in value\. Only the token’s value viewed in the currency terms of your capital changes\. Therefore, it is suboptimal to farm just to receive tokens if you can simply purchase the tokens outright\. If your risk tolerance is 100,000 DAI, it would be far better to just purchase 100,000 DAI worth of LILI tokens\.

As you can see, it is not in the interest of the farmer to constantly liquidate their LILI tokens\. Their risk of loss goes up with the TVL, their capital at risk stays constant, and they need their LILI token exposure to increase as well to compensate for the increased risk\. That means they would rather do their part to restrict supply of LILI in the secondary market to encourage an upwardly sloping price trajectory\. This is what I mean by a positive reflexive loop\. As the TVL increases, the price increases, and the risk of loss increases; therefore, if you hold the token and farm, you do not sell\.

Having zero secondary market liquidity is not entirely helpful for the project\. A rapidly appreciating token price brings attention to the project, which results in more TVL\. To encourage some liquidity in the token, many projects will distribute tokens to those who stake in DEX liquidity pools\.

A liquidity pool consists of two assets\. In this example, Lilipad will give LILI tokens to farmers who place equal parts DAI and LILI into either Uniswap, Sushiswap, and 1inch\.There are LILI tokens available for sale, and those who just wish to take delta price risk can purchase LILI\. This also provides farmers who wish to liquidate their LILI crop a market bid\.

The calculus for any farmer participating in the liquidity pool is impermanent loss\. I won’t go into too much detail about this risk, but here is a very good [blog post](https://pintail.medium.com/uniswap-a-good-deal-for-liquidity-providers-104c0b6816f2) describing it\. Impermanent loss is the covariance between the two assets\. As the price of LILI rises, liquidity pool stakers will have less LILI and more DAI\. As the price of LILI falls, liquidity pool stakers will have more LILI and less DAI\. If the LILI sale price is sufficient to cover the impermanent loss, then it is a good deal for the liquidity pool staker\. Because this is a well understood risk, projects will usually provide very high token rewards for liquidity providers enticing them to participate in this scheme\.

If you are able to purchase 100,000 DAI of LILI, then that is most optimal\. However, because the beginning secondary market supply is zero at T0, the incremental supply will carry a high price, and the price will skyrocket in the face of even a small amount of demand\. 100,000 DAI of exposure might pamp the price 100% or more\. That’s fine if you believe TVL will increase quickly but can be fatal if the project is stillborn\.

A simple example illustrates the advantageous position of a trader vs\. a farmer:

Capital = 100,000 DAI

Time = 0

LILI/DAI PRICE = N/A

Time = 1

Capital = 100,000 DAI

Farmed Tokens = 1,000 LILI

LILI/DAI PRICE = 1 DAI

**Downside**

There is a loss event and all of the TVL is wiped out\. The price of LILI/DAI declines to 0\.01 DAI\.

_For the farmer_

Capital Losses = 100,000 DAI

LILI/DAI Losses = 990 DAI

Total Losses = 100,990 DAI

_For the trader_

The trader purchased 100,000 LILI tokens for 100,000 DAI

Capital Losses = 0 DAI \[no capital was staked\]

LILI/DAI Losses = 99,000 DAI

In the downside scenario, the trader outperforms the farmer by 1,900 DAI\.

**Upside**

The TVL increases to 100 million DAI, the LILI/DAI token price also goes up 100x to 100 DAI\.

_For the farmer_

Capital Gain = 0 DAI \[the capital does not appreciate\]

LILI/DAI Gain = \(100 DAI — 1 DAI\) \* 1,000 Tokens = 99,000 DAI

Total Gain = 99,000 DAI

_For the trader_

Capital Gain = 0 DAI \[they did not stake anything\]

LILI/DAI Gain = \(100 DAI — 1 DAI\) \* 100,000 Tokens = 99,000,000 DAI

Total Gain = 9,900,000 DAI

In this extreme upside scenario the trader far and away outperformed the farmer even though they had the same initial capital of 100,000 DAI at risk\. The big assumption in this example is that you can accumulate 100,000 LILI tokens at a reasonable price\.

**A Hard Day’s Work**

Farming internet veggies and other meme tokens appears banal at first, but there are some complicated risks that must be weighed and managed by a burgeoning class of internet peasants\. My views since my prior post [Dreams of a Peasant](https://blog.bitmex.com/dreams-of-a-peasant/) have not changed\. Most of the DeFi projects are of dubious quality and can destroy your capital, but the borrow, lend, asset swap, insurance etc\. web3 powered infrastructure buildout is the bedrock for a more inclusive and equitable financial system\. Financial services for the digital age owned by those who participate the most\.

There will still be ownership concentration issues in this new ecosystem; however, those who take the most risk will garner the largest reward, regardless of their personal affiliations or connections\. This is in stark contrast to how things typically work where your proximity to a centralised power structure determines your ability to share in the spoils of the financial system\. Risk of failure is socialised, and outsized rent\-seeking profits are privatised\. A great game if you are on the inside, and insidiously evil if you are the tax donkey footing the bill\.



_[Post](https://cryptohayes.medium.com/poor-wojaks-almanack-55510dcd3bae) converted from Medium by [ZMediumToMarkdown](https://github.com/ZhgChgLi/ZMediumToMarkdown)._
=======
---
title: "Poor Wojak’s Almanack"
author: "Arthur Hayes"
date: 2021-03-18T22:01:15.200+0000
last_modified_at: 2021-03-18T22:01:15.200+0000
categories: "Hayes"
tags: ["hayes,"blog"]
description: "(Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor…"
---

### Poor Wojak’s Almanack

_\(Any views expressed in the below are the personal views of the author and should not form the basis for making investment decisions, nor be construed as a recommendation or advice to engage in investment transactions\. \)_


![](assets/55510dcd3bae/0*XTXnFAsICvQchcFS)


I became an avid cyclist after the onset of COVID\. I try to ride twice a week for 40–60km\. Given the popularity of cycling with Boomers, you might think it’s a nightclub for uncles on the public bike paths circa 5am — but it’s a high stakes affair\. My top speed hit on a sprint so far is 52 km/h; one wrong move and it’s game over\.

But aside from exercise, my cycling also gives me some much\-needed fresh air to do some of my best thinking\. My cycling buddy happens to be a crypto agrarian as well\. On a recent ride, we got into a risk management discussion about the types of risk Decentralised Finance \(“DeFi”\) “farmers” \(aka liquidity miners\) undertake when putting up their capital\. Based on our conversations, I’ve outlined below a quick history on why farming is popular, and a conceptual framework that evaluates the risk undertaken by crypto peasants\.

**Farmville**

DeFi is an ecosystem of projects that aim to provide financial services to the digital world without the need for centralised financial services providers, such as banks\. For example, many DeFi projects allow people to easily borrow directly from other individuals, who lend out their money in exchange for rewards that are built into the network\. This has massive implications for the future of lending: no credit check, personal data, or bank account is required\. Everyone can participate, and the lending terms are enforced by smart contracts that cannot be tampered with– removing the need for a trustworthy middleman\.

An example of a centralized intermediary is a bank\. In my August 2020 piece [Dreams of a Peasant](https://blog.bitmex.com/dreams-of-a-peasant/) , I spoke about how the DeFi ecosystem is building proto\-banks for humanity’s digital existence\. As a concept, I am fully on board with eventually replacing all banking and financial services with open\-source code\. The ecosystem is nowhere close to fully living up to those ideals, but I am betting that this future will eventually come to fruition\.

Ownership of the projects is open to all, and is based on providing a useful service to the network\. Given many DeFi projects focus on some sort of borrowing, lending, or asset swapping, these projects need lenders and market makers that provide liquidity\. In order to reward people for lending out their assets the projects mint, per a published schedule, a native token and distribute those tokens to all lenders, typically proportionate to the percent of the total lending pool their funds represent\. These tokens each represent a percentage of ownership of the project\. If the project is useful, these native tokens or governance tokens will have a non\-zero value\. In some cases, the tokens may even represent the right to receive a proportional percentage of fees enacted by the platform — e\.g\., receiving a portion of the trading fees charged by a decentralised exchange whose tokens you hold\.

Eventually, these tokens will also give tokenholders the ability to vote on how the protocol operates and is governed\. Imagine a DeFi bank where the tokenholders get to vote on interest rate loan spreads, and the types of collateral that can be lent against\. Or imagine a decentralised asset exchange \(e\.g\., Uniswap, Sushiswap, 1inch, etc\. \) whose tokenholders vote on trading fee rates\.

Below is a hypothetical example of a truncated lifecycle of farming a DeFi protocol’s native token\. Let’s assume this is a simple protocol that allows borrowers to deposit Ether \(ETH\) and borrow a fiat stablecoin Tether \(USDT\) \.
1. The protocol launches, and would like to offer USDT loans collateralised by ETH\.
2. The protocol’s governance token is called CORN\. 1,000 CORN will be distributed every day for the next 1,000 days\. 75% of the daily CORN tokens will be distributed to lenders proportional to the percentage of the USDT lending pool they represent\. 25% of the daily CORN tokens will be distributed to borrowers based on their percentage of daily ETH borrowed\. Something very important to know: you cannot buy CORN directly from the protocol\. You must participate to earn CORN\. Once there are CORN in circulation, you may purchase CORN in the secondary market from willing sellers\.
3. Therefore, even when you borrow or lend on the CORN farm, you are rewarded with ownership in the protocol\. Imagine if you received shares in your Too Big To Fail bank whenever you paid your overdraft fees, or when you paid 20% in fees to cash your government stimmie check because you are too poor to be a profitable client with a real bank account\. My mother recounted that this stimmie cashing situation played out in a blighted section of the inner city\. A line formed down the block, during the previous height of COVID, consisting of poor citizens who had no bank account, weren’t wearing masks, and paid $200 of fees to cash a $1,200 government check\. Disgraceful\.
4. As a lender of USDT, you connect your browser’s Ethereum network wallet to the CORN web3 site \(a popular wallet is Metamask\) \. You approve the connection, and then elect to stake — i\.e\., allow CORN to lend out your USDT\. CORN will pay you an interest rate in USDT by collecting ETH interest from the borrower, and converting it using a Decentralised Exchange \(DEX\), such as Uniswap, to convert ETH into USDT at the prevailing exchange rate\. All this is done programmatically\.
5. If you are a borrower, you again connect your wallet to the CORN platform in the browser\. Instead of staking USDT, you stake ETH as collateral and then borrow USDT and pay a continuous rate of interest in ETH terms\. To repay the loan and receive your ETH collateral back, you send the USDT you owe to the CORN protocol\. The CORN protocol will enforce a minimum leverage ratio based on the external price of ETH/USDT\. If, as a borrower, you breach the minimum level, the ETH you put up as collateral is programmatically sold on a DEX\.
6. As long as you are lending or borrowing, meaning you have USDT and/or ETH staked on CORN, you are continuously being credited with CORN tokens\. The CORN token represents a fraction of ownership of the CORN network, giving its holders voting power to change the CORN protocol and terms of operation, as well as a percentage of interest fees charged to borrowers\. The CORN token has a value determined by the marketplace based on the above traits and can be sold on the secondary market for that price\. To find the appropriate price you could construct a discounted cash flow \(DCF\) model that forecasts total value locked\-up \(TVL\) and uses an assumption on the type of fee income for CORN that will generate\. Plug in a discount factor, and boom — you have a “fair value” for the CORN token\. This is why TVL is the most important statistic for any DeFi project\. The more TVL, the larger the assumed future fee pool, the higher the token price trades\.


Because the market is currently so bullish on the future disruption DeFi projects will cause, their tokens are trading at very high non\-zero nominal values\. Therefore, even if the interest rates are not attractive to potential lenders in and of themselves, the opportunity to generate a token that rises exponentially in price still entices users to stake\.

The act of staking in order to accumulate platform governance tokens that hopefully appreciate in value is the essence of farming\. When you compute the all\-in annual percentage yield \(APY\), the return on your crypto capital dwarfs what you can earn in the centralized “free\-market” interest rate markets of traditional finance\. That sounds amazing, but there are significant risks undertaken by staking on DeFi protocols\.

**Skin in the Game**

Understanding these risks — which are largely tied to how secure the code of these DeFi platforms is — is critically important, as there are a few ways in which you could be at risk of losing some or all of your staked capital\.

While the code for all DeFi protocols is open sourced, most users do not read it\. And many \(like myself\) do not possess the requisite knowledge to discover malicious or poorly\-written code because we don’t understand it\. Even if you wanted to do extensive code review, the speed at which projects accumulate TVL and appreciate in price punishes those slow to the draw\. While you are stumbling through the github, the returns are diminishing\. That is chiefly because the number of tokens distributed remains static, so each lender receives fewer tokens as the number of lenders and TVL increases — diminishing the APY\. Therefore, ape\-ing into contracts without doing any technical due diligence is common and extremely profitable if you are an early mover\.

The more reputable projects will commission a smart\-contract security review by an audit firm\. Quantstamp, Hacken and Trail of Bits are a few of the industry leaders\. However, there is so much interest in this space and so few qualified auditors that obtaining an audit from a reputable firm is almost impossible without a connection to the heads of those firms\.

Here are a few of the common ways to suffer principal loss\.

**Backdoor Hack**

The protocol developers code a backdoor that allows them to drain the contract\(s\) of any staked assets\. This is usually referred to as an exit scam, and the assets are irretrievable\.

**Locked Contract**

The protocol developers coded the contract in such a way that a certain series of actions lock the contract and render all assets inside inaccessible\. A number of high\-profile projects have succumbed to this deficiency\.

**Economic Exploit**

The code as written \(either intentionally or unintentionally\) can be manipulated such that an uneconomic activity is undertaken by the protocol which drains assets from the contract\(s\) \. A common exploit for collateralised lending platforms is a flash loan attack\. [Hacking Distributed](https://hackingdistributed.com/2020/03/11/flash-loans/) wrote an excellent post detailing the many ways flash loans can be used to conduct arbitrage and economically exploit DeFi protocols\.

Backdoor hacks and locked contracts usually result in a 100% loss of staked capital\. Economic exploits usually result in a partial but substantial loss of staked capital\.

As a farmer, you must model the probability that a particular protocol may be hacked and you could lose some or all of your capital\. Given you cannot purchase the token at inception either in the primary or secondary market, the only way to obtain the asset is to stake and place capital at risk\. For the duration that you farm, you are subject to hacking risk\.

The second risk is that because your income is in governance token, the price at which you finally decide to sell it determines your return on capital\. If the platform experiences an unexpected negative event, the token price will decline sharply — thus eviscerating your return\.

However, there are two sound strategies to risk manage your farm and protect your returns\.

**Multiple Crops**

Like any good farmer, you should have multiple crops\. Spreading your capital amongst many different projects reduces your per\-project risk\. This strategy assumes that you have no ability to discern which projects are more or less likely to experience a negative event\. You go fast and hard and jump on any new hot project\. Ape in, collect tokens, and liquidate the tokens continuously to crystallise your profits\. Speed, breadth of tokens, and a high\-risk tolerance are your differentiators\.

Assume you believe that the probability that an event occurs with a 100% loss severity within one month is 30% for any given project\. If you invest in ten projects equally, in one month, 30% of your capital will be lost\. Therefore, your blended APY across the ten projects should be 30% per month just to break even on an expected value basis\. This is just a hypothetical example; I don’t have any empirical evidence that shows the actual statistics\. I’m sure someone reading this might have that data and be willing to share it with you for a nominal fee\.

If the internet veggie you farm has a pumping token price but does not attract TVL quickly you probably should find greener pastures\. You can make a survivorship bias assumption\. That is, the longer the project has been in existence with a large and increasing TVL, the less likely it is to experience a loss event\. Or if there is an event, the percentage severity will be lower\. This is a useful heuristic, but a past devoid of volatility does not necessarily imply a similarly tepid future\.

**Tech Due Diligence**

If you have the rare ability to quickly read and analyse DeFi code, then you have a distinct advantage\. The ability to concentrate capital into ideas with conviction is how you generate outsized returns\. Technical competence allows you to be extremely selective on which projects to farm\. In return, you cannot only farm, but also buy the token itself in the secondary market to double up\.

This is hard to do well\. There are simply too many projects for the limited number of competent security auditors to provide deep and thorough analysis on all of them\. Assessing the vulnerability of projects to the three major risk buckets described above is also difficult to do well\. The biggest issue is that with hundreds to billions of USD worth of TVL on the line, the incentive for malicious actors is significant relative to the amount of effort, time, and expense investors are willing to expend before aping into a project\.

In the Default world, farmers who have the best technology have the best yields\. Internet veggie farming is similar — however, on the electron enabled farm, technology comes in the guise of the ability to lean on competent technical talent to assess the risk of capital loss\.

**Farm or Buy**

This is a crucial decision and depends on multiple factors\. In order to procure the governance token in question, you can either participate by risking your principal and staking, or by purchasing the token in the secondary market\.

The best projects endeavor to distribute as few tokens as possible onto the secondary markets\. That assures significant participation in the form of farming or placing capital at risk for punters to accumulate tokens\. This also results in the recycling of the little supply that is available on the secondary market many times between a few hands and the creation of a positive reflexive feedback loop that results in … MOON\.

If you want to get in early, it is almost essential that you farm\. Farming risks include:
1. Your principal staked is 100% at risk\. A loss event could mean a complete loss of capital\.
2. The tokens distributed have delta price risk which includes an element of platform credit event risk\. If the project is hacked, the token price will fall along with the TVL\. If you do not sell your tokens as you receive them, then your achieved APY will also decline on any loss event\.


Assume you have 100,000 DAI that you stake on a farm — let’s call it Lilipad — which produces LILI tokens\.

You get in as soon as the contract is deployed\. Note: for best results you probably need a bot scanning the Ethereum blockchain monitoring when new contracts get deployed and if they have immediate TVL — especially given rewards are usually proportional to your % of the TVL\. If you are a large % of a small TVL you receive more tokens than if you are a small % of a large TVL\.

The TVL goes from 1 million DAI to 100 million DAI in a week\. Therefore your % of the TVL goes from 10% to 0\.10%; however, the project still only emits 10,000 LILI per day\.

If the price of LILI/DAI goes up 100x in line with the TVL, that is ideal\. Your risk profile and APY have not changed as the project becomes more outwardly successful\.

If the price of LILI goes up less than 100x, then you are taking more risk for less return\. To a nefarious locust, the larger the farm :: TVL, the more edible food\. Therefore your risk of principal losses increases alongside the TVL\. Is your risk 100x greater in line with the TVL? Probably not\. But it is definitely increasing in a non\-linear fashion\.

When you farm, your capital does not increase in value\. Only the token’s value viewed in the currency terms of your capital changes\. Therefore, it is suboptimal to farm just to receive tokens if you can simply purchase the tokens outright\. If your risk tolerance is 100,000 DAI, it would be far better to just purchase 100,000 DAI worth of LILI tokens\.

As you can see, it is not in the interest of the farmer to constantly liquidate their LILI tokens\. Their risk of loss goes up with the TVL, their capital at risk stays constant, and they need their LILI token exposure to increase as well to compensate for the increased risk\. That means they would rather do their part to restrict supply of LILI in the secondary market to encourage an upwardly sloping price trajectory\. This is what I mean by a positive reflexive loop\. As the TVL increases, the price increases, and the risk of loss increases; therefore, if you hold the token and farm, you do not sell\.

Having zero secondary market liquidity is not entirely helpful for the project\. A rapidly appreciating token price brings attention to the project, which results in more TVL\. To encourage some liquidity in the token, many projects will distribute tokens to those who stake in DEX liquidity pools\.

A liquidity pool consists of two assets\. In this example, Lilipad will give LILI tokens to farmers who place equal parts DAI and LILI into either Uniswap, Sushiswap, and 1inch\.There are LILI tokens available for sale, and those who just wish to take delta price risk can purchase LILI\. This also provides farmers who wish to liquidate their LILI crop a market bid\.

The calculus for any farmer participating in the liquidity pool is impermanent loss\. I won’t go into too much detail about this risk, but here is a very good [blog post](https://pintail.medium.com/uniswap-a-good-deal-for-liquidity-providers-104c0b6816f2) describing it\. Impermanent loss is the covariance between the two assets\. As the price of LILI rises, liquidity pool stakers will have less LILI and more DAI\. As the price of LILI falls, liquidity pool stakers will have more LILI and less DAI\. If the LILI sale price is sufficient to cover the impermanent loss, then it is a good deal for the liquidity pool staker\. Because this is a well understood risk, projects will usually provide very high token rewards for liquidity providers enticing them to participate in this scheme\.

If you are able to purchase 100,000 DAI of LILI, then that is most optimal\. However, because the beginning secondary market supply is zero at T0, the incremental supply will carry a high price, and the price will skyrocket in the face of even a small amount of demand\. 100,000 DAI of exposure might pamp the price 100% or more\. That’s fine if you believe TVL will increase quickly but can be fatal if the project is stillborn\.

A simple example illustrates the advantageous position of a trader vs\. a farmer:

Capital = 100,000 DAI

Time = 0

LILI/DAI PRICE = N/A

Time = 1

Capital = 100,000 DAI

Farmed Tokens = 1,000 LILI

LILI/DAI PRICE = 1 DAI

**Downside**

There is a loss event and all of the TVL is wiped out\. The price of LILI/DAI declines to 0\.01 DAI\.

_For the farmer_

Capital Losses = 100,000 DAI

LILI/DAI Losses = 990 DAI

Total Losses = 100,990 DAI

_For the trader_

The trader purchased 100,000 LILI tokens for 100,000 DAI

Capital Losses = 0 DAI \[no capital was staked\]

LILI/DAI Losses = 99,000 DAI

In the downside scenario, the trader outperforms the farmer by 1,900 DAI\.

**Upside**

The TVL increases to 100 million DAI, the LILI/DAI token price also goes up 100x to 100 DAI\.

_For the farmer_

Capital Gain = 0 DAI \[the capital does not appreciate\]

LILI/DAI Gain = \(100 DAI — 1 DAI\) \* 1,000 Tokens = 99,000 DAI

Total Gain = 99,000 DAI

_For the trader_

Capital Gain = 0 DAI \[they did not stake anything\]

LILI/DAI Gain = \(100 DAI — 1 DAI\) \* 100,000 Tokens = 99,000,000 DAI

Total Gain = 9,900,000 DAI

In this extreme upside scenario the trader far and away outperformed the farmer even though they had the same initial capital of 100,000 DAI at risk\. The big assumption in this example is that you can accumulate 100,000 LILI tokens at a reasonable price\.

**A Hard Day’s Work**

Farming internet veggies and other meme tokens appears banal at first, but there are some complicated risks that must be weighed and managed by a burgeoning class of internet peasants\. My views since my prior post [Dreams of a Peasant](https://blog.bitmex.com/dreams-of-a-peasant/) have not changed\. Most of the DeFi projects are of dubious quality and can destroy your capital, but the borrow, lend, asset swap, insurance etc\. web3 powered infrastructure buildout is the bedrock for a more inclusive and equitable financial system\. Financial services for the digital age owned by those who participate the most\.

There will still be ownership concentration issues in this new ecosystem; however, those who take the most risk will garner the largest reward, regardless of their personal affiliations or connections\. This is in stark contrast to how things typically work where your proximity to a centralised power structure determines your ability to share in the spoils of the financial system\. Risk of failure is socialised, and outsized rent\-seeking profits are privatised\. A great game if you are on the inside, and insidiously evil if you are the tax donkey footing the bill\.



_[Post](https://cryptohayes.medium.com/poor-wojaks-almanack-55510dcd3bae) converted from Medium by [ZMediumToMarkdown](https://github.com/ZhgChgLi/ZMediumToMarkdown)._
>>>>>>> 646bbbf0078baf384fc8786f676fd9825d420cd2
