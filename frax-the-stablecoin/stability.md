# Stability

Frax Finance ensures that FRAX trades at 1 USD with 3 mechanisms.

The first mechanism is that FRAX can be exchanged back and forward for 1 USD with the protocol, through the [mint-and-redeem.md](mint-and-redeem.md "mention") functions. So when FRAX trades above or below a dollar, anyone can use these protocol funtions to profit from a price difference. This arbitrage process restores the price of FRAX on the market to the peg.

The second method is by having users add FRAX against other stablecoins like USDC and DAI in trading pools on Decentralised EXchanges (DEX'es). This is done through Frax's staking program and through incentives for Curve stakers (often called "bribing"). More stablecoin-to-stablecoin liquidity means that more FRAX can be bought or sold before the price is impacted.

The third method is by having the protocol, opposed to users, own the liquidity in the stablecoin pools. This is also called Protocol Owned Liquidity or POL. FRAX has created specific smart contracts, called Autonomous Market Operations (AMOs), that have been very successful in increasing Frax's POL. So successful that there currently is not enough FRAX circulating that can be sold to make FRAX depeg.

