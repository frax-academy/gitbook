# Collateral Ratio

Frax's collateral ratio is defined as the total value of its collateral divided by the number of FRAX tokens issued. The higher the ratio, the more value backing each FRAX token. FRAX tokens that are owned by the protocol are excluded from the calculation. The reason for this is that protocol has no claim on collateral for any FRAX tokens it owns, just like you can't be in debt to yourself.

Unique to FRAX is its dynamic collateral ratio (CR) that has been adjusting based on market demand since its inception. This means that the amount of collateral per FRAX token is not fixed, say 1:1 (100%) or 1:2 (50%), but determined by an algorithm. This algorithm lowers the collateral ratio when the demand for FRAX is high, and increases the ratio when the demand for FRAX is low (see the [official documentation](https://docs.frax.finance/price-stability#pidcontroller-update) for details). Historically the Collateral Ratio for FRAX has moved between 80 and 100% as can be seen in the dashboard on [Frax Finance](https://app.frax.finance/). Being fractionally collateralized is what gave Frax its name.



