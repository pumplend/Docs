---
icon: envelope-open-dollar
---

# Max Borrow

### Introduction

The Borrow feature on Pumpmax allows you to unlock liquidity without selling your Pump coins. By using your Pump coins as collateral, you can borrow SOL and maintain your market exposure. This straightforward approach gives you access to extra funds for additional purchasing power, all while keeping your Pump coin holdings intact.

### Key Features

* **Unlock Liquidity:** Use your Pump coins as collateral to borrow SOL.
* **Maintain Exposure:** Hold onto your Pump coins while accessing liquidity.
* **Simple Borrowing:** No flash loans or dynamic interest rates—just a clear, time-based liquidation process.
* **Account Rent Refund:** A small fee (in SOL) covers the creation of an SPL-PDA account for tracking tokens and transactions. This fee is refunded once the loan is fully repaid.

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

### How It Works

1. **Collateralization:**\
   Your Pump coins serve as collateral. The amount you can borrow is determined by the value of your collateral.
2. **Borrowing SOL:**\
   Based on your collateral’s value and the current market conditions, you borrow SOL. This borrowed amount is available immediately for your use.
3. **Time-Based Liquidation:**\
   Instead of dynamic interest rates or flash loans, our system uses a time-based liquidation process. If the collateral does not meet the required conditions within a set time frame, liquidation procedures are initiated.
4. **Repayment:**\
   You repay the borrowed SOL plus any applicable interest. Once fully repaid, the associated account is closed and the rent fee is returned.

### Usage Guidelines

* **Monitor Your Collateral:**\
  Keep an eye on your collateral value to ensure it remains above the required threshold during the borrowing period.
* **Understand the Liquidation Timing:**\
  Be aware of the specific time frames set for liquidation. Timely repayment is crucial to avoid liquidation.
* **Plan for Repayment:**\
  Repay your borrowed amount within the specified period to recover the account rent fee and avoid liquidation penalties.

### Risk Management

* **Time-Based Liquidation:**\
  Our system uses a fixed time window for liquidation if collateral conditions are not met, ensuring that the process is predictable and transparent.
* **Simplified Borrowing Environment:**\
  Without the complexity of flash loans or dynamic interest rates, the borrowing process remains straightforward, reducing the risk of unexpected changes.



Pumpmax's Borrow feature is designed to give Pump.fun users a simple and effective way to unlock liquidity without sacrificing their Pump coin holdings. By leveraging a clear, time-based liquidation model, we provide a predictable and user-friendly lending experience. This enables you to maximize your purchasing power while keeping your assets intact.

***
