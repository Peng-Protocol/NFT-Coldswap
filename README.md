# NFT Coldswap 
A set of new contracts designed to work alongside [NFT Hotswap](https://github.com/Peng-Protocol/NFT-Hotswap/tree/main).
## Routers 
Hotswap Routers are meant to work alongside existing CFAMM DEXs (Constant Function Automated Market Maker Decentralized Exchanges) such as QuickSwap in order to enable swapping to and from any token the user desires in exchange for or from a listed NFT, this enables swapping to or from the native blockchain token as well. 
## Coldswap Contracts
The core Coldswap contracts allow listing an NFT collection with a fungible token created by the Coldswap, the NFT items can then be swapped - at a ratio set by the deployer - with the Cold Tokens, thus fractionalizing them and allowing further liquidity on other DEXs. 
Coldswap also comes along with a marketplace for listing specific NFT items at bid/ask price, thereby allowing more speculation.
## New Frontend 
The new Hotswap frontend merges Coldswap and Hotswap as one cohesive unit, introducing search functionality that allows users to find Hotswap controllers and Coldswap listing addresses by querying the NFT's own address. Furthermore the router enables "automatic" interaction across Hotswap - Coldswap and QuickSwap. 
