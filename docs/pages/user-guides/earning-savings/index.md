---
description: Learn how to earn savings on your stablecoin holdings.
---

# Earning Savings

:::info
Savings are now live on Base! More networks will be supported soon.
:::

Spark enables users to easily deposit stablecoins into savings, and receive Savings USDS (sUSDS) tokens in return. The sUSDS tokens represents your share of USDS in the Sky Savings Rate. As savings accrue, sUSDS increases in value over time. The Sky Savings Rate is set by Sky Governance. [You can read more about sUSDS here.](/user-guides/earning-savings/savings-usds)

Savings are supported on Ethereum, Base and Gnosis Chain. More major networks will be supported soon.

:::info
**Note:** Savings USDS and the Sky Savings Rate are non-custodial and permissionless smart contracts offered by Sky, and is not issued by Spark. Spark never has custody of funds deposited into savings or any control over the Sky Savings Rate or sUSDS token.
:::

## Tutorial

### Deposit Savings

1. Make sure you are connected to the network you wish to use. [Savings are supported across different networks](/user-guides/earning-savings/savings-usds#supported-networks-and-token-addresses).
2.  To earn yield on your stablecoins such as USDS, DAI, and USDC, navigate to the **Savings** page.

![](/assets/savings-1.png)
*Savings Page*

3. If you have stablecoins in your wallet, the UI will show you the savings opportunity based on your holdings. It shows the current Sky Savings Rate (SSR), a 30 day projected savings and a 1-year projected savings.

4. To deposit stablecoins, you navigate to the **Stablecoins in wallet** section, which displays the stablecoin holdings in your wallet, and click on the deposit button for the asset you wish to deposit.

5.  In the deposit window you specify the stablecoin (dropdown) and amount (input) you wish to deposit.

    In the Transaction Overview it will show the APY, the route (if not using USDS, how tokens are swapped, before being deposited), and the final outcome of the deposit.
    To finalize the deposit you must execute the transactions in the **Actions** section.

![](/assets/savings-2.png)
*Depositing USDS, and receiving sUSDS*

**Note:** If you deposit other stablecoins than USDS, they will be swapped for USDS before being deposited into Savings. The swap route is shown in the Transaction Overview. This swap uses non-custodial Sky smart contracts, and is not facilitated or in any way custodied by Spark.

The following example showcases a USDC deposit:

![](/assets/savings-3.png)
*Depositing USDC into Savings*

6. Once you have done all the necessary transactions, the specified amount of assets will be deposited and you will receive Savings USDS (sUSDS) tokens in return.

![](/assets/savings-4.png)
*Confirmation Savings Deposit*

7. The sUSDS tokens represents your share of USDS deposited the Sky Savings Rate. You need the sUSDS tokens to withdraw accrued savings in the future, so keep the tokens safe.

### Withdraw Savings

1.  When you wish to withdraw accrued savings, you simply click on the withdraw button in the Savings USDS window. In the withdraw window you specify the asset and amount you wish to withdraw. To finalize the withdrawal you must execute the transactions in the **Actions** section.


![](/assets/savings-5.png)
*Withdraw from Savings*

![](/assets/savings-6.png)
*Withdraw from Savings*

**Note:** If you withdraw USDC from Savings, USDS will be swapped for USDC using the Sky PSM after being withdrawn from Savings. The Sky PSM does not incur any slippage or fee beyond gas. The swap route is shown in the Transaction Overview. This swap is possible as long as there is liquidity in the Sky PSM. This swap uses non-custodial Sky smart contracts, and is not facilitated or in any way custodied by Spark.

The following example showcases a USDC withdrawal:

![](/assets/savings-7.png)
*USDC withdrawal from Savings*

2. Once you have done all the necessary transactions, the specified amount of USDS will be transferred to your wallet in exchange for sUSDS tokens.

![](/assets/savings-8.png)
*Confirmation: Withdrawal from Savings*