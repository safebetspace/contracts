# SafeBet smart contracts

In this repository, you will find SafeBet smart contracts.
Safebet.sol is the main token (BET) contract. The token is taking a 12% tax from each transaction on the blockchain (buy/sell orders on AMM and tokens transfers).

11% of each transaction is redistributed proportionally to actual holders (the more Bet tokens you have in your wallet, the more tokens are redistributed to you).
1% of each transaction is sent to the developer wallet (for development and marketing purposes).

The Pancakeswap liquidity tokens (LP) has been burned (so unclaimable forever), you can check via the link below that they are 100% owned by a dead address (no one can access it):
https://bscscan.com/token/0xac8c4e4803a9b28ff25655d1a150edaf4523c624#balances

Feel free to ask any question regarding these contracts into our telegram help desk: t.me/safebetspace
