## Header
This is the course header. This will be added on top of every page. Go to [DoDAO.io](https://www.dodao.io) to know more.

 ---
 
 ## Uniswap
 
 **Introduction**        
Inspired by one of Vitalik’s reddit [posts](https://www.reddit.com/r/ethereum/comments/55m04x/lets_run_onchain_decentralized_exchanges_the_way/) a few years ago, Hayden Adams initially sought to gain some Solidity practice; however, this training exercise quickly evolved into receiving a grant from the Ethereum Foundation, and then further development of Uniswap.

Uniswap was launched in November 2018 and was the first automated market maker (AMM) in the Ethereum ecosystem. This model quickly became popular and sparked a number of Uniswap clones (SushiSwap, PankakeSwap, MoonSwap). Since then, Uniswap has released a third major release of its AMM.

### Version 1
Uniswap V1 allows traders on the Ethereum network to use a new system of trading called Automated Market Maker (AMM) to allow traders to trade with a pool of money at any point in time with very low fees and they can theoretically trade for an infinite amount of coins. This happens because Uniswap was created using smart contracts. Here to understand the AMM, for example, if traders spent $200 they would get 1ETH and the next time when again they spent $200 they get 0.8ETH because due to buying the price of the 1ETH went up. Other investors and traders deposit the money in the pool and then trade with this money.


One of the drawbacks of the V1 was that it had many Liquidity pools but all of the pools had to contain at least Ethereum. For example, the pool can comprise of USDC and Ethereum pair or a Basic Attention Token (BAT) and Ethereum pair. Now if a trader wanted to trade USDC against BAT, they need to interact with each of the pools hence extra work.

### Version 2
The issue of interacting with various pools in V1 was resolved in V2. In V2, one can create any pool they want. For example, one can have USDC and BAT pair liquidity pool. Uniswap became famous for this transformation and since then they have grown exponentially. This update made Uniswap the most forked project in the  DeFi space.

### Version 3

  #### Concentrated Liquidity
  Uniswap V3 was launched on March 2021, on the Ethereum Mainnnet and Optimism Mainnet (Secondary Network used to scale Ethereum). The big update in V3 is the concept of concentrated Liquidity. The basic advantage of concentrated liquidity is that one can make their money work harder by applying some rules to it. Generally, when an investor puts their money in the liquidity pool and this pool lets other traders trade back and forth in the same pool and the liquidity provider (the investor) collects some small fraction of fees for each trade. In V3, the investor chooses a certain price range where they want to concentrate their liquidity. For example, if the investor chooses the bracket of $3000-$4000 for the Ethereum pool it means they want to trade their assets only within this range of Ethereum, This concentrated liquidity provides better return rates compared to fairly distributed funds. However there is a disadvantage of Impermanent loss, but as long as the price range of Ethereum is within the range of the concentrated liquidity the investor earns better returns.

  #### Flexible Fees
  Uniswap V1 consisted only of flat fees of 0.3% and V2 had a 0.05% protocol fee which could be turned on/off. Whereas V3 onwards there is a three-tier fee structure:

  1. `0.05%`- predicted for stablecoin pools like DAI/USDC
  2. `0.30%`- for standard non-correlated pools like ETH/DAI
  3. `1.00%`- for exotic non-correlated pairs

  #### Advanced Oracles
  The TWAP (Time-weighted average price) oracles saw substantial advancements with Uniswap v3. As opposed to Uniswap v2, it stores an array of cumulative sums, making it feasible to calculate any recent TWAP within the last nine days with just one on-chain call.


  This enhancement makes it simpler and less expensive to produce more sophisticated oracles. According to the team, this will result in a 50% reduction in the cost of gas used to maintain oracles.
 
 **Uniswap for Liquidity Providers**        
Anyone who is able to furnish a Uniswap exchange contract with an equal amount of ETH and an ERC-20 token qualifies as a liquidity provider. They receive tokens from the exchange contract in exchange, which they may use at any moment to withdraw their share of the liquidity pool. A 0.3% fee is charged for each trade made on the exchange, and this fee is allocated to the liquidity pool. This has the effect of dividing the transaction cost proportionally among all current liquidity providers since no new liquidity tokens are created.


In fact, trades are not only guaranteed to happen when the price in the larger market changes, but liquidity providers also get paid from all deals. This is due to the fact that if the price on another exchange changes, the price difference between that exchange and Uniswap will present an arbitrage opportunity. Liquidity providers gain from Uniswap exchange fees when an arbitrageur performs the lucrative trade that returns the Uniswap exchange to parity with the larger market. Sure enough, arbitrageurs are hard at work to keep prices closely aligned with the rest of the market on all Uniswap exchanges with considerable liquidity.
 
 **UNI Token**        
Uniswap created the UNI token to promote community ownership over the protocol, letting stakeholders vote on important protocol modifications and development efforts. This was done after years of successful operation and on its way to complete decentralisation. In September 2020, Uniswap launched the token. As a novel distribution method, it "airdropped" 400 UNI tokens to every Ethereum address that had ever used the protocol. The airdrop, which was valued at over 250,000 Ethereum addresses and about $1,400 at the time, was distributed. Since then, airdrops have gained popularity as a method for DeFi apps to thank loyal customers; Uniswap has stated that it intends to give away a total of 1 billion UNI over a four-year period.
 
 
