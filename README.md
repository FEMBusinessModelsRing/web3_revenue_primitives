[Join the telegram group](https://t.me/joinchat/DwEd_xcORJOv6m7Li7yOow)

THIS is a living document!  See something you don't like? [File an issue!](https://github.com/FEMBusinessModelsRing/web3_revenue_primitives/issues/new)  Got something you want to see? [File an issue](https://github.com/FEMBusinessModelsRing/web3_revenue_primitives/issues/new)!

# Web 3 Revenue Primitives

<img src='imgs/coins.png'>

*Core primitives* are a set of concepts that are innately understood but cannot be expressed in simpler terms.

This repository is an attempt at list of *web3 revenue primitives*, created by, for, and at [ETHMagicians Prague 2018 by the business models ring](https://hackmd.io/DaJhrasLQteUk3IwX5bQAg?view#8-Business-Models-Ring).

[Notes from Business Models Ring at Eth Magicians, the first session which convened on 2018/10/29, are here](https://hackmd.io/W11KX6Y9R3idXXhN2tHFzA).


More discussions about business models have been taken at ETH Denver 2019.

[Notes from Business Models Ring at Eth Magicians, at ETH Denver on 2019/2/14, are here](https://hackmd.io/N_nZMiA5S5Gtp18gYT14FA).

## TOC

- [Web 3 Revenue Primitives](#web-3-revenue-primitives)
  * [TOC](#toc)
  * [Revenue Share](#revenue-share)
    * [Percentage Fee](#percentage-fee)
    * [Income Share](#income-share)
    * [Government taxes](#government-taxes)
  * [ICOS](#icos)
  * [Continuous Funding Models](#continuous-funding-models)
  * [Streaming Money](#streaming-money)
    + [Side Channels:](#side-channels-)
    + [State Channels:](#state-channels-)
  * [Non Fungible Tokens](#non-fungible-tokens)
  * [Subscriptions](#subscriptions)
  * [Self-Sovereign Identity](#self-sovereign-identity)
  * [Lending](#lending)
  * [Curating](#curating)
  * [Creating](#creating)
  * [Gambling](#gambling)
  * [Crypto trading strategies](#crypto-trading-strategies)
  * [Funding](#funding)
    + [Budgeting](#budgeting)
      - [Limitations of existing Open Source Budget template:](#limitations-of-existing-open-source-budget-template-)
      - [Treasury management:](#treasury-management-)
      - [Additional thoughts:](#additional-thoughts-)
  * [Advertising](#advertising)
  * [Personal Tokens](#personal-tokens)
  * [Stablecoins Business Models](#stablecoins-business-models)
    + [Fiat-Backed](#fiat-backed)
    + [Crypto-Backed](#crypto-backed)
    + [Algorithmic](#algorithmic)
  * [Staking](#staking)
    + [Indirect Staking](#indirect-staking)
  * [Questionable / Possible Ponzi Schemes](#questionable---possible-ponzi-schemes)
    + [Rent](#rent)
- [Revenue Models](#revenue-models)
  * [8(+1) types of revenue models](#8--1--types-of-revenue-models)
  * [Why is this important?](#why-is-this-important-)
  * [Examples of disruptive business / revenue models](#examples-of-disruptive-business---revenue-models)
  * [New revenue models](#new-revenue-models)
      - [The PoolTogether model](#the-pooltogether-model)
- [Web2 Revenue Models](#web2-revenue-models)
  * [Examples](#examples)
      - [Advertising Model](#advertising-model)
      - [Commerce Model](#commerce-model)
      - [Subscription Model](#subscription-model)
      - [Freemium Model](#freemium-model)
      - [Peer to Peer Model](#peer-to-peer-model)
      - [Transaction Processing Model](#transaction-processing-model)
      - [Licensing Model](#licensing-model)
      - [Data Model](#data-model)
- [Accelerants](#accelerants)
- [What did we miss?](#what-did-we-miss-)

## Revenue Share

The Revenue share uses profits to enable separate actors to develop efficiencies or innovate in mutually beneficial ways such as splitting earnings. It has become a popular tool within corporate governance to promote partnerships, increase sales or share costs.

Some popular revenue share examples:

* [Percentage Fee](#percentage-fee)
* [Income Share](#income-share)
* [Government taxes](#government-taxes)

### Percentage Fee

This model is where you take a % of each transaction done on your platform. It is popular with exchanges and marketplaces.

Usually who pays for the % is the seller, since he is the one that gets the benefit of getting a sale done thanks to the connecting provided by the platform. An offline example would be a supermarket.

Notable examples:

  * [Open Sea](https://opensea.io/)
  * [Amazon](amazon.com)
  * [Airbnb](airbnb.com)

### Income Share

A pool of users share earnings from another entity. An offline example would be a restaurant where the cashier shares the tips with everyone. Web 3 takes this model to a new level, for example you could give 1 dollar tip in a coffee shop and split it with every actor in the coffee value chain with a minimal cost of transaction.

Some projects working with Tip Splitting:

* [Meridio](https://www.meridio.co/) Divisible real estate with equity and ownership.
* [Affogato Network](https://affogatonetwork.com/) Split tips to a barista and a coffee grower.

### Government taxes

A community shares earnings in order to improve everyones lives. Corruption makes it a not working model.

## ICOS

Sell a bunch of ERC20 tokens at once, or during a window of time.

Some popular ICO models:

* [Security Token Offerings](https://blockgeeks.com/guides/security-tokens/)
* [Interactive ICO](https://medium.com/legal-block/interactive-coin-offering-a-token-distribution-alternative-model-or-the-new-face-of-the-ipos-61eee71e75ef)
* [Initial Supply Auction](https://medium.com/@MetronomeToken/metronomes-initial-supply-auction-quick-glance-price-chart-c9132595871e)
* [Simple Agreement for Future Tokens](https://medium.com/@argongroup/explaining-the-simple-agreement-for-future-tokens-framework-15d5e7543323)
* [Cryptocurrency Airdrop](https://en.wikipedia.org/wiki/Airdrop_(cryptocurrency))
* [DAICOS](https://ethresear.ch/t/explanation-of-daicos/465)

Some popular ICOs:

* [Neo(China's Ethereum)](https://www.investinblockchain.com/what-is-neo/)
* [Stratis](https://www.investinblockchain.com/invest-in-stratis/)
* [Ark](https://www.investinblockchain.com/what-is-ark/)
* [Populous](https://www.investinblockchain.com/what-is-populous/)
* [Abyss](https://www.theabyss.com/)

Types of tokens:

* [Utility Token](https://medium.com/coinmonks/utility-tokens-a-general-understanding-f6a5f9699cc0)
* [Equity/Security Token](https://blockgeeks.com/guides/security-tokens/)
* [Currency Token](https://cryptocurrencyfacts.com/what-is-a-cryptocurrency-token/)
* [Reward Token](https://bitcoinexchangeguide.com/rewards-token-ico/)
* [Digitalized Asset](https://medium.com/pecunio/the-rise-of-asset-backed-tokens-90570438261c)
* [Digital Asset Token](https://blog.coinbase.com/the-playful-paradigm-shift-4bf35d9d1d11)

## Continuous Funding Models

Continuous Funding Models are business models that sell ERC20 tokens *over time*, rather than all at once.

* [Curved Bonding](https://medium.com/@simondlr/tokens-2-0-curved-token-bonding-in-curation-markets-1764a2e0bee5)

  Curved Bonding is a method of continuous funding that incentivizes early investment. In contrast to conventional ERC20 token sales and ICO's, which feature each individual token being sold for the same price (no matter the time of purchase), such models hardcode buy price according to an algorithmic curve. In doing so, by purchasing early, investors get more tokens for the same price, than if they had purchased later. Thus, using Curved Bonding incentivizes early adopters to invest in a token.

* [Continuous Organizations](https://medium.com/@thibauld/introducing-continuous-organizations-22ad9d1f63b7?_branch_match_id=578515516036471346)

  A continuous organization is one that sets up a *Decentralized Autonomous Trust* (DAT): an immutable smart-contract that implements curve bonding to automatically mint, burn, and distribute security tokens called FAIR *securities*. Organizations provide value to the trust by channeling part or all of their cash flow to it:
  1. When an investor **buys** FAIR, new FAIR tokens are minted by the trust, thus, increasing the price of the existing FAIR tokens. Part of the money invested goes to the organization, and part is held by the trust in its *buy-back-reserve*.
  2. When an investor **sells** FAIR, the FAIR tokens sold are burned by the trust, which decreases the price of FAIR tokens. The trust refunds the investor with funds in its *buy-back-reserve*.
  3. When the trust receives a **payment**, a fraction of the payment is used to mint new FAIR tokens which: (1) increases the price of existing FAIR tokens, and (2) increases the trusts *buy-back-reserve*. The rest of the money goes to the organization.
  4. When the trust receives a **dividend** payment from the organization, the dividend is used to mint and issue new FAIR tokens to current FAIR token holders, thus, increasing both the price of the token and the *buy-back-reserve*.

  In a simpler manner, a *Decentralized Autonomous Trust* allows an organization to:

  1. Continuously mint tokens whenever demand exceeds supply, thus, providing ongoing funding for the organization.
  2. Guarantee that an investor will always be able to buy or sell their FAIR tokens (albeit, not at the price they want) no matter if the token is listed publicly or not, due to the *buy-back-reserve*.
  3. Promote long term investment through the continual minting and dispersion of FAIR tokens upon dividend payments.

  **Note:** Such a business model is regarded as a security token offering and, as such, must comply with the security laws of its jurisdiction.

  For additional information, refer to the [white paper](https://github.com/C-ORG/whitepaper/).

## DAO Models

DAOs are an emerging field of research. There are many models that are live and many new models that are being created every day. The "killer app" of DAOs is the ability to design mechanisms that align the the interests of participants in a way that is trustless and verifiable. This allows anyone anywhere to collaborate on things they care about, make decisions, and get stuff done. In addition, since the DAO itself owns the project's funds (and in the near future code, docs, and domain) the DAO can exist and be supported by a decentralized community regardless of if a founder or core team moves on to something else. 

### MolochDAO

MolochDAO is a well known DAO that is live on Ethereum mainnet. The purpose of MolochDAO is to support development of the Etehreum commons, particularly ETH2. Anyone can request to join the DAO, but they must offer a tribute in the form of ETH. If they are accepted into the DAO they receive a set of DAO tokens proportional to the size of their tribute. The ETH tribute is then owned by the DAO and members of the DAO vote on how to manage it. Members can submit proposals for DAO members to vote on. In the case of MolochDAO, these proposals are all related to ETH2.0 development, but the model can be used for any purpose. If members disagree with a decision made by the DAO members, they can leave at any time provided they voted no on the most recent proposal or have not voted. When a DAO member leave the organization they return their DAO tokens to the DAO, thus forfeiting their ability to vote on future proposals. In exchange they receive a percentage of the DAO's tributes relative to the amount of DAO tokens they own (for example if you had 5% of the DAO tokens you would receive 5% of the DAO's tribute funds at that time). This aligns incentives so that members want to support proposals that other members agree with, because if they don't members will leave and the DAO will have less funds to allocate. This incentive alignment ensures that a wide variety of participants can come together in a trustless manner to support a goal or cause they care about. 

MolochDAO Resources:
- [Web App](https://moloch.vc/)
- [GitHub](https://github.com/MolochVentures/moloch)
- [Community Docs](https://www.burrrata.ch/molochasaurus/)

### 1Hive

1Hive is an Aragon DAO model created to support open source communities. The main goals are to make it easy to make decisions (governance) and to make it easy to reward contributors (sustainability). Due to the composable nature of Aragon DAOs, this is a living model that will evolve over time as Aragon apps are added or upgraded. By the time you read this the 1Hive model may have changed, but this is a description of the original design.

The 1Hive DAO has a dual token model: BEEs (non-transferable token for core contributors) and HONEY (transferable token to reward contributors). Both BEE tokens and HONEY tokens can be used to signal, vote, and move funds. Which apps can do this is up to the discretion of each community. The main idea here is that the core team can manage funds and important decisions in a sybil resistant manner, but the broader community can also contribute, earn tokens, and have a say in decision making. This way you can avoid an all or nothing approach that only uses permissioned membership (1 person 1 vote) or only uses coin voting (1 coin 1 vote).

BEEs control the minting of BEE and HONEY tokens. At any time BEEs can choose to mint a new BEE token to add a member to the DAO. BEEs can also vote to mint more HONEY to reward community contributions and/or to create more bounties. 

1Hive also features the Aragon Bounties and Allocations apps. Bounties allow the core team to create rewards for tasks on the roadmap. Allocations allow the community to allocate transferable HONEY tokens to members of the community who did cool stuff. This is similar to the GitCoin "kudos" model. The idea is to say thank you and recognize and reward contributions that don't fit neatly into the scope of bounties.

1Hive Resources
- [1hive.org](https://1hive.org/)
- [GitHub](https://github.com/1hive/)

### Cryptoeconomics.Study

The Cryptoeconomics.Study DAO is similar to the 1Hive model, but with a few key differences.
- The non-transferable core membership token is GERBIL.
- The fungible community contributions token is CARROT. 
- In addition to just having voting apps for core members or community contributors, there will be a voting app for core members AND community contributors. This will be accomplished via a voting app that "caps" the weight that each token has in a vote. Often times this will be 50/50, but it would be 60/40 or any other configuration. This allows the DAO to start as a more centralized model managed by a core team, and then slowly transition voting power to the community. This also ensures that incentives are aligned between DAO members and community contributors so that one group cannot unilaterally take actions without the buy-in of all parties involved.
- Rather than having the core team set bounties, anyone who holds transferable CARROT tokens can set bounties. This drives value to the CARROT token because it can be bought and used to incentivize the community to do stuff. For example, many current open source projects have an enterprise support model where they offer the software for free, but provide custom support or forks for enterprise clients. With the Cryptoeconomics.Study DAO model anyone could purchase (or earn) CARROT and stake it to bounties requesting support from the community. Since Cryptoeconomics.Study is a course and community based around education, we anticipate new users purchasing CARROT tokens to stake to tutoring or code review requests.
 
Cryptoeconomics.Study Resources
- [Cryptoeconomics.Study](https://cryptoeconomics.study/)
- [GitHub](https://github.com/cryptoeconomics-study/)

## Streaming Money

### Side Channels:
A sidechain is a separate blockchain that is attached to its parent blockchain(mainchain) using a two-way peg. You can move assets to the sidechain and then back to the parent chain.
Sidechains need their own miners. These miners can be incentivized through ‘merged mining’, whereby two separate cryptocurrencies, based on the same algorithm, are mined simultaneously.
Here is a list of some of the Sidechain Projects:

* [POA](https://poa.network/)
* [Truebit](https://truebit.io/)

### Plasma Chains:
Plasma chains are like sidechains in that users can move tokens between the plasma chain and the layer 1 blockchain. Unlike sidechains (which have their own miners and security gauruantees which are divorced from the blockchain they are bridged to), plasma inherits all of the security properties of the layer 1 blockchain that it extends. In Ethereum this is includeds data availbility, data validity, and livliness / censorship resistsance (any party can submit transactions and valid transactions are always processed).
* [Plasma](http://plasma.io/)
* [Plasma Group](https://plasma.group/)
* [Loom](https://loomx.io/)

### State Channels:
State channels are basically two-way pathways opened between two users that want to communicate with each other in the form of transactions. Here, only the final outcome needs to be included in the form of one single transaction on main chain. Other transaction's are done on off chain. Few know projects around it are:

* [Raiden Network](https://raiden.network/)
* [Machinomy](https://machinomy.com/)
* [FunFair](https://funfair.io/)
* [Liquidity](https://liquidity.network/)
* [Trinity](https://trinity.tech/#/)
* [Celer](https://www.celer.network/)
* [Spankchain](https://spankchain.com/)
* [Connext](https://connext.network/)
* [Counterfactual](https://counterfactual.com/)

## Non Fungible Tokens

Non fungible tokens are tokens that are unique from one another

Famous NFT projects:

* [CryptoKitties](https://medium.com/@codetractio/a-look-into-cryptokitties-revenue-model-6466b705a998)
* [OpenSea NFT marketplace](http://opensea.io)

## Subscriptions

Subscriptions are a recurring exchange of value over time.

* [EIP 1337](https://github.com/ethereum/EIPs/pull/1337)
* [1337 Alliance](https://1337alliance.com)

## Membership

Similar to the subscription model, but without the promise of regular content. Memberships can be on off (often for early supporters) or require recurring payments (think gym membership). Members often get perks such as access to exclusive content, access to early releases of content, member only events, and special pricing discounts, and more. 

* [Unlock](https://unlock-protocol.com/blog/unlock-donations/) - Unlock uses Ethereum contracts and NFTs to allow supports to get a membership token for a project they support.

## Self-Sovereign Identity

Identity Standards Proposals:
* [EIP 725](https://github.com/ethereum/EIPs/issues/725)
* [EIP 725 Alliance](https://erc725alliance.org/)
* [EIP 1056](https://github.com/ethereum/EIPs/issues/1056) and [ERC 780](https://github.com/ethereum/EIPs/issues/780)
* [Identity Foundation](https://identity.foundation/)
* [Decentralized Identifiers (DID)](https://w3c-ccg.github.io/did-spec/)

Projects in the Identity space:
* [uPort](https://uport.me)
* [Civic](https://www.civic.com/)
* [BloomID](https://bloom.co/identity/)
* [TENZ-ID](https://tenzorum.org/tenz_id/)
* [Ethereum Name Service](https://ens.domains)

## Lending

Smart contracts that control credit scores, loan issuance, and interest payments will run on top of protocols like Ethereum. These debt contracts will be hashed into existence and generate hashflow for the lenders. This is a flow of hashflow above the base layer protocol.

* [Dharma Protocol](https://dharma.io/)
* [LoanScan](https://loanscan.io/)

## Curating

The job of a search engine like Google is to collect and curate data from the Internet. This is one of the most valuable curation projects in the world. The key with curation markets is to get all of the incentives aligned so that you can trust the underlying data. The term used in the industry is the Token Curated Registry.
It’s not just about creating a list. It’s about creating a list you can trust by incentivising curators to do the research for you.

* [Ocean Protocol](https://oceanprotocol.com/)
* [Messari](https://messari.io/)

## Creating

The creation of new things on chains will have value. Selling them to people who want them will generate hashflow. Making these unique tokens takes a lot of effort. You have to get a community of people to agree to their value.

* [Cryptokitties](https://www.cryptokitties.co/)

## Gambling

Decentralized applications focused around Gambling capitalize on the fixed-state nature of smart contracts to enable betting. Common examples of these applications include:

* [Ethercrash](http://ethercrash.io)

  Ethercrash is a crash-styled gambling game. It allows users to deposit ETH (which is added to your site balance after twelve confirmations), and handles payouts through a smart contract. In terms of business models, it allows users to invest in the operation by providing contract liquidity in the form of an [ethercrash investment](http://ethercrash.io). Users can stake their ETH for a percentage of house returns.

* [Etheroll](https://etheroll.com/)

  Etheroll is a dice-styled gambling game. It is completely built around a smart contract which automatically pays gamblers. After selecting a win percentage, the contract randomly determines a round ticket. If the round ticket matches your predictions, you are sent a multiple of your original deposit. If the round ticket does not match your predictions, you have lost, and you are sent back `1 wei` to signify a loss. In terms of business models, Etheroll accepts liquidity investments in the form of [Etheroll DICE tokens](https://etheroll.com/#/dice-token), which are ERC-20 tokens that provide quarterly ETH dividends (from house profits) to their holding accounts.

* [Fomo3D](https://exitscam.me)

  Fomo3D gained popularity as being one of the largest Ethereum gambling DAPPs in late-2018. In a simple pot-styled game, users purchase keys, which increases the pot timer. Over time, the price to purchase a key increases as well. The profits from purchasing a key at an increased rate are dispursed amongst the previous key holders, and the individual to purchase the last key when the pot timer runs out wins the value of all the keys currently in the pot. A better, in-depth explanation of the investment system behind Fomo3D can be found [here](https://fomo3d.hostedwiki.co/pages/Fomo3D%20Explained).

## Crypto trading strategies

Not unsimilar to conventional market trading, crypto markets have their own set of strategies utilized by various traders:
1. **Algorithmic trading** - Algorithmic trading is commonly used in crypto markets to programmatically automate trading in response to varying market data. Based on defined sets of rules (including timing, price, quantity, or even a mathematical model), this type of trading not only eliminates the factor of human sentiment when making market decisions, but also enables 24/7 automatic trading, with limited human input, enabling instant and accurate order placement with reduced risk of manual errors.
2. **Machine Learning-influenced trading** - Machine Learning-influenced trading is another strategy becoming more popular with improvements in AI/ML. This method involves using Machine Learning to analyze past trends and factor in existing market conditions in real-time, to execute trades based on the analyzed data. This allows for traders to make better predictions through probabilistic analysis. 
3. **Arbitrage** - Arbitrage encompasses the simultaneous buying and selling of an item (in this case, crypto) across different markets in order to take advantage of different prices for the same asset. It is commonly exercised by crypto traders on exchanges, by purchasing crypto at a lower price than what it sells for on competitor exchanges, thus, netting them a profit, while also equalizing the price spread across exchanges.


## Funding

Funding is the same whether it is at the ecosystem level or at the level of a single entity wanting to support funding. Grants are the main source of funding for projects in the Ethereum Community. Grants give a short time horizon for projects and don’t take into consideration the setup costs. Once a project has been set up, maintenance requires longer-term funding than grants provided. In many cases for an individual or small team, a business model of services can be considered on a project to project basis to find long term support. Operational costs hit projects with real-world budget and cash flow problems, and decentralized projects excel when they gather together for support.

There is no one entity in charge of Ethereum, so the community must look at different funding bodies and revenue streams. For decentralized projects, it is a good idea to have different funding for different aspects of the ecosystem, such as stack, research, or community.  Obtaining multiple entities to fund a project is part of the shared ecosystem of Ethereum. Multiple entities of funding stop the community from defunding project Y, and instead disperse funding to both project X and Y. To get funding and sustainability of a project, it is best to collaborate with others who want to support the infrastructure, rather than waste time on putting together grant systems.

* [Funding Taxonomy](https://ethereum-magicians.org/t/funding-taxonomy-issues-for-ethereum-ecosystem/2014)
* [Funding Opportunities](https://github.com/fredexed/crypto-funding-ops)
* [Web3 Grants](https://hackmd.io/z5zFMTjiRJqs-4Wm43bJtQ)

### Budgeting
Closely associated to funding, budgeting and appropriating long-term cashflow is essential for the success of Ethereum projects, teams, and individuals. With an increasing focus on long-term sustainability, it is essential to outline a fundamental budget to track funds and plan for the foreseeable future. The [Open Source Budget](https://docs.google.com/spreadsheets/d/1CqaIu4ZupDWU0IedRXQw2coJptUhhyyMTu7ep6nNmIU/edit#gid=989402327) template by Boris Mann simplifies this concept into a simple, single currency spreadsheet for tracking expenses, basic payroll, and funding sources, in order to provide an outlook into long-term financial stability.

#### Limitations of existing Open Source Budget template:

  Identified limitations of the Open Source Budget template should be taken into consideration by Ethereum projects, teams, or individuals. These include:

  * The template assumes zero cost for an office or hardware.
  * The template does not factor in annual taxation or tax subsidization.
  * The template provides the "break-even" for a project, ignoring the potential need of a margin, or, buffer.

#### Treasury management:

  With projects being built on Ethereum, treasury management is also essential. Highlighted in a [Twitter thread](https://twitter.com/DeanEigenmann/status/1064723747582619648), it is generally recommended by Boris to keep upwards of six months of expenses for a team as a buffer. In addition, teams and projects should clarify their policies on payroll and payable expenses, to prevent market instability and variance from affecting their budgets (in the case that their budget is primarily in Ethereum or other non-fiat currencies).

#### Additional thoughts:

  With grants being main sources of funding for projects in the Ethereum Community, understanding their impact to long-term security & sustainability is essential. While one-off bounties and small grants may fund for the short-term, projects should look into additional sources of funding to ensure that they: (1) do not have to devote time and value to search for additional short-term funding, and (2) have a sustainable source of funding for their foreseeable project runway.

## Advertising

There are some options for doing advertising-based business models for open source projects, listed below.

* [CodeFund](http://codefund.app)

## Personal Tokens
Personal tokens are fixed-supply and -cost ERC20 tokens that derive their value from the performance of a human being. They are commonly used to tokenize either individual service offerings or a fixed-price hourly service.

* [DAppBoi](https://dappboi.com/)

  DAppBoi is an example of a personal token which tokenizes an hour of digital work by designer Matthew Vernon. By initiating the ERC20 token with a fixed supply of 100 $BOI tokens, purchasable directly from Matthew for 0.65ETH each, this personal token allows an individual to effectively purchase, trade, and invest in Matthew's design skillset.

  The tokens are redeemed by sending them to Matthew, who in exchange for 1 $BOI token provides 1 hour of design work. By using a personal token, not only does Matthew create demand for his skillset through a fixed token supply, but he also ensures that he will receive a minimum of 0.65ETH for each hour he works, since he is the primary supplier of the token and hence, regulates its price. In addition, using a personal token ensures that even if the market price for $BOI falls, Matthew will have already been compensated at his pre-determined hourly rate for the tokens in circulation.

  In the case that Matthew denies service to an individual who redeems $BOI, although the market valuation for the token may fall, Matthew has already been paid in advance for the initial purchase, thus, fulfilling his hourly rate.

 * Equity based

 In this model people are obligating to use % from their pre-tax or post-tax revenue to buyback issued tokens. It's similar to Income Share Agreement ( implemented by Lambda School ). Because of that the marketcap of tokens is tied to person earning ability.

 * Debt based

It's possible to sell hours of work upfront for further redeeming ( used by DAppBoi ) - issued tokens represent debt redeemable for work directly.

## Radical Markets

### Constrained Capital Liberal Radicalism

The funding for Liberal Radicalism is likely to come from philanthropists or some dedicated government appropriation rather than from unlimited tax revenue. Capital-constrained Liberal Radicalism (CLR) aims to answer how philanthropists can fund public goods or services optimally. Traditionally funding is likely to come from philanthropists or some dedicated government appropriation. Funding can optimally be distributed to project by making contributions proportional to the number of contributions already received by the community. This allows collective decision making by the community in funding and will benefit a public good or service based on the good it provides to the community.

### Property is Monopoly

Imagine a world in which all major private wealth is constantly for sale at a fair price and where most of the value of this property is paid out equally to all citizens as a social dividend. While some might believe that the wealthy would dominate such a market, the most private wealth would become shared by all. Every asset would become cheaper to own, at the same time making large scale projects to become far easier to develop. In a system called Common Ownership Self-Assessed Tax (COST), every citizen would self-assess the value of assets they possess, pay tax on these values, and be required to sell any additional assets at this price. The tax would eliminate the need for other taxes on capital and reduce income tax, at the same time providing benefits through social dividends or funding public infrastructure. COST would create a healthier relationship to property, and help the community seek to increase the value of commonwealth.

### Radical Democracy

Envision a world where political minorities could be protected at the ballot without having the rely on judges or compromises on sensitive issues. With the trading of influence, the minority could overwhelmingly vote out oppressive politicians while the majority will keep the candidates that represent the best direction for the country. With Quadratic Voting, every citizen receives an equal amount of credits used to vote in collective decisions. Any issue can be voted on individually with these credits. The cost of a vote must be quadratic in the number of votes acquired, bringing an incentive to vote in proportion to the importance of the issue. This would lead to social decisions producing the greatest good for the greatest number of people.

### Uniting the World's Workers

The Visas between Individuals Program (VIP) gives the ability to sponsor an immigrant to citizens, while also benefiting the citizen through the sharing of gains. The program is not much different from today's world, where instead of the H1-B program trading sponsorship for gains to corporations the gains would be given to the individuals sponsoring. The migration would benefit all citizens, giving an extra stipend for hosting the migrant works and removing migration as a divisive issue in most countries. VIP would reduce the inequalities across countries, and allow the migrants to send back their earnings to their impoverished families. VIP would begin to break down the boundaries of wealthy countries and help out the poorer countries.

### Dismembering the Octopus

There is a possibility that, just by changing the structure of corporate ownership and antitrust regulations, wages will grow, prices will fall, and decent-paying jobs will become more available. Although the standard of living has stagnated the past 40 years, the stock markets have soared and the gap between the wealthy and poor has grown. The fundamental problem is that the antitrust laws the keep competition high have been unenforced. A simple, yet radical solution would be to limit institutional investors from investing in more than one company in each industry. This would force the promotion of competition between multiple companies in an industry. Antitrust prohibitions would also be applied to mergers, prohibiting the lowering of worker's wages to increase prices. All the is needed is for government antitrust enforcers or harmed groups of citizens to band together to defend their cause.

### Data as Labor

Data could be honored as an individual's work and compensated, instead of gathered by tech companies today. This change would open more well-paying jobs, and convert our passive consumers of entertainment to producers of data. With Data as Labor (DaL), we can build a fairer, more equal society, and spur the development of technology and economic growth. Data suppliers are currently not properly rewarded for contributions and lack the incentive to produce high-quality data. This wasteful model results in the dominance of large tech companies, such as Google, being able to thrive off of free user data. Awareness amount users about their data value make a large difference and empower them to demand more fair compensation.

## Stablecoins Business Models

The main component behind stablecoins capturing value in a market is seigniorage. This is profit made by issuing currency, which is generated from the difference of the face value of the currency and its production costs. The three major types of stablecoins are:

* Fiat-backed
* Crypto-backed
* Algorithmic

### Fiat-Backed

A fiat-backed stablecoin system will collateralize every stablecoin issued with fiat currency or some other non-crypto asset. The fiat currency is stored with some custodian, such as a bank or major institution.

These stable coins can generate revenue from collecting fees on issuing/redeeming stablecoins, market-making, or short-term lending. The most popular fiat stablecoin systems today are:
* [Tether](https://tether.to/)
* [TrueUSD](https://www.trusttoken.com/trueusd/)

### Crypto-Backed

Crypto-backed systems provide decentralized ways to maintain claims on collateral. Reserves of collateral are kept in the form of crypto-assets (such as ETH) on smart contracts. All issued stablecoins are backed by these reserves of ‘volatility coin’ collateral.

Crypto-backed stablecoin systems focus more on the volatility coin put up as collateral to generate revenue. These systems can collect transaction fees created on-chain. Holders of the volatility coin are then paid proportionally.
In the case of Maker, they issue stablecoins as collateralized debt positions, which accumulate interest at an annual rate of 2.5%. The interest is again paid proportionally to those holding on the volatility coin. Other crypto-backed stablecoins have issued shares for collateral assets, which can be redeemed in exchange for stablecoins or another asset. Check out:
* [Maker](https://makerdao.com/en/)
* [Havven](https://www.synthetix.io/)

### Algorithmic

A newer business model, algorithmic stablecoins adjust supply to stabilize price without collateral requirements. These stablecoins may use a volatility coin to capitalize the system at first. This system is very lucrative due to the fact that all supply increases in the stablecoin are distributed to those holding on to the volatility coin.

These stablecoin systems can issue shares called seigniorage shares. When there is demand for more stablecoins, more are issued to offset demand and keep price level. If demand decreases and price of stablecoins fall, shares are put up for sale in exchange for stablecoins, which are then burnt from supply. Therefore, if the market cap of stable coins reaches a certain level, the value of all seigniorage shares will be at that same level.

Another revenue-generating tactic are variable interest rate deposits, where users can deposit stablecoins into smart contracts that pay out interest. When demand is low, interest rates are increased to incentivize depositing stablecoins, which lowers the circulating supply of stablecoins and price increases; and vice-versa.

### Staking

Staking could be a main way to generate revenue in the future. Right now, the only use revenue-related cases are service-based staking pools like Rocket Pool. Many staking-related models have appeared in 2019, of which the most common example is melding ICOs and staking together such as in NuCypher's worklock and Edgeware's lockdrop. Most notably, a [serious review of businesses staking their reserve assets](https://medium.com/@ameensol/what-you-should-know-before-putting-half-a-million-dai-in-compound-fafdb2645f77) was performed by a Spankchain.

## Indirect Staking

We can extend the worklock/lockdrop model from an initial offering into a sustainable revenue primitive for proof-of-stake base-layer blockchains. A dApp built on such a blockchain would allow users to stake base-layer tokens to mine dApp tokens (or earn other forms of utility such as reputation), and then the dApp would utilize this pool of staked layer 1 tokens to earn mining rewards on the layer 1. In a proof-of-stake system where slashing occurs (e.g. slash 33%), a smart contract could enforce that the dApp needs to provide 33% of stake and "top up" 66% from users such that user funds would not be compromised. In this case, the "mining" done by dApp users provides a revenue stream to the dApp in non-zero-sum manner which is extremely sustainable.

## Questionable / Possible Ponzi Schemes

TODO - What else should live here?

* [Fomo3d](https://medium.com/@eetusro/i-note-this-is-fin-e-6646f4a1e55b)

### Rent

* [Determining a fair rent model of ENS](https://discuss.ens.domains/t/determining-a-fair-rent-model/603) = NOTE: At ENS, the purpose of the rent is to avoid squatters rather than making profit


## Exchange Business Models

### Fees

The main model that exchanges use to generate revenue is through trading fees. An exchange will take x% fee on a per trade basis, creating income by providing a service. What differentiates exchanges is how those fees are taken. Fees can be taken through the form of a utility token, a percentage of the token you are trading, or out of a balance you carry. The fees for the top exchanges are found below.

| Exchange  | Maker  | Taker |
| --- | --- | --- |
| Binance   | 0.1%   | 0.1% |
| Bit-Z     | 0.08%  | 0.12% |
| ZB        | 0.2%   | 0.2% |
| LBank     | 0.1%   | 0.1% |
| Upbit     | 0.25%  | 0.25% |

Exchanges take fees on all withdrawals as well. Under normal conditions, there is a 0% deposit fee and x% withdrawal fee. This incentivizes customers to deposit cryptocurrency into their exchange and start trading, bringing more users to the platform. Withdrawal fees incentivize the user to stay and keep using an exchange's service, increasing the overall revenue of an exchange.

The general business model for an exchange:

Bring in users -> Provide a service for fees -> Incentivize users to stay on the platform

### Utility Token

The current largest exchange, Binance, was the frontrunner of including a utility token into their business model. Binance started with a token sale and then continues to add utility to the token as it interacts with their exchange. Binance and other exchanges have added features to their token including:

* Discounted usage on fees
* Exclusive usage in token sales
* Burn tokens equal to % of revenue
* Voting for listing
* New Listing Airdrops

Having a utility token with perks incentivizes more customers to join the platform, creating more revenue and traffic throughout the life of the platform.

### Listing Model

An exchange's listing model often contributes to the daily volume and revenue. Many exchanges require a listing fee for a new token to be brought onto their platform. Token creators will pay that fee to increase liquidity in their token, and the exchange will bring more customers to the platform listing tokens with large user bases. However, making sure that an exchange has a high-quality pool of tokens contributes to the daily volume and brand of the exchange.

<img src='imgs/Volume_Over_Tokens.png'>

We can see here that the number of tokens that an exchange has diminishing returns. Exchanges with higher listing policies, such as [Binance](https://www.linkedin.com/pulse/binance-listing-tips-changpeng-zhao/), have a higher return per token listed.

### ICO Host

Exchanges such as Binance have hosted ICO's on their platform as a model of bringing in more users. Have an ICO hosting on your platform creates an exclusivity of a token in your ecosystem, forcing customers to come to join your platform in order to retrieve that token. Binance has been employing this with multiple ICOs, [selling out on the ICOs within seconds](https://twitter.com/cz_binance/status/1100040669752549378). This business model brings a lot of users to their platform and creates higher volume with these tokens.

### Referral Program

Often employed by exchanges, referral programs provide a small incentive to their current user base to advertise and bring others onto the platform. Different incentives include:

* Percentage of fees
* Token reward for every user
* Discount on fees

### Business Model Success Through Bull and Bear Markets

Different business models will succeed or fail in a bear or bull market. The following is a study of Binance, Kucoin, and Bitmex throughout these two markets:

<img src='imgs/Quarterly_Profits.png'>

Binance and Kucoin's quarterly revenue is public and verified on the blockchain due to their quarterly token burn. We can see that throughout the life of each exchange, they both took a downturn after Q2 2018, where the market changed from a bull to bear market. Both dropped significantly, but Binance is able to sustain a large amount of revenue by building an ecosystem around them. They have worked tirelessly to increase the adoption of BNB, their token, and add features of BNB to the exchange.

<img src='imgs/Bitmex_Monthly_Volume.png'>

Bitmex's Volume over both bear and bull markets shows a noticeable difference than Binance and other major exchange. Bitmex offers leverage and options in order to short or long bitcoin and other cryptocurrencies. Because of this, Bitmex has thrived in the bear market as customers have got on their platform in order to make similar gains during the previous bull market.

# Revenue Models

This breaks down business revenue models into 8 types and provides examples of each. In addition, we reference Ben Wenmuller’s series of tweets with a potentially new business model for decentralized platforms - capital gains.

## 8(+1) types of revenue models

||Description|Examples|
|--- |--- |--- |
|Unit sales|Sell a product or service to customers|Daily necessities at local market|
|Advertising fees|Sell others opportunities to distribute their message on your space.|Billboards, banner ads, search engine ads|
|Franchise fees|Sell the right for others to invest and manage a version of your business.|Fast food restaurants, e-sports leagues|
|Utility fees|Sell goods and services on a metered basis.|Road tolls, electricity and water bills|
|Subscription fees|Charge a fixed price for access to services for a set period of time.|Video and music streaming, gym memberships|
|Transaction fees|Charge a fee for referring, enabling, or executing a transaction between parties.|Credit card merchant fees, online stock trades|
|Professional fees|Provide professional services on a time-and-materials contract.|Lawyers, accountants, real estate agents|
|License fees|Sell the rights to use intellectual property.|Physical toys based on movie characters|
|Capital gains*|Rises in asset value (i.e. tokens) will benefit both the decentralized platform and its users/hodlers|Decentralized startups|


[*As proposed by Ben Werdmuller’s tweets.](https://twitter.com/benwerd/status/1060209690808745985)

## Why is this important?
A company’s revenue model, very simply, is the way it makes money. New applications of revenue models against traditional revenue models can create disruptive new businesses.

## Examples of disruptive business / revenue models
Video Entertainment

Company A - retail stores, charge per rental (unit sales)

Company B - online “DVDs-by-mail”, monthly fee (subscription)

## New revenue models
How can decentralized platforms up-end the revenue models for businesses that seem to have their revenue model locked in?

For example, payments, which has been based on utility fees.

### The PoolTogether model
#### (tangential to unlimited growth)

Works like this:

1. At genesis, there are 0 Dai in the contract.
    
2. The contract will issue 1 PTG token for 1 Dai. The first user submits 1 Dai to the contract, and receives 1 PTG token.
    
3. Now, there is 1 Dai in the reserve. The new price for 1 PTG token is 1.01 Dai.
    
4. A second user believes very strongly that PoolTogether will be very successful, and capture a lot of Dai in its reserve. They come and purchase 1,000 PTG tokens for the cost of ~1,500 Dai (the bonding curve updates its price for total order size, as Uniswap does).
    
5. Because of this sale, the first user that purchased 1 PTG token at 1 Dai, can now come to the bonding curve, and submit their PTG token, and receive 1.50 Dai, for a .50 Dai profit.
    
6. But the first user also thinks that PoolTogether will be successful, so he doesn’t.
    
7. Everyone wants some exposure to PoolTogether. The bonding curve takes in 500,000 Dai over the next few months, and issues 200,000 PTG tokens, now worth 2.5 Dai each.
    
![This is how it grows together](https://miro.medium.com/proxy/1*rvTSneINGx3IunJcdjW8Ew.jpeg)

8. The 500,000 Dai issued by the bonding curve goes to the Dai Reserve, is lent in compound, and receives ~675 Dai in interest rate every week (7% interest rate). This 675 Dai goes to the winning pool of the PoolTogether Lottery, which attracts many users and ticket sales, which adds funds to the Dai Reserve as well.

9. The cycle repeats.

For the complete description of the model visit https://medium.com/@TrustlessState/funding-model-for-pooltogether-and-other-money-lockup-apps-86b928900efa.

# Web2 Revenue Models

 The system designed by which a business monitizes its services
---
*"The ideal revenue model will be one that improves the user experience, or at least in no way harms it."*

| Model     |                                      Description                                      | Examples |
|:------------------------:|-------------------------------------------------------------------------------------|:----------:|
| Advertising            |       Service is free to use, marketers pay to reach your users via advertising       | [examples](#advertising-model) |
| Commerce               |             Sell something to your users, keep some or all of the proceeds            | [examples](#commerce-model) |
| Subscription           |     Charge your users monthly or annually for the opportunity to use your service     | [examples](#subscription-model) |
| Freemium          |     Sell a basic free product to as many customers as possible, but keep the premium features exclusively for paying customers     | [examples](#freemium-model) |
| Peer to Peer           |  Connect people together in a network, take a small piece of the activity that ensues | [examples](#peer-to-peer-model) |
| Transaction Processing |      Settle transactions, then take a small piece of the transaction for doing so     | [examples](#transaction-processing-model) |
| Licensing              |          Charge users once upfront for the opportunity to use your technology         | [examples](#licensing-model) |
| Data                   |                          Sell the data your service generates                         | [examples](#data-model) |
| Mobile                 | Not a revenue model but presents unique challenges and opportunities for monetization | [itunes app store](https://itunes.apple.com/us/genre/ios/id36?mt=8) |
| Gaming                 | Not a revenue model but presents unique challenges and opportunities for monetization | [steam](https://store.steampowered.com) |

These categories are not mutually exclusive. Many web/mobile services use multiple revenue models. Freemium for example is a combination of advertising & subscription.
---
## Examples

#### Advertising Model
* Search Ads - [Google](https://google.com)
* Video Ads - [Youtube](https://youtube.com)
* Location-based Ads - [Foursquare](https://foursquare.com)

#### Commerce Model
* Group buying - [Groupon](https://groupon.com)
* Digital goods/downloads - [Itunes](https://itunes.com)
* Auction commerce - [Ebay](https://ebay.com)

#### Subscription Model
* Software as a Service (SaaS) - [FreshDesk](https://freshdesk.com)
* Infrastructure as a Service (IaaS) - [AWS](https://aws.amazon.com/)
* Membership services - [Amazon Prime](https://www.amazon.com/gp/prime
)

#### Freemium Model
* [Dropbox](https://dropbox.com)
<img src='imgs/dropbox.jpg'>

* [Adobe](https://adobe.com)
* [LinkedIn](https://linkedin.com)

#### Peer to Peer Model
* [Airbnb](https://airbnb.com)
* [Uber](https://uber.com)
* [Match.com](https://match.com)

#### Transaction Processing Model
* [Paypal](https://paypal.com)
* [Stripe](https://stripe.com)
* [Google Pay](https://pay.google.com/)

#### Licensing Model
* Per Device/Server License – [Microsoft products](https://microsoft.com)
* Per Application instance – [Adobe Photoshop](https://adobe.com)
* Patent Licensing – [Qualcomm](https://qualcomm.com)

#### Data Model
* User data - [LinkedIn](https://linkedin.com)
* Search data - [Google](https://google.com)
* Benchmarking services – [Comscore](https://comscore.com)

# Open-source business models
Open-source business models enable projects and organizations to collaboratively build software made freely available for redistribution or modification, while still being profitable ventures.

A few examples of tried and true open-source business models, summarized from Eric S. Raymond's [Magic Cauldron](https://blog.licensezero.com/2018/10/17/mapping-models.html) include:

* *Loss-Leader/Market Positioner*, example Mozilla, from Netscape developed to prevent Microsoft from dominating the web browser market.
* *Widget Frosting*, example Darwin, developed open-source to promote driver-support and reduce interface-tool development cost.
* *Give Away the Recipe, Open A Restaurant*, examples Cygnus and RedHat, which offer professional services and support for their open-source offerings.
* *Free the Software, Sell the Brand*, example Star Office, now OpenOffice.org. Many frequent contributors and platform developers run their own LibreOffice certification businesses to fund platform development.
* *Free the Software, Sell the Content*, for any intangible media businesses.
* *Free the Future, Sell the Present*, example Ghostscript, with older-versions being offered open-source, and newer-version sales driving business revenues.

## Free the Future, Sell the Present
Of the functioning business models above, one of the models is unlike the others: *Free the Future, Sell the Present*. Focused around being a value-added selling proposition, such business models focus on the value of the software being sold. As [License Zero](https://blog.licensezero.com/2018/10/17/mapping-models.html) put it best:

> The value they sell is the value of the software, and the software is open.

In a simple way, this license builds upon two concepts: *Dual Licensing* and *Delayed Release*:

1. Dual Licensing is the concept where individuals are open to develop on older source, but, they can pay to easily ship the latest-and-greatest version, without making the rest of their systems open to competitors.
2. Delayed Release is the concept that allows closed-software to be released as open source on a schedule. Before the release date, the license gives permission for non-production use only. On the scheduled release date, the license’s terms automatically transform into those of a standard open source license.

## What do users need to benefit from software?
Another aspect to consider when choosing a business model is to consider the needs of the user. A generalization is:

* *Implementation*: Users can't run software that doesn't exist.
* *Distribution*: Users can't run software someone else wrote, but didn't share.
* *Permission*: Users can't safely run software without a license.

From a users point of view, developers can choose to meet these requirements partially or completely:

> They can implement what one customer needs or wants, but not what another does. They can distribute copies to some users, but not to others. They can grant permission for the software to everyone, or only to specific customers.

## Constraints
Finally, when choosing an effective model, it's necessary to look forward to the future and consider constraints. Norms of open-source software limit developer freedom and choice, and understanding the limitations associated with open-source development is essential. For example, from a legal perspective, it's difficult to reduce the permissions of published open-source material, but, it is relatively straightforward to do the same for unpublished or proprietary content.

#### *Additional information*
For more information, [License Zero](https://blog.licensezero.com/2018/10/17/mapping-models.html)'s blog on mapping models should be referenced.

# Accelerants
Accelerants are pieces of useful and resuable infrastructure. They are commonly leveraged by users to quickly prototype their projects. Due to their extensive use, they are reliable components to use when developing new applications.

### Examples of accelerants:

* [Wyre](https://www.sendwyre.com/)

  Wyre, founded in 2013, is a developer-first exchange that offers crypto to fiat and compliance solutions. Its most popular offerings are the [Wyre SDK](https://docs.sendwyre.com/) and [Wyre API](https://docs.sendwyre.com/docs/general), which allow developers to easily integrate a fiat onramp into their applications, in under ten lines of code.

  According to a [report by Cambridge](https://www.jbs.cam.ac.uk/fileadmin/user_upload/research/centres/alternative-finance/downloads/2019-01-ccaf-2nd-global-cryptoasset-benchmarking.pdf), there are near 35 million ID-verified crypto users. This leaves an untapped market of upwards of a billion potential users who aren't as adept with crypto. Wyre aims to resolve this by making it easy for DAPP and conventional application developers to allow users to seamlessley convert their fiat funds (in the countries where Wyre operates) to Crypto.

  Wyre is a frequently used accelerant. An example of its integration is [AirSwap](https://www.airswap.io): a decentralized crypto exchange. Via Wyre, Airswap is able to offer users the ability to purchase crypto using USD, GBP, EUR, and AUD, all integrated directly into Airswaps existing interface and self-custodied wallet.
* [Portis](https://www.portis.io/)

  Portis is a JavaScript SDK for developers and online wallet that gives users a simple and secure gateway to the Ethereum network. Acting as a [Gateway as a Service](https://medium.com/@portis/portis-connecting-users-to-dapps-bea1c1d16063), Portis allows users to create wallets in their browser, use these wallets across DAPPS (without installing any extensions or third-party applications), and have complete control over their private-keys.

  For developers, using the Portis SDK and [npm module](https://www.npmjs.com/package/portis) is the simplest way to integrate a secure wallet into a DAPP. With a simple `npm install portis` and `import & add portis as a Web3 Provider`, Portis automatically hooks into the standard Web3.js method calls that a DAPP already contains. Thus, Portis allows developers to easily and securely connect their users to the Ethereum network.
* [Open Zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity)

  Open Zeppelin is a library for secure smart contract development. It provides tested implementations of standards like `ERC20` and `ERC721` contracts, as well as community-audited Solidity components that DAPP developers can easily integrate into their own contracts and decentralized systems.

  The library is managed by [Zeppelin](https://zeppelin.solutions/), a decentralized core infrastructure and security audit firm, and contracts are audited by the community. The library is considered an accelerant due to it being a reliable component for smart contracts, built upon the core development principles of: security in depth, simple and modular code, clarity-driven naming conventions, comprehensive unit testing, pre-and-post-condition sanity checks, code consistency, and regular audits.
* [0x Protocol](https://0x.org/)

  The 0x Protocol is an open-sourced protocol allowing the peer-to-peer exchange of assets on the Ethereum blockchain. By developing a standard which enables off-chain order relaying (using the blockchain on order-settle rather than every transaction), it speeds up, and reduces the transaction fees involved with processing decentralized crypto asset exchanges. With over $750M in total volume, it is one of the most commonly used protocols when integrating asset exchanges into a DAPP or conventional application.

  The protocol is used by projects like [Radar Relay](https://radarrelay.com/), [Ethfinex](https://www.ethfinex.com/), and [Veil](https://veil.co/).
* [Truffle Framework](https://truffleframework.com/)

  The Truffle Framework is a suite of open-sourced applications including the [Truffle](https://github.com/trufflesuite/truffle) smart-contract development tool, [Ganache](https://github.com/trufflesuite/ganache) personal blockchain for Ethereum development, and [Drizzle](https://github.com/trufflesuite/drizzle) front-end libraries for writing DAPPS.

  The framework allows developers to quickly prototype and deploy decentralized applications. It is considered an accelerant since it reduces the conventional manual overhead of processes including, but not limited to: setting up test blockchains, deploying smart contracts for testing, building testing pipelines, synchronizing contract and transaction data, and more.

* [Infura](https://infura.io/)

  Infura's developer tools and API allow DAPP developers to easily connect to the Ethereum network via RPC. By providing a public Ethereum interface, multi-client backend (for resiliency), and TLS-enabled endpoints, Infura enables simple and secure connections to the blockchain. It takes less than 5 lines of code for DAPP developers to take advantage of Infura's robust network in their applications.
  
  Infura is considered an accelerant since it reduces the manual overhead of setting up Ethereum nodes for RPC endpoints, third party dependency for blockchain information, and the start-up time and cost when interacting with the Ethereum network. It's trusted by projects like [MetaMask](https://metamask.io/), [MyCrypto](https://mycrypto.com/), and [CryptoKitties](https://www.cryptokitties.co/) as their primary RPC provider.
  
# What did we miss?  

Coming to Prague this October? [Join us on the business model ring at ETHMagicians 2018](https://hackmd.io/DaJhrasLQteUk3IwX5bQAg?view#8-Business-Models-Ring)

Remote? [Open an issue and let us know](https://github.com/owocki/web3_revenue_primitives/issues/new), or, even better, [open up a PR](https://github.com/owocki/web3_revenue_primitives/compare).

<!-- Google Analytics -->
<img src='https://ga-beacon.appspot.com/UA-1014419-15/owocki/web3_revenue_primitives' style='width:1px; height:1px;' >
