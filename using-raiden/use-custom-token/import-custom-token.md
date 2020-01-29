---
description: >-
  The Raiden Network supports transactions of ERC20 compliant tokens. Any smart
  contract that implements the ERC20 interface can be used with Raiden.
---

# Import Custom Token

Importing the custom token is done via the [Remix Ethereum IDE](https://remix.ethereum.org/). You can read more about ERC20 tokens in [this GitHub repo](https://github.com/OpenZeppelin/openzeppelin-contracts/tree/master/contracts/token/ERC20).

![Screen for importing a custom token](../../.gitbook/assets/remix_gist_import.png)

1. Start of by getting the Solidity code for an ERC20 token from [this GitHub gist](https://gist.github.com/eorituz/a779c0277f2fc5c935e2b2f62e49da49).
2. Enter the URL for the [Remix Ethereum IDE](https://remix.ethereum.org/) in your browser.
3. Under **"Environments"** click **"Solidity"**.
4. Under **"File"** choose to import from **"Gist"**.
5. In the pop-up that appears enter the ID, _a779c0277f2fc5c935e2b2f62e49da49_, of the gist you just viewed.

If the import was successful you should be able to open the imported code from the file explorer on the left hand side menu.

