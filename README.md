ERC-20 test
===========

This is a super simple ERC-20 token using [Open Zeppelin](https://openzeppelin.com/contracts/) to estimate the cost of deploying such a contract on Ethereum.

Using [Open Zeppelin's deploy instructions](https://docs.openzeppelin.com/learn/deploying-and-interacting) to deploy to a development Ethereum network (created using `ganche-cli`), we find that deploying this contract uses 1,107,670 gas units.

Similarly, we find that using `oz send-tx` to call the `approve` function to name an escrow uses 44,108 gas units.
