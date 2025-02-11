# Website Api

Website api is a proxy for pump.fun http-interface.

## Base Url :

`https://app.pumpmax.fun/api`

## Random Pump Token

* Base Url :&#x20;
  * `/`
* Method :
  * `GET`
* Query :&#x20;
  * `limit` : Number : How many data you wants .
* Response:

```json
[
    {
    "mint": "977qicYEptMPuKNyS2LTNWnS9FJN175uG8uihHgrJT92",
    "name": "MARGIN",
    "symbol": "VIVACIOUS",
    "description": "SNARL",
    "image_uri": "https://ipfs.io/ipfs/QmWfycMzqjrgpfVLu4wUET8gdmB864G4LYehAK4LjGfiqi",
    "metadata_uri": "https://ipfs.io/ipfs/QmW5AwX3CMEt9eCiPpScvgCre35d2Jdph5Sj69XPAQcCWk",
    "twitter": "https://tweethunter.io/fake-tweet-generator",
    "telegram": "https://tweethunter.io/fake-tweet-generator",
    "bonding_curve": "AmX8n525cuwLcAQJmxy9rVF4fE7e8orXMamh1iCQCU5H",
    "associated_bonding_curve": "DkPkgn8vynU1fQiKzPatihLyt988k58asr2NGUJawk5G",
    "creator": "6PU71xg7FBFPmdEf5emovDXSmMFVtkfmeh4ap8vjovi6",
    "created_timestamp": 1739259431166,
    "raydium_pool": null,
    "complete": false,
    "virtual_sol_reserves": 30880533392,
    "virtual_token_reserves": 1042404274316511,
    "hidden": null,
    "total_supply": 1000000000000000,
    "website": "https://tweethunter.io/fake-tweet-generator",
    "show_name": true,
    "last_trade_timestamp": 1739259433000,
    "king_of_the_hill_timestamp": null,
    "market_cap": 29.624334965,
    "reply_count": 0,
    "last_reply": null,
    "nsfw": false,
    "market_id": null,
    "inverted": null,
    "is_currently_live": false,
    "username": null,
    "profile_image": null,
    "usd_market_cap": 6085.13464516065
    }
]
```

## Search Pump Token

* Base Url :&#x20;
  * `/search/:search/:limit`
* Method :&#x20;
  * &#x20;`GET`
* Response

```json
[
    {
    "mint": "EUo725ahDJeMVEMkUwyJavWqp5HsgvUZYWybfNw2pump",
    "name": "Pumpmax.fun",
    "symbol": "Pumpmax",
    "description": "Unlock Pump coin liquidity→ Unlock Pump coins potential!Collateralize coins→ Borrow SOL → MaxBuy → Repeat. 🔄🚀.No price oracles, only time-based safety. ⏳ ",
    "image_uri": "https://ipfs.io/ipfs/QmaSQ3PWJcJb5n2vE4iEWAPUZ1odQw2VEJ3UsPycG5qKze",
    "metadata_uri": "https://ipfs.io/ipfs/Qmf8thkPwM2gEfkNQ3VtUaPH3vcddmRQUwGwNyPHy4r4dU",
    "twitter": "https://x.com/pumpmaxfun",
    "telegram": null,
    "bonding_curve": "GRb5vGxYc5CF6ncT22Gi4ks7WaW1sPKb8pUddgtQwhKC",
    "associated_bonding_curve": "71PQxAacNNCDRqqa4gKjPQDS1znkJE5XMS2YzM4t54Sm",
    "creator": "6ydMPqJUvSALdNjMNcCt59wY7UtHdVr56K1hndekNtT2",
    "created_timestamp": 1739029235815,
    "raydium_pool": null,
    "complete": false,
    "virtual_sol_reserves": 30000000006,
    "virtual_token_reserves": 1073000000000000,
    "hidden": null,
    "total_supply": 1000000000000000,
    "website": "https://pumpmax.fun/",
    "show_name": true,
    "last_trade_timestamp": 1739031339000,
    "king_of_the_hill_timestamp": null,
    "market_cap": 27.958993481,
    "reply_count": 0,
    "last_reply": null,
    "nsfw": false,
    "market_id": null,
    "inverted": null,
    "is_currently_live": false,
    "username": null,
    "profile_image": null,
    "usd_market_cap": 5743.05685093221
    },
    {
    "mint": "7Hf5LRvWg5xvGpgdcb62FZhjECrKstqtavJ9yihcpump",
    "name": "Pumpmax.fun test coin",
    "symbol": "pmf",
    "description": "Pumpmax is a financial platform built for Pump.fun users, offering integrated lending and spot leverage features.",
    "image_uri": "https://ipfs.io/ipfs/QmTYwWD164JR53sZq5x67zJhH2oQCmK2kkMyq1sGk6Rsgt",
    "metadata_uri": "https://ipfs.io/ipfs/QmNpfDqvf4CTTYUZscUDixq6ytkUHbJhSoNpnWfX2ASBxw",
    "twitter": null,
    "telegram": null,
    "bonding_curve": "3eHjjYKtxkssbAENpoeJphvqrcBJXxS4VzRdcq4ySjP2",
    "associated_bonding_curve": "E4yPkkeLpaGvLP2beEpZYB7Vi5cjqm7J1CFxWfa2J9hb",
    "creator": "FqJ1vRkdaipZ9WYTf3UAaDSsFHCjvBodQUodyMCdhdRX",
    "created_timestamp": 1738946684793,
    "raydium_pool": null,
    "complete": false,
    "virtual_sol_reserves": 30001000006,
    "virtual_token_reserves": 1072964234525516,
    "hidden": null,
    "total_supply": 1000000000000000,
    "website": null,
    "show_name": true,
    "last_trade_timestamp": 1738972575000,
    "king_of_the_hill_timestamp": null,
    "market_cap": 27.960857445,
    "reply_count": 0,
    "last_reply": null,
    "nsfw": false,
    "market_id": null,
    "inverted": null,
    "is_currently_live": false,
    "username": "FqJ1vR",
    "profile_image": null,
    "usd_market_cap": 5743.43972777745
    }
]
```
