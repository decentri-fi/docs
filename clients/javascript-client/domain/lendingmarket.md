# LendingMarket

```
export type LendingMarket = {
    id: string,
    name: string,
    protocol: Protocol,
    network: Network,
    token: FungibleToken,
    rate: number | null,
    poolType: string,
    marketSize: Big,
    prepareInvestmentSupported: boolean
    exitPositionSupported: boolean
    marketType: string,
    enter: Function
}
```
