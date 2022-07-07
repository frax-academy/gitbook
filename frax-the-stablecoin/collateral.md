# Collateral

Collateral are the assets backing a stablecoin. Collateral is a guarantee that a stablecoin token has a value, even when it goes to zero or stops trading on the open market. Frax does not have all of its collateral sitting as USDC tokens in a wallet, but uses it to create revenue for the protocol and increase the stability and availability of the FRAX token within DeFi.

#### FRAX's Collateral

The collateral of FRAX can be seen in the "Frax Distribution Graph" on [Frax Finance](https://app.frax.finance/). It currently consist of stablecoin tokens in FRAX pools on Curve Finance (Curve AMOs), stablecoin tokens in various other pools and protocols (Liquidity AMOs), non-stablecoin tokens (Investor AMO), claims on FRAX supplied to lending protocols (Lending AMOs), and USDC tokens (USDC pool). All this collateral sits on the blockchain and is directly owned by the protocol. While the Frax Shares token (FXS) is used by the protocol to back the price of FRAX, it is not counted as collateral (see [mint-and-redeem.md](mint-and-redeem.md "mention") for more info).

#### **Collateral Ratio**

Unique to FRAX is that it has a dynamic collateral ratio (CR). This means that the amount of collateral per FRAX token is not fixed, say 1:1 (100%) or 1:2 (50%) but determined by an algorithm. This algorithm lowers the collateral ratio when the demand for FRAX is high, and increases the ratio when the demand for FRAX is low. Historically the Collateral Ratio for FRAX has moved between 80 and 100% as can be seen in the dashboard on [Frax Finance](https://app.frax.finance/). Being fractionally collateralized is what gave Frax its name.

The dynamic collateral ratio, use of collateral, and AMOs are key features that make FRAX capital efficient and sustainable.
