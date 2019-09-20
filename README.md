
# Bitcoin-Explained-101

What is Bitcoin? Why should you care? What makes it special? How it works? How to invest in Bitcoin? How to get started? 

The purpose of this guide is to introduce to Bitcoin phenomena and other cryptocurrencies in simple terms and easy to digest manner, without skipping the essentials.

> Disclaimer: 
> 
> This guide was written for an average person, who may have little to no technical knowledge needed to grasp the technical aspects of Bitcoin and related blockchain technologies. 
>
> For the sake of keeping this guide accessible for everyone, some of the technical concepts were simplified to make it easier for a non-technical person to grasp the essential information.
>


<br><br>


## Table Of Contents

1. About Bitcoin

- Where it came from?
- How Bitcoin works?
- Bitcoin in numbers
- Bitcoin Forks & other cryptocurrencies

2. Why Bitcoin

- From idea to reality
- Why Bitcoin is growing?
- Can the Bitcoin be stopped?

3. Getting Started with Bitcoin

- Buy Bitcoin with credit card
- Buy Bitcoin on exchange

4. Storing Bitcoin (Safely)

- Bitcoin wallets explained
- Non Custodial Wallets
- Understanding the "Private Key"
- Storing Private Keys Securely
- What if Phone is Lost

5. Transacting with Bitcoin

- How to send Bitcoin?
- How to receive Bitcoin?
- How fast are Bitcoin transactions?
- Bitcoin privacy explained
- Crypto to fiat credit cards

6. Bitcoin Nodes and Mining

- Do I Need to Run a Node
- Different Types of Nodes
- Is It Profitable To Run A Miner Node


## 1. About Bitcoin

Over the last few years Bitcoin got labeled in many different ways, from electronic cash to the digital gold.

While Bitcoin may be defined in many different ways depending on who you ask, it holds certain universal properties which in the eyes of many make Bitcoin "valuable" and consequently regarded as a better alternative to the traditional money like USD or EUR (aka fiat money) or other hard assets such as gold or silver.

The idea of Bitcoin was first proposed by Satoshi Nakamoto (not a real name) back in 2008. Satoshi's paper introducing Bitcoin idea can be found [here](https://bitcoin.org/bitcoin.pdf). The paper puts focus on ability to transact with anyone in a decentralized manner without the need for a 3'rd party intermediary such as central banks in traditional centralized monetary system.

The images below demonstrate the difference between a centralized network (i.e. traditional monetary system) versus the Bitcoin or a similar decentralized network.



<p align="center">
	*Centralized Network*
	<img src="/images/image_banks.png" width="600">
</p>



<p align="center">
	*Decentralized Network*
	<img src="/images/image_blockchains.png" width="600">
</p>


In the original paper, Satoshi Nakamoto proposed a Bitcoin in a form of decentralized network that is:

- not reliant upon any central entity to remain online
- functional 24 hours/day without dependence on any entity
- has equal rules for all network participants
- unconditionally open for anyone to join
- works without geographical borders


> The ideas brought forward in the paper required a fairly comprehensive understanding of the contemporary monetary system and graduate-level knowledge of Mathematics, Cryptography and Computer Science. 
>
> Therefore, Bitcoin should be regarded as a scientific invention that potentially challenges the status quo of present day monetary system and regulatory entities surrounding them.


### How Bitcoin Network Works

Usually, when someone talks about Bitcoin or Bitcoin blockchain the person refers to the Bitcoin network.

The sketch below illustrates the basic structure of Bitcoin network. There are two types of parties participating on the network: wallets and nodes. Some Bitcoin network nodes are also known as miners.

<p align="center"><img src="/images/image_net.png" width="600"></p>

Anyone is able to join the network as a node or as a wallet and start transacting with Bitcoins on equal terms with everyone else.

1. Wallets are generally represented by Bitcoin users which may send and receive payments.

2. Nodes are the entities which validate Bitcoin transactions and keep history of transactions. A node can also act like a wallet at the same time. 

While every network participant is able to send/receive Bitcoin payments, only nodes keep the entity history of transactions from the very first one to the transactions happening in real-time. That entire history of transactions is what is called a Bitcoin blockchain. 

> The word blockchain originates from the fact that new transactions are added to history in batches (i.e. a block of transactions), roughly once every 10 minutes.

Nodes are also tasked with validating every new transaction and ensure that only valid transactions are added to the blockchain. Anyone can setup a node without much effort. The node doesn't require any maintenance and can autonomously operate even on an old computer as long as there is a working Internet connection. 

If one or several nodes try to cheat the network by marking an invalid transaction as valid it would be disregarded by all other nodes on the network. Cumulatively nodes guarantee the openness, availability, decentralization and security of the network. Cheating on such network in practical terms is close impossible.

