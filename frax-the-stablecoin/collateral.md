# Collateral

Collateral are the assets backing a financial agreement that guarantee that it has a value. The purpose of collateral is to cement trust between the holder and the asset so the holder does not have to worry about the asset going to zero. There are several examples of collateral being used in DeFi including for loans and in the case of FRAX, a stablecoin.

#### Collateral Assets

At launch FRAX's collateral consisted of USDC tokens sitting idle in a smart contract. With the introduction of Algorithmic Market Operations (AMOs), Frax has diversified its collateral. This diverse range of collateral of FRAX can be seen in the "Frax Distribution" diagram on [Frax Finance](https://app.frax.finance/). It currently consist of stablecoin tokens in FRAX pools on Curve Finance (Curve AMOs), stablecoin tokens in various other pools and protocols (Liquidity AMOs), non-stablecoin tokens (Investor AMO), claims on FRAX supplied to lending protocols (Lending AMOs), and USDC tokens (USDC pool). All this collateral sits on the blockchain and is directly owned by the protocol. While the Frax Shares token (FXS) is used by the protocol to back the price of FRAX, it is not counted as collateral (see [mint-and-redeem.md](mint-and-redeem.md "mention") for more info).

#### Collateral Ratio

Unique to FRAX is that it has a dynamic collateral ratio (CR) which has been adjusting based on market demand since its inception. This means that the amount of collateral per FRAX token is not fixed, say 1:1 (100%) or 1:2 (50%) but determined by an algorithm. This algorithm lowers the collateral ratio when the demand for FRAX is high, and increases the ratio when the demand for FRAX is low (see the [official documentation](https://docs.frax.finance/price-stability#pidcontroller-update) for details). Historically the Collateral Ratio for FRAX has moved between 80 and 100% as can be seen in the dashboard on [Frax Finance](https://app.frax.finance/). Being fractionally collateralized is what gave Frax its name.



The dynamic collateral ratio and AMOs are key features that make FRAX capital efficient and sustainable.
