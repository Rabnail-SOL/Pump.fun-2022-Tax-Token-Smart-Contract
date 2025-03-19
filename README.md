## Tax Token (Token 2022) Pumpfun Smart Contract ⚓
Pump.fun smart contract that works just like pump.fun, but with Token 2022 to support fee distribution to users and token creator. 
After hitting 100% bonding curve it is migrated to Raydium CPMM pool.

There are 2 types of contracts that I have developed, one that use SPL token and migrating to Raydium AMM (V4), and one that use token 2022 to support earning from fee and migrate to Raydium CPMM.

#### Token 2022 (tax token) contract deployed to devnet.
[4kVhbPiRZZm5HHruHgQfR42tDGXE1SuCTkcrZ5bHGDCp](https://solscan.io/account/4kVhbPiRZZm5HHruHgQfR42tDGXE1SuCTkcrZ5bHGDCp?cluster=devnet)

#### SPL token pump.fun contract deployed to devnet.
[5mdPUgyK9mqosLtqZvfpY5pcpCqQBWHuS3XoU34CrJK3](https://solscan.io/account/5mdPUgyK9mqosLtqZvfpY5pcpCqQBWHuS3XoU34CrJK3?cluster=devnet)


### Benefits of upgrated new Token 2022 Pump.fun smart contract compared to pump.fun
- The token creator and token holders get reward from tax fee from token itself, decreasing the possibility of rug pull by rewarding token creator not by pulling liquidity but by holding the token.
- CPMM pool creation does not need openbook market program, and costs much less to create pool, providing pool creator much more SOL and reduce loss when migrating to raydium.


In here, you can see the creation transaction, buy and sell transaction and withdraw transaction

## Environement and Development ⚙️
- For the one who want to clone the project, need to setup as following

```
    - anchor : v0.30.1
    - solana : v1.18.18
    - rustc : v1.82.0 
```
- Main functions

```
    - Contract initialization
    - Launching pool (bonding curve)
    - Swap (buy and sell)
    - Migration (Raydium CPMM)
    - Some admin related functions
```


## Recording of pumpfun smart contract test process

You can see how the project works from this video.

https://github.com/user-attachments/assets/09ecf494-117f-4e8b-926f-7f27942d182f


Uploaded the contract test video with solscan explorer to my X.
[Smart Contract Test Video](https://x.com/Rabnail_SOL/status/1902255553650340249)   

Original smart contract test video recorded.

https://github.com/user-attachments/assets/54606cb9-3be0-49a9-a92d-2759d0648f4b


### Frontend and backend part is also developed and reserved as private.

### Raydium migration and other detailed code are reserved for private, you can contact me for more understanding about the project and other features

### 👤 Author
#### Twitter: [@Rabnail_SOL](https://twitter.com/Rabnail_SOL)   
#### Telegram: [@Rabnail_SOL](https://t.me/Rabnail_SOL)   
