# Time Locked Balance

A Sui module for depositing and protecting a `Balance<T>` to be vested over time.

Adapted from [here](https://github.com/kunalabs-io/sui-smart-contracts/tree/master/token-distribution#time-locked-balance).

| Env | Address |
| --- | ----------- |
| Mainnet | [0xbafd431cc9362367d02dc2752216782a265216af069d70a7679de5f38c0d62ca](https://suivision.xyz/package/0xbafd431cc9362367d02dc2752216782a265216af069d70a7679de5f38c0d62ca) |
| Testnet | [0x04f451eb5cf59598059452e80e9d5ebe74d88f23f72735597089d3e5ea82a1f7](https://testnet.suivision.xyz/package/0x04f451eb5cf59598059452e80e9d5ebe74d88f23f72735597089d3e5ea82a1f7) |

---

#### Usage
```toml
# Move.toml

[dependencies]
TimeLockedBalance = { git = "https://github.com/ronanyeah/time-locked-balance.git", rev = "master" }
```
