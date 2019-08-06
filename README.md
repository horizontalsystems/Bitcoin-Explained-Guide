# Bitcoin-Explained-101
What is Bitcoin? How it works? How to get started? Everything you should know in simple terms.

## Table Of Contents

1. About Bitcoin

-- What is Bitcoin?
-- How many Bitcoins are out there?
-- How Bitcoin network works?


2. Why Bitcoin

- Why Bitcoin is growing?
- What Problems it tries to solve?
- Is it legal to use Bitcoin?


3. Getting started with Bitcoin

- How to acquire Bitcoin?
- Bitcoin exchanges


4. Storing Bitcoin (Safely)

- Bitcoin wallets explained
- What you should know to keep your Bitcoins secure?


5. Send / Receive Bitcoin

- How to send Bitcoin?
- How to receive Bitcoin?
- Are Bitcoin transactions anonymous?
- Bitcoin transaction fees explained
- How long the transaction takes place?
- Is it possible to cancel bitcoin transaction?


6. Bitcoin Nodes and Mining

- What is Bitcoin mining?
- Why mining is important?
- How to become a bitcoin miner  ?


<br><br><br>

## 1. About Bitcoin

### What is Bitcoin?

### How many Bitcoins are out there?

### How Bitcoin network works?

## 2. Why Bitcoin

### Why Bitcoin is growing?

### What Problems it tries to solve?

### Is it legal to use Bitcoin?

## 3. Getting started with Bitcoin

### How to acquire Bitcoin?

### Bitcoin exchanges


## 4. Storing Bitcoin (Safely)

### Bitcoin wallets explained

Bitcoins stored in Bitcoin wallets. When someone says they own X amount of bitcoins they don't have actual bitcoins on their Bitcoin wallet. What they actually have is the key (a random collection of letters that's impossible to guess, even for the most powerful computer). Only the person who knows that key (often called SECRET KEY or PRIVATE KEY) can send those Bitcoins, or in other words spend/transfer them to someone else.

When it comes to Bitcoin wallets, people usually get to choose between two following options

Wallets that do not let you control your SECRET KEY.

These come in many forms but in general what you get is username and password so that you can send them instructions like withdrawing/depositing bitcoins. In Bitcoin community these are considered insecure.

The risk here is for wallet to be hacked or for the wallet operators to scam everyone by telling that they were hacked. They also can freeze/restrict your wallet for whatever reason. All of the risks mentioned are fairly common. More common than you may think :)

A LOT of Bitcoins were and being stollen this way. This months alone around 40 million worth of bitcoins were gone from one such wallet provider.

Wallets that give you (and only) full control of your SECRET KEY

In that case you're the only one with access. No one but you (as owner of the key) can transfer Bitcoins under the control of that SECRET KEY.

The risk here is that you may loose the key or expose it to someone who can then reenter that key in some other wallet and get control of your Bitcoins. So, while this option is secure it requires a basic understanding of security which I hopefully managed to explain above. You just need to ensure they Secret Key for the wallet is kept somewhere safe.

If you keep bitcoins on exchange:

 - It means the exchange keeps them for you on their account. They give you username and password so that you can send them instructions like withdrawing/depositing bitcoins.

- The risk here is for exchange tone hacked or for them to scam everyone by telling that they were hacked. They also can freeze/restrict your account for whatever reason. All of the risks mentioned are fairly common.

- If someone somehow gets hold of your username/password to access the exchange you will loose your funds because the attacker will withdraw Bitcoins elsewhere. Note that some senior level administrators on the exchange probably have full access to your account. The point I am trying to make you kind of have to trust them not to be evil... :)


### What you should know to keep your Bitcoins secure?

Bitcoin (and most of other crypto) don't have usual accounts/passwords. Instead you get something usually referred as the “Private Key”. You get that key when setting a new wallet app/program for the first time. This key generated randomly so no one can ever guess it. Not even the most powerful computer in the world even if it runs for decades

The “Private Key” usually shown to you in a form of 12 plain English words. Sometimes it can be more than 12. Those 12 plain words is just a ”human readable” representation of that key.

Safely storing that “Private Key” is extremely important. Let's say you transferred some bitcoins to your new wallet app. Even if your phone stops working OR the wallet app stops working your funds are safe. You will always be able to restore access to your bitcoins using that “Private Key”. It can be even years later, in the same app or some other wallet app/program.

