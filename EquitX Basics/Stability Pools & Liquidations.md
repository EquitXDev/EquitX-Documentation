# Stability Pools & Liquidations

## What are Stability Pools?

**Overview**

Stability Pools at EquitX serve a critical role in maintaining the solvency of eStocks by acting as liquidity reserves. These pools are used to absorb debts from liquidated Collateral Debt Positions (CDPs), ensuring that all minted eStocks are consistently overcollateralized. Each type of eStock supported by EquitX has its corresponding Stability Pool, which is funded by eStocks that users voluntarily deposit.

**Liquidation Mechanism**

When a CDP becomes undercollateralized, possibly due to fluctuations in the underlying asset's value, it is eligible for liquidation. In such an event, eStocks deposited in the relevant Stability Pool are burned to settle the CDP's debt. Stability Pool contributors, therefore, lose a portion of their eStock deposits but gain a pro-rata share of the liquidated CDP's collateral, which can offset or even exceed the loss of eStocks.

**How to Deposit eStocks into a Stability Pool?**

To contribute to a Stability Pool, you must own eStocks, which you might have obtained by opening a CDP or purchasing on the open market. Depositing these eStocks into the corresponding Stability Pool can be done through the EquitX platform interface.

**Benefits for Stability Pool Contributors**

Contributors to Stability Pools not only help in maintaining the overall health and stability of the platform but also earn rewards. These rewards are distributed in EQTX tokens, enhancing the incentives for participation.

**Changes in eStock Balance**

If you notice a decrease in your eStock balance within the Stability Pool, it is likely due to liquidations where your eStocks were used to cover debts. In return, you receive a proportional share of the collateral from the liquidated CDPs.

**Fees Associated with Stability Pools**

There are several fees associated with participating in Stability Pools:

1. A nominal XLM fee for initial deposits into a Stability Pool, redistributed as rewards to all pool contributors.

2. A transaction fee (for deposits, withdrawals, or reward claims), also redistributed to contributors.

3. A 2% fee on the total collateral rewards from liquidated CDPs, redistributed to EQTX stakers. As with all protocol parameters, this fee can be adjusted based on governance decisions by the community.


## What are Liquidations?

**Overview**

Liquidations occur when a CDP's collateral value falls below the required threshold, making it undercollateralized. Both automated systems and community participants can trigger liquidations to protect the platform's integrity.

**Liquidation Process**

1. Freeze the CDP: This action removes all access and control over the CDP from its owner, preventing any further activity.
2. Liquidate the CDP: The debt of the CDP is cleared by burning the corresponding eStocks from the Stability Pool, and the CDP’s remaining collateral is distributed among the Stability Pool stakers.


**Incentives for Liquidating CDPs**

Liquidating CDPs is incentivized because participants can acquire a share of the collateral, which is often worth more than the value of the eStocks burned to cover the debt. This not only supports the financial stability of EquitX but also provides a potentially profitable activity for users.






