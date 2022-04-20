# Unit 21: Martian Token Crowdsale

![alt=""](Images/application-image.png)

## Background

After waiting for years and passing several tests, the Martian Aerospace Agency selected me to become part of the first human colony on Mars. As a prominent fintech professional, they chose me to lead a project developing a monetary system for the new Mars colony. I decided to base this new system on blockchain technology and to define a new cryptocurrency named **KaseiCoin**. (Kasei meaning Mars in Japanese.)

KaseiCoin will be a fungible token that’s ERC-20 compliant. I'll launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.

## Important Note

The requiements advise to copile the contract by using compiler version 0.5.0. Due to updates in the OpenZepplin import files, the contract needs to be compiled with version 0.5.5. As such this version has been used for consitency in all .sol files. 

### Create the KaseiCoin Token Contract

![](https://github.com/apfreeman/Unit-21-Martian-Token-Crowdsale/blob/main/Images/1_coin_compiled.PNG?raw=true)

### Create the KaseiCoin Crowdsale Contract

![](https://github.com/apfreeman/Unit-21-Martian-Token-Crowdsale/blob/main/Images/2_contract_compiled.PNG?raw=true)

### Create the KaseiCoin Deployer Contract

![](https://github.com/apfreeman/Unit-21-Martian-Token-Crowdsale/blob/main/Images/3_deployer_contract_compiled.PNG?raw=true)

### Deploy and Test the Crowdsale on a Local Blockchain

1. Deploy the crowdsale to a local blockchain by using Remix, MetaMask, and Ganache.

[Click Here - Deploy Crowdsale Video](https://screenrec.com/share/f4kxuhTonB)

2. Test the functionality of the crowdsale by using test accounts to buy new tokens and then checking the balances of those accounts.

3. Review the total supply of minted tokens and the amount of wei that the crowdsale contract has raised.





