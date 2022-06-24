# Farming Market

```
data class StakingMarketVO(
    val id: String,
    val network: NetworkVO,
    val protocol: ProtocolVO,
    val name: String,
    val stakedToken: FungibleToken,
    val reward: List<FungibleToken>,
    val contractAddress: String,
    val vaultType: String,
    val marketSize: BigDecimal?,
    val apr: BigDecimal?,
    val prepareInvestmentSupported: Boolean
)
```
