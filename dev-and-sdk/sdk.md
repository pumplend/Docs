---
description: SDK intergration of pumpmax protocol
---

# SDK

#### PUMPMAX NPM SDK IS [HERE](https://www.npmjs.com/package/@pumplend/pumplend-sdk) , IT'S FULLY [OPEN-SOURCE](https://github.com/pumplend/pumplend-npm-sdk)



## How to use it ?

Simple . start install it via&#x20;

```
npm i @pumplend/pumplend-sdk
```

And import it to your project .&#x20;

```javascript
const sdk = require("@pumplend/pumplend-sdk")
```

Or

```typescriptreact
import { Pumplend } from "@pumplend/pumplend-sdk";
```

Init the class first .&#x20;

```javascript
  const lend = new Pumplend("devnet");
```

Now you can generate the transaction you wants now . For example

```typescript
  const tx = await lend.leverage_raydium(
    connection,
    amount * LAMPORTS_PER_SOL,
    token,
    publicKey,
    publicKey,
  );
```

### Function method support

* `stake`
  * Stake SOL into protocol
* `withdraw`
  * Withdraw SOL from protocol
* `borrow`
  * Deposite token and borrow out SOL from contract
* `repay`
  * Repay SOL and take token back
* `liquidate_pump`
  * From borrow account : Close the position of user token in pump.fun
  * From other account : liquidate the user token position in pump.fun
* `liquidate_raydium`
  * From borrow account : Close the position of user token in raydium
  * From other account : liquidate the user token position in raydium
* Pump.fun Functions
  * `pump_buy`
    * Buy Tokens in pump.fun
  * `pump_sell`
    * Sell Tokens in pump.fun
  * `mint`
    * New Token Mint via pump.fun

### Data fetch support

* `UserBorrowData`
  * The borrow data information
* `PoolStakingData`
  * Currently staking information of pool
* `UserStakingData`
  * Staking data of users
* `SystemConfigData`
  * Protocol base states and currently status
* `pumplend_culcuate_max_borrow`
  * Get max borrw able amount with tokenamount input
* `pumplend_culcuate_max_leverage`
  * Get max leverage able amount with SOLamount input
* Pump.fun Datas
  * `BondingCurve`
    * Details information of Bonding Curve

