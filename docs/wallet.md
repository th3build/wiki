# Be Your Own Bank

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/cbMDgGD-HOE?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

*You can copy the code we used to deploy multi-sig wallets [here](https://github.com/th3build/btc-multisig)*

First thing you'll need to do is equip yourself with a bitcoin wallet. This will teach you the basics how to receive and send cryptocurrency so that you can begin equipping your friends!

Bitcoin is more fun when you use it with people. Once you are familiar with how a cryptocurrency wallet works, you'll have the independence of being able to manage your own money, and make organizations that share money, all by yourself.

?> **At the end of this excercise, you'll have the same power as banks, in your pocket.**

## Wallet Basics

Everytime you create a bitcoin wallet, you'll receive the following
* **A Seed**: 12 or 24 randomly generated words. These words are used to recreate your wallet incase you lose access to it.
* **A Private Key**: the password to spend the coin 
* **A Public Address**: similar to an email address, you send this to everyone so they can send money to you. It's completely safe to send the public address to anyone, they won't be able to send coin without the private pey.

!> **The Seed is your BACKUP.** <br> 
**When you generate this, DO NOT TAKE A SCREENSHOT.** <br>
*These words should be written on paper with a pen/pencil, and then store that piece of paper somewhere safe. You don't want anyone on the internet knowing your seed, or they can take all the money out of your wallet.*

## 🔥 Hot Wallet

**Purpose**: For conveniently and quickly spending coin.

A hot wallet is any that connects to the internet. It's called hot because it's extremely dangerous to hold large amounts of money in this wallet. This is the wallet you carry around with you around town and making purchases. When it runs out of funds, you'll refill it with money from your cold storage.

<!-- https://www.tablesgenerator.com/markdown_tables# -->

**Hot Wallet Recommendations**
* 🖥 Windows/Mac OSX/Linux: [Electrum](https://bitcoin.org/en/wallets/desktop/mac/electrum/) | [Exodus](https://www.exodus.io/)
* 📱 Android/iOS: [BTC.com](https://wallet.btc.com/#/setup/register) | [Coinomi](https://www.coinomi.com/downloads/) | [Edge](https://edge.app/) | [GreenAddress](https://greenaddress.it/en/wallet.html#/create_warning)

!> Note these options should only be used for smaller amounts of money. Savings should be kept in cold storage. 

## ❄️ Cold Storage

**Purpose**: For secure long-term storage of your coin.

A cold-storage wallet does not connect to the internet. It's optimized for security, meaning it's safer to store your coin compared to your hot wallet.

**Cold Storage Recommendations**
* [Trezor](https://shop.trezor.io/product/trezor-one-white)
* [Ledger](https://www.ledger.com/products/ledger-nano-s?r=6f77f179bcff)

## 👥 Multi-Sig

**Purpose**: For sharing a wallet with multiple people. Everyone must approve each transaction.

A multisig (multiple-signatures) wallet lets you create organizations/projects with other people. Everyone involved can join the shared wallet, making it easy for anyone to send money to the shared wallet. This let's groups easily setup secure wallets for facilitating payments/donations to their project, without someone running off with the funds when no one is looking.

**Multi-Sig Wallet Recommendations**

* [CoPay](https://copay.io/) (Without Terminal)
* [Fork th3build's multisig script](https://github.com/th3build/btc-multisig)