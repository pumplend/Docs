---
description: Explorer Api Interface List
---

# Explorer Api

Pumpmax protocol explorer api is fully [opensource](https://github.com/pumplend/explorer-api) . You can frok it and run it in our local .&#x20;

## Base URL&#x20;

[`https://api.pumpmax.fun/explorer`](https://api.pumpmax.fun/explorer/positions)&#x20;



## Get Active Positions&#x20;

* Base Url :&#x20;
  * `/`positions
* Method :
  * `GET`
* Query :&#x20;
  * `user`:
    * String
    * Optional
      * User address in base58 .&#x20;
  * `token`
    * String
    * Optional
      * Token Mint address in base58 .&#x20;
  * `userBorrowData`
    * String
    * Optional
      * UserToken BorrowData address in base58 .&#x20;
  * `hash`
    * String
    * Optional
      * SOLANA transaction hash in base58 .&#x20;
  * `deadline`
    * Number
    * Optional
      * Timestamp for the liqudtion time
  * `page`
    * Number
    * Optional
      * Page num
  * `pageSize`
    * Number
    * Optional
      * Page Size
* Response:

```json
{
    "code": 200,
    "data": [
        {
        "hash": "2FzqbCeSK6dc5R4btd5E8Togrj1FCoNsdYCY5uTGyBgN4hLXTuJsyqGjwACcFWB1x7Q6CiM8AEAHNzTT3kEDmeBJ",
        "id": "PDMMQiE5PVdu37icVXurDBUsXKGM5NsP3GLmkNEdMSJ",
        "user": "Ge3vpViqwz4fvx2EAZPsAfvUiwh7PajvTsZtKW33nMmE",
        "token": "Eq1Wrk62j2F2tLf9XfdBssYJVr5k8oLJx3pqEL1rpump",
        "collateralAmount": "15793974000000",
        "depositSolAmount": "0",
        "borrowedAmount": "304624623",
        "referrer": "Ge3vpViqwz4fvx2EAZPsAfvUiwh7PajvTsZtKW33nMmE",
        "blockTime": 1739175781,
        "deadline": 1740705097
        }
    ]
}
```



## Get Active History

* Base Url :&#x20;
  * `/`actives
* Method :
  * `GET`
* Query :&#x20;
  * `user`:
    * String
    * Optional
      * User address in base58 .&#x20;
  * `token`
    * String
    * Optional
      * Token Mint address in base58 .&#x20;
  * `userBorrowData`
    * String
    * Optional
      * UserToken BorrowData address in base58 .&#x20;
  * `hash`
    * String
    * Optional
      * SOLANA transaction hash in base58 .&#x20;
  * `type`
    * String&#x20;
      * "stake"
      * "withdraw"
      * "borrow"
      * "repay"
      * "borrow\_loop\_pump"
      * "borrow\_loop\_raydium"
      * "liqudtion\_pump"
      * "liqudiion\_raydium"
    * Optional
      * SOLANA transaction hash in base58 .&#x20;
  * `deadline`
    * Number
    * Optional
      * Timestamp for the liqudtion time
  * `page`
    * Number
    * Optional
      * Page num
  * `pageSize`
    * Number
    * Optional
      * Page Size
* Response:

<pre class="language-json"><code class="lang-json">{
<strong>    "code": 200,
</strong>    "data": [
        {
        "hash": "3CpWNX1QWgc7uj7495TeYGDCKdVxW4mxQjzBSBauvzN4E3718bqAQR6g6NgXMTDe2eH2eiMrjfFSQPFoG5hEQZH4",
        "id": "ALHyT76TPSuWX6xpQifhmD9JGvgURVMxzfjprfe1DkFA",
        "type": "liquidatePump",
        "liquidator": "3NKhkQpqjBzQfYZ3CmmAsHTreCE8ZEJza8rjgab5YtFh",
        "user": "3NKhkQpqjBzQfYZ3CmmAsHTreCE8ZEJza8rjgab5YtFh",
        "token": "CbineB365vkiy3rNgvxuBm6cXxA4iu6uAAsHwX5rpump",
        "referrer": "3NKhkQpqjBzQfYZ3CmmAsHTreCE8ZEJza8rjgab5YtFh",
        "blockTime": 1739175912
        }
    ]
}
</code></pre>



