This is a patched version of the Parity/Openethereum node which we used in our 2020 Usenix Security paper [EthBMC](https://github.com/RUB-SysSec/EthBMC).
Note this version is based on the most recent stable relase (2.7.2).

We added an additional rpc call which dumps the storage of an account. The main logic can be found [here](https://github.com/Joool/openethereum/blob/b73fb28dfd5560487dc8b20bae62c9897a998a31/ethcore/src/client/client.rs#L1776-L1818).
