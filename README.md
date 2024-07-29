# Euler Price Oracle Providers

The [Euler Vault Kit](https://github.com/euler-xyz/euler-vault-kit)(EVK) is agnostic about how assets are priced. You can read more about how to build oracle adapters to work with the EVK using any type of pricing source in the [Euler Price Oracle](https://github.com/euler-xyz/euler-price-oracle) repository. 

For convenience, however, a range of oracle adapters designed to wrap around oracles from popular providers including Chainlink, Pyth, RedStone, Chronicle, and API3, have been audited and deployed. The assets supported by these adapters across a variety of EVM-based networks are listed here:

- [Ethereum](ethereum.csv)
- [Arbitrum](arbitrum.csv)
- [Base](base.csv)

Note: these lists are subject to change at any time. 

To request support for additional price oracle providers or adapters for specific assets, please visit the Euler DAO governance [forum](forum.euler.finance).

## Disclaimer

Use at your own risk. These lists are not recommendations. Oracles vary widely in quality. It is the responsibility of vault creators to verify that the pricing system they deploy for their vaults uses secure and robust oracles. 
