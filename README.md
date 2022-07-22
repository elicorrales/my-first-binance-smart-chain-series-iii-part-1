# my-first-binance-smart-chain-series-iii-part-1  
  
[Set Up Your Dev Environment](https://github.com/elicorrales/blockchain-tutorials/blob/main/How-To-Set-Up-Ethereum-Env.md)  
  
## Learn To Use Ganache  
  
### Start Up Ganache  
DO:
```
 cd MySoftwareProjects/blockchain/rust/rust-binance-smart-chain-projects/my-first-project/
```  
  
In order to retain your data between development cycles, you might persist the database.  
DO:  
```
ganache --database.dbPath ~/MySoftwareProjects/blockchain/rust/rust-binance-smart-chain-projects/my-first-project/ganache-database
```  
  
OUTPUT:  
```
IamDeveloper@SoftwareDevelopUbuntu2004
~/MySoftwareProjects/blockchain/rust/rust-binance-smart-chain-projects/my-first-project-prep-lesson
$ ganache --database.dbPath ~/MySoftwareProjects/blockchain/rust/rust-binance-smart-chain-project
s/my-first-project-prep-lesson/ganache-database
ganache v7.3.2 (@ganache/cli: 0.4.2, @ganache/core: 0.4.2)
Starting RPC server

Available Accounts
==================
(0) 0x4F09aA48b88966BF8803D363B62902e540474Cac (1000 ETH)
(1) 0x57466b1Ef1093d9c744D6B1CF5964eA14A27323E (1000 ETH)
(2) 0x3d8f397f585ae006B168970c9152a401Cfd2b97A (1000 ETH)
(3) 0x033625DaD62A819580D10F9c3F98E616B18A598e (1000 ETH)
(4) 0xf7461AB804c6079fCF61Ab1cF512BB1C00b46b1D (1000 ETH)
(5) 0x2BE1c24688Cd9A7DB97947876aeDD0FB2294E554 (1000 ETH)
(6) 0xd0B3352EAEC0E50fF0b89219034Aa9f3c6a94a4f (1000 ETH)
(7) 0xa5e123324bE68E0a174a154f1aD7D11BbA96C7b5 (1000 ETH)
(8) 0x61911c65e39EAA55a9B31836A4fA1E2AA6069D89 (1000 ETH)
(9) 0x75A142116f2E43f52f6977a4cC73266A76487FEF (1000 ETH)

Private Keys
==================
(0) 0x49dcdebe2370025cb2eff30d4c7187272238afba33d377373c4a089e39bcbce9
(1) 0xd2c0be659f64a8386cb7b0dc80e4c815b263d7272a6342f606ea42e6f368e649
(2) 0x1455ee88e29d1761d0ee9e9f665739855426a89c4895f469192d1598ca9d94db
(3) 0x8668d45f93d89f264eddf6da40783c34ef39efa15447a4c705145ed82226731b
(4) 0x89495844f18bcabf4c7d20b62a6cfe359863c8baa3b7dc273151816590587a83
(5) 0x7cc1d7340a9a905df0d8418f2f95970305ab96d2618086c5629941aab493366c
(6) 0x8dbb8a7423f1e3c3ced85b5e4abf77ca8c51f1a6f21b1d6684c72ed15c8d6666
(7) 0x4520540ead05e4e5cfdc731cadb83651d3b6cedeb3b6150d8948fbdc1d4deb21
(8) 0xca59bcd22a74b296a8fcfdc38c39a805b2a809d17f09fe8178c208a4701e53da
(9) 0x4283706be7fc909e3865786f6b96725a18ca2d46cf73b8402c437e217155d82f

HD Wallet
==================
Mnemonic:      quick kiss receive pledge used pink student oblige edge pact polar erase
Base HD Path:  m/44'/60'/0'/0/{account_index}

Default Gas Price
==================
2000000000

BlockGas Limit
==================
30000000

Call Gas Limit
==================
50000000

Chain Id
==================
1337

RPC Listening on 127.0.0.1:8545
```  
  
Leave that running in a terminal, and open up another terminal.  
  
  


