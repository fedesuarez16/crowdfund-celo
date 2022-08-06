# CrowdFund Dapp

## Description
This is a very simple crowdfund dapp where users can:
* See campaigns hosted on the dapp
* Create campaigns
* Donate to campaigns
* End campaigns
* Get refund of the donation amount if campaign fails

## Live Demo
[CrowdFund Dapp](https://dacadeorg.github.io/celo-marketplace-dapp/)

## Usage

### Requirements
1. Install the [CeloExtensionWallet](https://chrome.google.com/webstore/detail/celoextensionwallet/kkilomkmpmkbdnfelcpgckmpcaemjcdh?hl=en) from the Google Chrome Store.
2. Create a wallet.
3. Go to [https://celo.org/developers/faucet](https://celo.org/developers/faucet) and get tokens for the alfajores testnet.
4. Switch to the alfajores testnet in the CeloExtensionWallet.

### Test
1. Create a product.
2. Create a second account in your extension wallet and send them cUSD tokens.
3. Buy product with secondary account.
4. Check if balance of first account increased.


## Project Setup

### Install
```
npm install
```

### Start
```
npm run dev
```

### Build
```
npm run build