There are over 9000 Bitcoin nodes powering the network at any given time (source: [https://bitnodes.earn.com](https://bitnodes.earn.com/)). The nodes are spread geographically, covering most of the countries worldwide.

<p align="center"><img src="/images/bitcoin-nodes-global.png"></p>

As mentioned earlier anyone can setup a Bitcoin node at home and act as a guardian of the Bitcoin network. It will be covered in detail later in this guide.


### Bitcoin in Numbers

There will be 21 million Bitcoins in total with over 17 million Bitcoins have been already released to the market. The remaining part will be automatically created by the Bitcoin network over the course of 130 years in a manner described below.

> A single Bitcoin consists of 100 million (100,000,000) units called Satoshi.

The Bitcoin network designed in a way where a certain number of Bitcoins are added to the network roughly every 10 minutes. Those newly created Bitcoins are given away "randomly" to one of the nodes on the Bitcoin network. The award goes to the node that is the first to successfully solve a mathematical problem. While all nodes are trying to solve it only the very first one gets the prize. The process of solving this mathematical problem is called mining.

> Note: The release of new Bitcoins to the circulation is not something that's controlled by some entity. It's a fully automated process and is regulated autonomously by algorithms that were coded into Bitcoin at the very start, back in 2009.

Once the total Bitcoin count reaches 21 million no new Bitcoins will be awarded to the winning node.

In conclusion:

- 21 million: total number of Bitcoins that can exist
- over 17.8 million have already been created by network since 2008
- the remaining 3.2 million will be created over the next 130 years


It's worth noting that it's estimated that about 4 million Bitcoins have been already lost (source: [fortune.com](https://fortune.com/2017/11/25/lost-bitcoins/)). Taking that into account, it can be concluded that out of 17.8 million Bitcoins only about 14 millions are available on the market at this point. 

<p align="center"><img src="/images/bitcoins_circulation.png"></p>

More Reading:

- [How Many Bitcoins Are There?](https://www.buybitcoinworldwide.com/how-many-bitcoins-are-there/)
- [Nearly 4 Million Bitcoins Lost Forever, New Study Says](https://fortune.com/2017/11/25/lost-bitcoins/)
- [The 21 million Bitcoin story explained: Why is the number special?](https://coinsavage.com/content/2018/11/the-21-million-bitcoin-story-explained-why-is-the-number-special/)
- [How Many Bitcoins Are Lost vs How Many Are Hodled](https://www.reddit.com/r/BitcoinBeginners/comments/d2g8z3/how_many_bitcoins_are_lost_vs_how_many_are_hodled/)


### Bitcoin Forks and Other Cryptocurrencies

When trying to understand the Bitcoin for the first time a lot of people are usually left confused and frustrated. Before gaining any concrete understanding of what Bitcoin is, newcomers discover a large number of cryptocurrencies with many portraying itself as a better alternative to Bitcoin. 

Moreover, some of these cryptocurrencies have the word "Bitcoin" in its name adding to further confusion. All these aspects make the onboarding experience for the new users extremely difficult. 

<p align="center"><img src="/images/bitcoin-and-forks.png"></p>

The essential points can be summarized as:

- Bitcoin: In addition to Bitcoin itself, there are a number of other cryptocurrencies with Bitcoin in the name. The one that's considered the original Bitcoin is the one with the symbol BTC. It's generally referred to as *Bitcoin* and less often as the *Bitcoin Core*.

- Bitcoin forks: Cryptocurrencies which were derived from the original Bitcoin (BTC). Due to the open source nature of Bitcoin and underlying code anyone with programming experience is able to create a Bitcoin like cryptocurrency with some modifications and market it as a separate cryptocurrency. The most noteworthy such cryptocurrency is [Bitcoin Cash](https://en.wikipedia.org/wiki/Bitcoin_Cash).

- Altcoins: Usually the term refers to all other cryptocurrencies that are around. While there are thousands of them around only few managed to attract the audience and gain some crypto market share. The altcoins which have not attracted any audience are generally regarded as coins with no value proposition and are labeled as "shitcoins".

For the comprehensive list as well as current market prices of cryptocurrencies check out [CoinMarketCap.com](https://coinmarketcap.com).

<p align="center"><img src="/images/coinmarketcap.png"></p>


## 2. Why Bitcoin

Bitcoin started as an idea, which was initially worthless because only a handful of people knew about it. In its early days, general public mostly perceived Bitcoin as a "fun money for geeks" rather than a phenomena that can potentially challenge present-day financial system. Only few understood the true purpose of Bitcoin. Although a lot more more people understand that now, the number of such people is still relatively low. 

Mainstream media have played a strong role in shaping how the masses perceive Bitcoin. Nearly all early mainstream media [mentions of Bitcoin](https://www.ccn.com/bitcoin-mainstream-media/) have been negative. It was declared dead [about 400 times](https://99bitcoins.com/bitcoin-obituaries/) by now.

Back in early days, the idea that someday Bitcoin would be worth over $10,000 appeared somewhat unbelievable...  With [some](https://bitcointalk.org/index.php?topic=137.msg1195#msg1195) spending 10,000 BTC (over 100,000,000 USD today) to buy pizza :)

Fast forward to August 2019, Bitcoin have been mostly trading over the $11,000 mark and seems to have consolidated above the $10,000 at this point.

> Regardless of the current price, the biggest challenge for the Bitcoin was to grow from 0$ to 100$ and that first happened sometime in 2013 (nearly 5 years after it emerged)... As time gone buy, it grew higher and higher. It broke $1,000 next year in 2014 though retreated quickly, and even reached nearly $20,000 in the end of 2018. But the hardest point was to break away from 0$ mark and raise above the 100$.

Understandably Bitcoin was and still is extremely volatile. The volatility is primarily due to low number of people willing to buy/sell the Bitcoin at any given time. Today Bitcoin has a 200 billion market cap it's still fairly common to see a daily price change of 5%. The market cap of Bitcoin should reach a couple of trillions before public hype/panic/traders would be unable to affect the price significantly.

More Reading: 

- [A Dazzling History of Bitcoin Ups and Downs](https://cointelegraph.com/news/a-dazzling-history-of-bitcoins-ups-and-downs)
- [What Causes Volatility In Bitcoin?](https://www.fxcm.com/uk/insights/what-causes-volatility-in-bitcoin/  )
- [Why Bitcoin Has a Volatile Value ](https://www.investopedia.com/articles/investing/052014/why-bitcoins-value-so-volatile.asp)
- [The Bitcoin Volatility Index](https://bitvol.info  )

Bitcoin today is very different from what it was 10 years ago. While the mainstream media still plays a huge role in how people perceive the Bitcoin, they seem to be loosing the battle as the price seem to be going up... 

These days, nearly all mainstream financial channels regularly talk about Bitcoin. And not just media, the kings of the financial world as well as the world leaders are all taking notice.

- [Fed Chair Jerome Powell on Bitcoin as a Store of Value](https://www.youtube.com/watch?v=jBUlXryF2WI)
- [President Trump on Bitcoin](https://twitter.com/realdonaldtrump/status/1149472282584072192)
- [Jack Dorsey, CEO of Twitter](https://www.cnbc.com/video/2019/03/06/jack-dorsey-spends-10k-a-week-on-bitcoin-predicts-a-massive-bitcoin-boom.html)
- [Ron Paul Pledges Allegiance to Bitcoin, Calls Crypto a Great Idea](https://www.ccn.com/ron-paul-pledges-allegiance-to-bitcoin-calls-crypto-a-great-idea/)
- [Brian Armstrong, CEO of Coinbase](https://twitter.com/brian_armstrong/status/1162185049699057664)
- [14 Bitcoin Quotes by Famous People](https://medium.com/@MartinRosulek/14-bitcoin-quotes-by-famous-people-6e7a1a009281)

It's no longer perceived as "fun money for geeks" but more often as a "valuable financial asset" that's not tied to any state or corporation. The current Bitcoin price as well as the current market capitalization is an indication of that.


### Why Bitcoin Keeps Growing?

To understand what drives Bitcoin price higher and further adoption it's important to look at Bitcoin as a social cause. A cause that seeks to provide a solution to some major socio-economic and geopolitical problems rather than merely a new asset class or even an alternative to gold or fiat money.

> Bitcoin is not an improvement to how we transact and preserve wealth. 
> It's a whole new way to own and exercise control over the wealth. 

Unlike traditional assets and financial instruments which are generally enforced by governments or some other centralized organizations, the core driving force of the Bitcoin is a global community. These people are driven by liberating ideas and share a strong passion to convey these ideas to the world.


Some of the main principles at the core of these ideas are:

- Financial system must be decentralized and temper-proof

- Financial network must be unconditionally open for all

- Participants must have unconditional control over assets

- The underlying value transfer asset should be scarce


In face of modern-day problems such as excessive money printing, politically-motivated sanctioning, for-profit wars, centralized financial system etc. a growing number of people are gradually moving towards Bitcoin. 

- [Coinbase Custody Seeing $200-400 million in Crypto Deposits Weekly](https://www.reddit.com/r/Bitcoin/comments/cqzxtb/coinbase_custody_seeing_200400_million_in_crypto/ )
- [Billionaires are 'Scouring the Market' to Own 25% of Bitcoin in Circulation](https://www.ccn.com/billionaires-are-scouring-the-market-to-own-25-of-bitcoin-in-circulation/)
- [Bitcoin Stats: Rich List & Distribution](https://btc.com/stats/rich-list)
- [Russia plans to tackle US sanctions with Bitcoin investment, says Kremlin economist](https://www.telegraph.co.uk/technology/2019/01/14/russia-plans-tackle-us-sanctions-bitcoin-investment-says-kremlin/)
- [Venezuela Smashes Weekly Bitcoin Trading Record With 114B Bolivars](https://cointelegraph.com/news/venezuela-smashes-weekly-bitcoin-trading-record-with-114b-bolivars)


The growing trend for Bitcoin is likely to continue. Those that understand this are trying to accumulate the Bitcoin reserves now.


### Can The Bitcoin Be Stopped?

A lot of new people entering Bitcoin ecosystem remain somewhat skeptical about its ability to succeed. The narrative that one day a Bitcoin or alike decentralized system may replace centrally regulated financial institutions seems unbelievable. Especially when the core beneficiaries of the current status quo are some of the most powerful entities.

An outlook that at some point governments are going to try banning the Bitcoin generally regarded as more likely scenario, especially by those unaware about how Bitcoin operates on a technical level.

So, the real question is can the government or some other organization(s) stop the Bitcoin? The answer is NO. 

Should any government try to outlaw Bitcoin enforcing such ban would be practically impossible. As long as there is electricity powering your computers, phones and other smart devices the Bitcoin network can exist and flourish. It can surely be made more difficult for people to participate in the network but that's pretty much it.

Taking down the Bitcoin network is even more difficult then taking down the entire Internet. While modern day governments/regulators are able to effectively censor what is being seen on search engines, YouTube or mainstream media, censoring people from being able to participate in Bitcoin network is a whole new level.

- [Rep. Patrick McHenry: 'There's no capacity to kill Bitcoin'](https://www.youtube.com/watch?v=xolYGw2wU6Y)
- [U.S. Lawmakers Are Realizing They Can’t Ban Bitcoin](https://www.forbes.com/sites/ktorpey/2019/07/30/us-lawmakers-are-realizing-they-cant-ban-bitcoin/)
- [Unstoppable Code: The Difference Between Can't and Won't](https://www.youtube.com/watch?v=Q6euy5W1js4&app=desktop)
- [Blockstream Satellite: Broadcasting Bitcoin from Space](https://bitcoinmagazine.com/articles/blockstream-satellite-broadcasting-bitcoin-space)

The only way for the Bitcoin network to stop having any meaningful value is for everyone to stop using it. Such an outcome may occur only if someone discovered an unrepairable fundamental flaw in the code powering the network. Other than that any measure to outlaw the Bitcoin would lack the substance needed to enforce it. 


## 3. Buying Bitcoin

If you made until this point you should already have a general idea of what Bitcoin phenomena is. The next step for us is to introduce you to buying Bitcoin so that you can actually own some.

<p align="center"><img src="/images/buy-bitcoin-online.png"></p>

At [current](https://www.coinbase.com/price/bitcoin) prices, buying even just one Bitcoin would set you back as much as $10,000 or even more. The good news, you don't have to spend $10,000 to get started. Start small and buy only $50 or $100 worth of Bitcoin at first. Later once you're comfortable with all aspects of owning Bitcoin you may buy more and increase your holdings over time.  

> Disclaimer: 
> 
> Regardless of what anyone says about Bitcoin and its future potential, you should understand that there are no guarantees that the price of Bitcoin will grow higher and meet your expectations. A lot of people believe in this new technology and hope it will get its place on world stage BUT no one knows how the Bitcoin going to evolve. 
>
> Therefore, use your own judgment when contemplating investing in Bitcoin and keep in mind that it may just go down in price and never recover from there. Future is unpredictable and hence don't spend on it more than you can afford to loose.

There are two main ways for a newcomer to acquire Bitcoin. You can either find someone willing to send you some or you may purchase some amount of Bitcoins online.


### Buying Bitcoin with Credit Card

The easies option ios to buy with the credit card.

There are plenty of places online where it's possible to buy Bitcoin using Visa or MasterCard. While this option is convenient bear in mind that you will be purchasing the crypto at slightly elevated prices (approx. 1%) than market rates which is not really an issue for smaller amounts.

> Note: There are a lot of places that advertise buying Bitcoin. Keep in mind that many of those options are not safe. For your safety use only resources recommended below or that you have thoroughly researched yourself.

Below you will a list of popular places that have already served thousands of people looking to purchase Bitcoin and other cryptocurrencies using credit cards. While for EU or US residents any of the options below should work without issues for people coming from less developed nations there will be fewer options to choose from. That said, regardless of where you coming from at least one of the options below should work for you.

- https://cex.io/cards/
- https://payments.changelly.com/
- https://www.coinbase.com/
- https://www.coinmama.com/bitcoin
- https://www.binance.com/en/creditcard
- https://buy.bitcoin.com
- https://indacoin.com
- https://www.bitpanda.com/en/prices/bitcoin

If you're looking to buy more than a couple of thousands worth of Bitcoins and on a regular basis than you should be buying on some cryptocurrency exchange at market prices.


### Buying Bitcoin on Exchange

Cryptocurrency exchanges are websites where you can buy/sell cryptocurrencies for USD/EUR or trade one cryptocurrency for another. If you're looking to invest substantial amount of money then buying on cryptocurrency exchange is the the only safe option. That may sound a bit complicated for someone who never traded stocks or currencies but it's not difficult at all. 

When it comes to trading terms and requirements, most exchanges are same as all of them have to abide by financial regulations and therefore have certain rules and limits in place. 

The steps of purchasing the Bitcoins on Exchange is generally as follows:

1. setup an account
2. verify account identity (passport scan etc)
3. fund exchange account (via credit card or bank transfer)
4. purchase Bitcoin on exchange
5. transfer purchased Bitcoin to your wallet for safekeeping


> Note: While basic documents (i.e. driver's license) would work for accounts with a monthly turnover in the range of $5,000, once you go beyond that expect to go through a more robust inspection known as [KYC/AML checks](https://www.quora.com/What-is-a-difference-between-KYC-and-AML). In addition to identity checks you will be asked to provide documents proving the origin of your funds. Keep in mind, should you fail to do that your funds/account may get frozen.

Listed below are some of the better known cryptocurrency exchanges: 

- [Coinbase.com](https://www.coinbase.com/)
- [CEX.io](https://cex.io)
- [Binance.com](https://binance.com)
- [ShapeShift.com](https://shapeshift.com)
- [eToro.com](https://www.etoro.com)
- [CoinMama.com](https://www.coinmama.com)
- [Changelly.com](https://changelly.com) 


## 4. Storing Bitcoin Safely

Bitcoins are generally stored in cryptocurrency wallets which come in many different forms and types. A wallet can come in a form of a mobile app, a desktop program, a website or even a small hardware gadget.

### Bitcoin Wallets Explained

Regardless of the wallet type and what's being said on the wallet website there is just **one crucial point** you should understand. That is whether the wallet lets you (the owner of funds) exclusively control the cryptocurrency held on that wallet, or not. That is the main security criteria you should look for when choosing a wallet for your Bitcoins.

Taking the ownership aspect into account cryptocurrency wallets can be categorized as:

1. Non-Custodial Wallets that give user exclusive and unlimited control over user's crypto funds. The company providing the wallet does not have any control over the assets user holds. The wallet user is the only one with access to control the funds. Generally, these type of wallets also enable users to easily switch between wallets made by different parties without issues. These are preferred type of wallets.

2. Custodial Wallets that don't give user exclusive control over the funds. The wallet provider may potentially block user from spending the wallet funds. Moreover, it's not uncommon for such wallet providers to get hacked and have users' funds stolen as a result. Unfortunately, most of the wallets out there fall in that category. Avoid such wallets whenever possible.

3. Then there are Hybrid wallets where neither a wallet user nor the wallet provider has full control over the funds. These wallets are programmed to require approval from both parties for both the owner and the wallet provider. This works well against hacking attempts but still keeps the door open for the wallet provider to censor the user.

<p align="center"><img src="/images/custodial-non-custodial.png"></p>

> Note: Non-Custodial wallets are generally considered safer and preferred over the Custodial or hybrid wallet types because they provide users with exclusive control over cryptocurrencies held on that wallet.

A lot of people prefer keeping the purchased Bitcoins on the Crypto exchange itself. For the most part, crypto exchanges like Binance, Coinbase, CEX.io etc provide users with Custodial type wallets. Many mistakenly assume that keeping them on exchanges is safe while it's not. Just like wallet providers, exchanges are often targeted by hackers. And when exchanges are hacked users usually loose their funds and not compensated.

- [The Largest Cryptocurrency Hacks So Far This Year](https://www.investopedia.com/news/largest-cryptocurrency-hacks-so-far-year/)
- [Coincheck: the Biggest Crypto Exchange Hack of All Time](https://coin360.com/blog/top-7-crypto-exchange-hacks)
- [A Timeline of Major Crypto-exchange Hacks](https://discover.ledger.com/hackstimeline/)
- [Hack Flashback: The Mt.Gox Hack](https://www.ledger.com/hack-flasback-the-mt-gox-hack-the-most-iconic-exchange-hack/)
- [Crypto Developer Komodo ‘Hacks’ Wallet Users to Foil $13 Million Theft](https://www.coindesk.com/crypto-developer-komodo-hacks-wallet-users-to-foil-13-million-hack)
- [9 Ways to Hack Your Bitcoin Wallet](https://www.wipersoft.com/9-ways-to-hack-your-bitcoin-wallet/)
- [Cryptocurrency customers are unable to access their coins after Canadian CEO’s death](https://www.cnbc.com/2019/02/05/millions-in-cryptocurrencies-frozen-after-quadriga-founders-death.html)

If you keep Bitcoins on exchange, it means the exchange keeps them for you on their account. The exchange gives you username and password so that you can send instructions to withdraw/deposit Bitcoins or other crypto currencies. The exchange may freeze funds or restrict access to your account for whatever reason. You kind of have to trust them not to be evil :)


### Understanding the "Private Key"

The notion of Private Key is relevant to Non-Custodial wallets. 

With Bitcoin, wallets are not required to provide users with usual account/password authentication methods. Instead of traditional accounts, privacy-focused wallets generate secure cryptographic keys usually referred as the Private Key. These private keys essentially become the way to access and exercise control over the funds.

The entity which has access to that Private Key has full access to funds on the wallet and can be considered the owner of that wallet. The Private Key is randomly generated by the wallet itself.

>- Custodial wallets do not provide user with Private Key. The wallet operator has full control over the assets.
>
>- Non-Custodial wallets provide the Private Key. It puts full control over the funds in hands of the wallet user.

The Private Key usually shown to user in a form of 12 or more plain English words. Those 12 plain words is just a ”human readable” representation of the “Private Key”. Sometimes it can be more than 12 words.


<p align="center"><img src="/images/sample-private-key.png" width="330"></p>

*Image above shows a sample private key from [Unstoppable Bitcoin wallet](https://unstoppable.money). The wallet associated with that key does not have any funds on it. If it had any funds on it then anyone reading this could import/restore that key on some wallet app, access the wallet and transfer the funds elsewhere :)*

Safely storing Private Key is extremely important and all wallets that provide you with one will tell you about that.

Nearly all Non-Custodial wallets provide Import (or Restore) wallet feature which enables anyone to enter existing Private Key (that was previously generated in that wallet app) and restore access to the wallet funds as well as past transactions. Some wallet apps allow you to import/restore keys that were generated in other wallets as well but for the sake of keeping things simple we won't go into that here.

<p align="center"><img src="/images/restore-private-key.jpeg" width="330"></p>

Let's say you transferred some Bitcoins to your new wallet app. Even if your phone breaks or the wallet app stops working your funds are still safe because you will always be able to restore access to your Bitcoins using the Private Key the wallet has generated for you. It can be even years later, in the same app or some other wallet app.

Treat the Private Key the wallet app gives you with great care. If someone ever sees it, your funds are in danger because that person can potentially download same or some other compatible wallet app and restore access to your wallet funds using that key. 

> Note: The risk here is that you may loose the key or unknowingly expose it to someone who can then reenter that key in some other wallet and get control of your Bitcoins. That’s the only thing you should really understand. The rest is secondary.


### Storing the "Private Key"

- Option 1: Write Private Keys on the paper and store it somewhere safe offline. 
- Option 2 (Mac OSX users): [Store Private Keys in Keychain's Secure Notes](https://support.apple.com/guide/keychain-access/what-is-keychain-access-kyca1083/mac)
- Option 3 (Windows users): [How to Encrypt and Protect Your Data and Files Using VeraCrypt](https://www.makeuseof.com/tag/encrypt-data-files-veracrypt/)


### Recommended Non-Custodial Wallets

Below are some of my favorite Non-Custodial type wallets. Most of the screenshots shown in this guide were taken on Unstoppable wallet that's listed below as well.

Wallet Apps:

- Unstoppable Wallet (https://unstoppable.money)
- BRD Wallet (https://brd.com)

Hardware Wallets:

- Ledger (https://www.ledger.com)
- Trezor (https://trezor.io)

Strong Focus on Privacy:

- Samourai (https://samouraiwallet.com)
- Wasabi (https://wasabiwallet.io/)



### What Happens If You Lose Phone

Let's say you lost your phone and someone finds it... The question you may have is whether your wallet funds are in danger.

Both Google's Android and Apple's iOS operating systems provide security mechanisms to keep sensitive data safe in case of a phone loss. A good wallet app would usually have you covered in that regard by storing wallet Private Keys as per safe storage guidelines recommended by Google or Apple. 

There were a number of incidents in the past where authorities tried to unlock the Pin locked phones. It's a challenging task...

- [FBI–Apple Encryption Dispute](https://en.wikipedia.org/wiki/FBI%E2%80%93Apple_encryption_dispute)
- [Tim Cook: Americans Shouldn't Have to Choose Between Privacy and Security](https://money.cnn.com/2015/12/20/technology/apple-tim-cook-60-minutes/index.html?iid=EL)
- [A Year After San Bernardino And Apple-FBI, Where Are We On Encryption?](https://www.npr.org/sections/alltechconsidered/2016/12/03/504130977/a-year-after-san-bernardino-and-apple-fbi-where-are-we-on-encryption)

Long story short, if the phone doesn't have the Pin Lock in place, the person who finds your phone may potentially access (hack into) the apps on the phone incl. the wallet app itself. If successful, the thief may then steal your Bitcoins by sending them to another wallet. On the other hand, if the phone has OS Pin Lock in place it is extremely difficult to hack into it. Private Keys become unreachable.

>Note: The Pin Lock on an Operating System level is a safety requirement to ensure that sensitive data remain safe when an unauthorized party gets hold of the phone. Most of the good wallet apps will not work if the phone's Operating System doesn't have the Pin Lock in place. 

Some of the better wallet apps out there would refuse to work if the phone does not have the Pin Lock enabled. 

<p align="center"><img src="/images/pin-lock2.png" width="330"></p>

So, in case of a device loss, the person may get a new phone and restore the wallet funds with the help of the safely stored Private Key. After the access to the wallet is restored, it still recommended to transfer the funds to a new wallet.


## 5. Transacting with Bitcoin

So now that you understand the importance of the Private Keys, let us quickly go through the process of sending/receiving Bitcoin. Nearly every cryptocurrency wallet comes with a standard Send and Receive features.

- Send : for sending Bitcoins to others
- Receive : for receiving Bitcoins from others


### How to Receive Bitcoin?

To receive Bitcoins from someone or to transfer them from one of your own accounts (i.e. account on exchange) to your wallet account, you only need your Bitcoin address. That address usually located in receive section of the wallet app. The screenshot below shows the 'Receive' screen from Unstoppable wallet app.

<p align="center"><img src="/images/receive-bitcoin.png" width="330"></p>

Copy that address and send it to the entity that wants to send you Bitcoin.

It should be noted, that most Non-Custodial wallets will provide you a new receive address for each transaction. This is a recommended privacy feature enabled in any well designed wallet aimed to keep your transactions history somewhat anonymous (will be explained below).

Although, the wallet will generate a new receive address after each incoming Bitcoin transaction, older addresses will still remain functional and appear in your wallet whenever someone sends funds to you. In practice, this means that you may generate an unlimited amount of addresses where people can send you Bitcoins and all of them will reach you.


**How to Send Bitcoin?**

To send someone Bitcoin you simply need to ask the recipient for his/her Bitcoin address and then use the Send feature in your wallet app to send the desired amount to the provided address.

<p align="center"><img src="/images/send-bitcoin.png" width="330"></p>

When sending a transaction the sender expected to add a small transaction fee which would be awarded to the nodes which adds the transaction to the blockchain. 

Once the user clicks on Send button, the there is a brief period while the transaction remains in queue (mempool). Some wallet apps allow the user to potentially change the transaction for a brief moment while it is in that queue (i.e. in pending state).

> Note: Bitcoin transactions are final. Once the Bitcoins are sent to the destination address and included in the block it can be assumed that this transaction is final. Only the owner of the destination Bitcoin address can then send/spend those Bitcoins.


### How Fast Are Bitcoin transactions?

In this section, we'll look into what happens to transaction after the user clicks on Send button from the wallet. 

Every Bitcoin transaction goes through following stages:

PENDING PHASE: Sending transaction

1. User clicks on Send button in the wallet app
2. Transaction ALMOST instantly reaches most of the nodes on the Bitcoin network
3. Each nodes places the transaction in queue, so called "mempool". 
 
This phase should be nearly instant in most wallets. At the end of this phase most network nodes already have the transaction in the queue but not it in the blockchain (global history of transactions) yet. 

When the transaction is sent the recipient will see it as pending in his/her local transactions list within a couple seconds. While it remains pending it's still potentially possible for the sender to modify/cancel the transaction.


CONFIRMATION PHASE: Transaction waiting to be included in blockchain

4. Transaction added to the blockchain and becomes confirmed. That usually happens within 10 minutes but can take loner as well. There are two factors which can affect the amount of time for the transaction to be confirmed:

- the transaction fee set by the sender
- the current amount of pending transactions in the network

When the number of transactions in the network exceeds the amount of transactions nodes can process, nodes get to choose which transactions to include first. In general, nodes prefer to give priority to transactions which pay higher fee because the nodes get to keep the fee. Most good wallet apps would take the current network conditions into account and would recommend the optimal fee to the sender on the Sent screen itself.

<p align="center"><img src="/images/transaction-fee.jpg" width="330">

If the fee was sufficient then it will most likely be confirmed within 10 minutes. That's why setting the fee properly is important, especially for larger payments that need to happen quickly.


FINAL PHASE: Waiting for 3-6 blocks to pass

After the transaction is included in the block it's fairly safe to assume that it's final and completed. However due to the nature how Bitcoin network operates it's generally recommended to wait somewhere between 3-6 blocks to pass before the transaction can be considered final and irreversible.

> Note: It's safe to assume that transaction is final once it was included in a block. As soon as transaction is included in the block it's considered to have had "1 confirmation". When the blockchain adds another block on top of it, it's assumed to have received "2 confirmations" and so on.

Most wallets will show the transaction as final after 3/6 blocks has passed. For some wallets even 1 confirmation is enough for transaction to be shown as final.

Anyone can monitor the status of any transaction from the moment it was sent using a number of public block explorer sites. In practice this means that as soon as you the user hit the Sent button the receiving party can already monitor this transaction online and see how it's progressing. In order to do that the receiver needs only an ID of the transaction which can be obtained from the wallet itself.

Below, you will find some of the popular public transaction explorers for Bitcoin network:

- [Blockchain.com/explorer](https://www.blockchain.com/explorer)
- [BTC.com](https://btc.com/)
- [BlockChair.com](https://blockchair.com/)


### Bitcoin Privacy Explained

When it comes to privacy in Bitcoin it's somewhat semi-private. While all transactions in Bitcoin network are public they simply appear as transaction from some Bitcoin address to another.

The image below shows a screenshot of a transaction (ID: [https://btc.com/75e728201f3c35346542f5671ebefa958191aa64b0567aad46d2a7360b626280](https://btc.com/75e728201f3c35346542f5671ebefa958191aa64b0567aad46d2a7360b626280)) from a public BTC.com block explorer.

<p align="center"><img src="/images/block-explorer.png"></p>

As you can see from the image above just by looking at individual transaction there is no way to know who the sender or recipient is. It might even be that both the sender and recipient is the same person. 

That said, by clicking on the sender address it's possible to see when and what address the sender received these funds from. Now, if the wallet user always uses the same address for incoming transactions, it would be easy to see all incoming transactions to that address and from that get a fairly comprehensive transaction history. 

On the other hand, if the wallet user uses a new address for each new transaction then identifying that user's incoming transactions becomes close to impossible.

In addition to using new addresses for each transaction, a general rule of thumb here is to make sure that only the people you want to know are aware of how much Bitcoin you have, how/where you store it etc.

> Note: While the information above give some basics in regards to how Bitcoin privacy works, keep in mind that it's by no means a complete picture when it comes to the privacy aspects to the Bitcoin. 

For an advanced user with large amount of Bitcoins or for someone living in hostile environments there are several other factors that should be taken into account when it comes to transacting with Bitcoins. This subject alone warrants a brief guide on its own.

- [A non-technical Guide to Privacy in Bitcoin](http://bitcoinsnippets.com/protect-your-bitcoin-through-privacy/)


### Using Bitcoin for Purchases

Ability to pay with the Bitcoin in offline transactions is still something very uncommon. While [some merchants](https://www.forbes.com/sites/michaeldelcastillo/2019/05/13/starbucks-nordstrom-and-whole-foods-now-accept-bitcoin-just-dont-ask-them/#41074bb12252) like [Whole Foods](https://fortune.com/2019/05/13/bitcoin-comes-to-whole-foods-major-retailers-in-coup-for-digital-currency/) are slowly starting to accept payments in Bitcoin, the vast majority of retailers worldwide are still in waiting phase. There are many reasons for that, ranging from lack of legal guidelines for merchants in others its the fundamental issues relevant to the technical architecture of the Bitcoin blockchain itself which won't be discussed here.

That said, there are already some effective ways to spend your cryptocurrency pretty much everywhere. A number of companies provide branded debit cards which can be used to pay for things anywhere where the Visa or MasterCard is accepted. You pay with a card as you would normally do and the amount is deducted from your crypto wallet balance per current market rates.

<p align="center"><img src="/images/crypto-cards.jpg">

Below, you will listed some of the more popular providers of such cards. Most are available only to people residing in US or Europe and all of them require the user to provide some identification documents.

- [Crypterium.com](https://cards.crypterium.com)
- [Crypto.com](https://crypto.com/en/cards.html)
- [Coinbase.com](https://www.coinbase.com/card)
- [Nexo.io](https://nexo.io/nexo-card)
- [2gether.global](https://www.2gether.global)
- [Cash.app](https://cash.app)
- [Cryptopay.me](https://cryptopay.me/bitcoin-debit-card)

When using the services above the card provider will provide you with the wallet app as well. This will be a Custodial wallet tied and therefore you should never keep too much funds on it. 

Use a Non-Custodial wallet for your primary funds and occasionally top up the wallet provided by card provider with some amount. Think of it like a debit card balance that can be spent.


## 6. Bitcoin Nodes and Mining

As mentioned earlier, currently there are over 9000 nodes powering the Bitcoin network. The nodes are spread geographically, covering most of the regions worldwide.

Anyone can setup a node without much effort. The node doesn't require any maintenance and can autonomously operate even on an old computer as long as there is a working Internet connection.


### Do I Need to Run A Node

As briefly mentioned above, nodes are tasked with validating every new transaction and broadcasting transactions it receives to other nodes in the network. If one of the nodes tries to cheat the network by marking an invalid transaction as valid it would be disregarded by other nodes. 

Cheating on such network in practical terms is close impossible. Cumulatively nodes guarantee decentralization, availability and security of the network.

- decentralization: By allowing participants to communicate with the network using any desired node (even their own).

- availability: As long as at least one node is online the Bitcoin network will remain operational.

- security: The more nodes there are on the network the harder it's for an entity to cheat as every single node would be working against it.

So, if you're contemplating to run a Bitcoin node, know that by running a node you're effectively contributing to the Bitcoin network. 

Also, keep in mind that there are [some countries](https://en.wikipedia.org/wiki/Legality_of_bitcoin_by_country_or_territory) where Bitcoin currently is considered illegal. So, make sure you're aware of the potential risks.


### Different Types Of Nodes

While all nodes on Bitcoin Network are equal, some nodes may do more things than others. Below, we'll look at some of them.

All nodes are asked with validating and propagating new transactions and blocks. 

- Some nodes, known as full nodes, keep a complete copy of the blockchain (history of transactions). Any such full node can independently verify any transaction for validity.

- There are also nodes known as "miners" which constantly compete between each other. All nodes compete in order to be the node that gets to add the next block (of new transactions) to the blockchain (history of transactions). The miner node that is the first to solve a mathematical problem is the one that wins the competition.

A node can be both a miner and a full node.

As mentioned earlier, the Bitcoin network designed in a way where a certain number of Bitcoins are released roughly every 10 minutes. This happens at the moment when a new block of transactions added to the blockchain. The node that adds the new block to the blockchain gets to keep these newly released Bitcoins. As a result, every node is motivated to become the one that gets to add the block in order to receive that reward. Currently, that reward is 12.5 Bitcoins (reduced by half every couple of years). Moreover, that node also receives all individual transaction fees from that block of newly added transactions. 

In summary:

1. Roughly every 10 minutes blockchain gets a new block of confirmed transactions. These transactions are taken from queue of pending transactions. 
2. While every miner node tries to be the one that gets to add the block, only one succeeds.
3. The winning miner gets rewarded for that by keeping all transaction fees from that block as well as the newly released Bitcoins.


### Is It Profitable To Run A Miner Node

If you're contemplating to run a miner node for the sake of making some money keep in mind that it's extremely difficult these days due to the large competition. 

Taking into account electricity prices in the world you're more likely to loose money as a result. At present day, mining is profitable only for people running large number of specialized computers who are buying electricity at industrial rates in countries like China.

Other than that running a miner node is not cost effective


## Conclusion

That's about it! Now you know pretty much everything that's important when it comes to owning and transacting with Bitcoin. 

Thanks for reading :) Do humanity a favor and share this guide with people you know!

This guide didn't cover of the technical aspects powering the Bitcoin protocol (code). Those who are interested in this should checkout an excellent [Mastering Bitcoin](https://www.oreilly.com/library/view/mastering-bitcoin/9781491902639/) guide from Andreas M. Antonopoulos, one of the world’s foremost Bitcoin and open blockchain experts.

Peace!

