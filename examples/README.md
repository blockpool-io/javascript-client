## Blockpool Javascript API Client Examples

### `send-to-random-wallet`
This example sends 1 DBPL to a random wallet if you've enough balance. To do that, this examples makes use of the JavaScript crypto library that it is part of [Core](https://github.com/blockpool-io/core/tree/master/packages/crypto).

 * **To use this example, it's necessary having a devnet wallet with at least 1.1 DBPL**.

To try this example, install the dependencies, and execute the script:
```
cd examples
yarn install
BPL_CLIENT_EXAMPLE_SENDER="devnet wallet address" BPL_CLIENT_EXAMPLE_PASS="the twelve words that forms the password of the wallet" ./send-to-random-wallet.js
```