Treat “Private Key” wallet app gives you with great care. If someone ever sees it, your funds are in danger because that person can essentially download some wallet app and get access to you funds using that key.

Let's say you lost your phone and someone finds it. If the phone doesn't have the Android/iOS PIN lock in place, the person who found your phone may potentially access (hack into) the wallet app and from there essentially become in possession of that “Private Key” controlling your funds. That person may then spend your bitcoins by sending them to his/her address.

On the other hand, if your has OS PIN in place it would extremely difficult for someone to hack into it. You will have enough time to get a new phone or simply download some new wallet app to your computer. Use the 'Restore' option which most apps have to get access to your funds. 

Finally you will need to move your funds to a new wallet, which can be created on that same and will come with a new "Private Key". Once you have moved your funds, even if the intruder manages to break into your lost phone the old wallet will be useless as it won't have any money on it.

That’s the only thing you should really understand. The rest is secondary.


## 5. Send / Receive Bitcoin

### How to send Bitcoin?

Once certain amount of bitcoins are transferred to another address, their ownership is transferred to the owner of the destination address. From that moment onwards, only the owner of the destination address can send/transfer/spend those bitcoins. And for that this new owner will use his/her own PRIVATE KEY (which is know only to him/her.) to send/send them in the future.

Ownership of bitcoins essentially means the ownership of the SECRET KEY using which the owner of the key can spend corresponding amount of bitcoins. A bitcoin wallet is a program that primarily stores that key. 

The Send feature deducts amount the SECRET KEY can spend by passing the ownership for that amount to a new owner. The Receive feature allows someone to bitcoins from other people.

To send someone Bitcoin you simply need to ask the recipient for his/her address and then use the wallet where you have bitcoin to send the desired amount to the provided address.

Once certain amount of bitcoins are transferred to another address, their ownership is transferred to the owner of the destination address. From that moment onwards, only the owner of the destination address can send/transfer/spend those bitcoins. And for that this new owner will use his/her own PRIVATE KEY (which is know only to him/her.) to send/send them in the future.

Unlike regular money Bitcoin transactions are final and non reversible. Once they are sent it's impossible to revert them.
Storing Bitcoins

As mention above ownership of bitcoins essentially means the ownership of the SECRET KEY using which the owner of the key can spend corresponding amount of bitcoins. A bitcoin wallet is a program that primarily stores that key. The wallet also usually has SEND/RECEIVE features.


### How to receive Bitcoin?

### How to know that your Bitcoin transaction was successful?

### Are Bitcoin transactions anonymous?

### How long the transaction takes place?

At first transaction sent from sender's wallet to the network. At the end of this step most (usually > 99%) miners/nodes that store blockchain and process transactions have the transaction in something called as "mempool". This whole process usually takes a couple seconds. In practice, that would mean that when you send transaction the recipient will see it PENDING in his/her wallet within a couple seconds. 

It should be also noted that this would be the case if the wallet you're using is a decentralized one (i.e. talks directly to a blockchain rather than through a middle man).

When the transaction reaches every miner/node it's not yet part of the blockchain. The transaction becomes confirmed and no longer pending when it's included in the block. In Bitcoin blockchain the block closed roughly every 10 minutes, it varies for other blockchains.

.... 


### Bitcoin transaction fees explained


There are some factors which may affect the duration of this step. The main factor is the fee sender used when sending the transaction. If the fee is low and the mempool was crowded when transaction was sent it will take longer. More precisely, it will be confirmed when the mempool gets less crowded. In most cases it will happen within 24 hours.

If the fee was sufficient then it will most likely be confirmed within 10 minutes. So, that's why setting the fee properly is important, especially for large payments that need to happen quickly.

Some of the wallets that have the fee estimation/recommendations capabilities are bread wallet (https://brd.com), unstoppable wallet (https://unstoppable.money)

After the transaction is included in the block it can be already considered as completed.



### Is it possible to cancel bitcoin transaction?

After the transaction is included in the block it can be already considered as completed. However, there is a general consensus for the transaction to be considered as FINAL (irreversible) 6 more blocks has to pass after the transaction was included in the block. This will add roughly another 50 minutes.

There are some ways a transaction can be cancelled after it's sent...

## Bitcoin Nodes and Mining

### What is Bitcoin mining?

### Why mining is important?

### How to become a bitcoin miner  ?






