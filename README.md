- Installation

```
- yarn add @maticnetwork/maticjs
```

- Importing Plasma and POS client

```
const MaticPlasmaClient = require("@maticnetwork/maticjs").default;

const {MaticPoSClient} = require("@maticnetwork/maticjs);

yarn add @maticnetwork/walletconnect-provider

yarn add web3
```

- loadWeb3

```
window.web3 = new Web3(window.ethereum);
await window.ethereum.enable();
```

```
// Matic Provider
const maticProvider = new WalletConnectProvider({
    host: MATIC_PRC,
});
```

```
// Ethereum Provider
const ethereumProvider = new WalletConnectProvider({
    host: ETHEREUM_PRC,
});
```
