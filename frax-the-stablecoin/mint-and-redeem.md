# Mint and Redeem

Mint and Redeem are smart contract functions allowing anyone to mint (create) FRAX tokens or burn (destroy) FRAX tokens at a rate of 1 USD per FRAX.

****

**Mint**

Anyone can mint FRAX tokens by sending USDC and FXS tokens to a smart contract from Frax Finance. One always receives one FRAX token per one dollar worth of USDC and FXS tokens. The ratio between USDC and FXS is determined by the collateral ratio, see [collateral.md](collateral.md "mention"). Minting is only possible when the price of FRAX is higher than $1.0033, otherwise it is simply cheaper to buy FRAX on the open market. If FRAX trades above a dollar, anyone can profit by minting FRAX at one dollar and selling it on the market for more than a dollar. By selling FRAX on the market its price will decrease again, ensuring that the FRAX price returns to 1 USD quickly.

&#x20;****&#x20;

**Redeem**

Anyone can burn FRAX tokens and redeem them for USDC and FXS tokens using a smart contract from Frax Finance. One always receives one dollar worth of USDC and FXS tokens per FRAX token.  The ratio between USDC and FXS is determined by the collateral ratio, see [collateral.md](collateral.md "mention"). To ensure that FRAX tokens don’t get burned unnecessarily, redeeming is only possible when the price of FRAX drops below 0.9933 USD. This means that anyone can profit by buying FRAX below one dollar and redeeming for one dollar with the protocol. By buying FRAX on the market its price will increase again, ensuring that the FRAX price returns to 1 USD quickly.

&#x20;****&#x20;

_Note that in practice only large entities and bots are rich and/or quick enough to profit from the mint and redeem process._
