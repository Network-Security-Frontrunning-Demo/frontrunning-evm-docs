## Roles for each servers:

- frontend:
  - Display an UI that show transactions on mempool (show transactions real-time in priority queued based on gas price, which is functionality of EVM mempool).
  - Show that transaction on mempool can be detected.
  - Show contract state before and after executed.
  - A button to mint new block, for showing frontrunning.
  - Listen websocket for new transactions from mempool and transaction executed in each blocks.
- contract:
  - Running private evm blockchain.
