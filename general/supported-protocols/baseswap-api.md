---
description: >-
  BaseSwap is an innovative protocol on base offering seamless swaps and
  liquidity options.
---

# Baseswap API

{% hint style="info" %}
You can find all available Baseswap Farming Markets by fetching

[https://api.decentri.fi/baseswap/farming/markets](https://api.decentri.fi/baseswap/farming/markets)
{% endhint %}

## Claimables

You can programmatically find out what ✨claimables✨ we currently support for **baseswap**.

{% swagger method="get" path="/baseswap/claimables" baseUrl="https://api.decentri.fi" summary="Fetch claimable markets for baseswap" %}
{% swagger-description %}

{% endswagger-description %}
{% endswagger %}

Actually fetching the claimables can be done using [the claimable api](../../api-endpoints/claimables/). You can also use the lower level api, like below:

{% swagger method="get" path="/baseswap/{address}/claimables" baseUrl="https://api.decentrri.fi" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="address" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Claimable Markets" %}
```
[
   {
      "id":"rwrd_frm_base-baseswap-0x64fcfa940f286af1261107f993189379e8d3ae1c",
      "name":"Baseswap Token earn pool reward",
      "network":{
         "name":"BASE",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
         "chainId":8453
      },
      "protocol":{
         "name":"BASESWAP",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/protocol/baseswap.png",
         "slug":"baseswap",
         "primitives":[
            "POOLING",
            "FARMING",
            "CLAIMABLES"
         ],
         "website":"https://baseswap.fi",
         "company":{
            "name":"Baseswap",
            "slug":"baseswap"
         }
      },
      "rewards":[
         {
            "token":{
               "network":{
                  "name":"BASE",
                  "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
                  "chainId":8453
               },
               "logo":"https://raw.githubusercontent.com/trustwallet/assets/master/blockchains/base/assets/0xd9aAEc86B65D86f6A7B5B1b0c42FFA531710b6CA/logo.png",
               "name":"USD Base Coin",
               "symbol":"USDbC",
               "address":"0xd9aaec86b65d86f6a7b5b1b0c42ffa531710b6ca",
               "decimals":6,
               "type":"SINGLE",
               "totalSupply":96933331840573,
               "underlyingTokens":[
                  
               ],
               "protocol":null
            }
         }
      ]
   },
   {
      "id":"rwrd_frm_base-baseswap-0x26fd5de668f091222791cc0ea45ac072d7bfe0cd",
      "name":"BaseX earn pool reward",
      "network":{
         "name":"BASE",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
         "chainId":8453
      },
      "protocol":{
         "name":"BASESWAP",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/protocol/baseswap.png",
         "slug":"baseswap",
         "primitives":[
            "POOLING",
            "FARMING",
            "CLAIMABLES"
         ],
         "website":"https://baseswap.fi",
         "company":{
            "name":"Baseswap",
            "slug":"baseswap"
         }
      },
      "rewards":[
         {
            "token":{
               "network":{
                  "name":"BASE",
                  "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
                  "chainId":8453
               },
               "logo":"https://raw.githubusercontent.com/trustwallet/assets/master/blockchains/base/assets/0x4200000000000000000000000000000000000006/logo.png",
               "name":"Wrapped Ether",
               "symbol":"WETH",
               "address":"0x4200000000000000000000000000000000000006",
               "decimals":18,
               "type":"SINGLE",
               "totalSupply":48001133545454625685239,
               "underlyingTokens":[
                  
               ],
               "protocol":null
            }
         }
      ]
   },
   {
      "id":"rwrd_frm_base-baseswap-0x326929eae4e1923b9d08de6bd8b2e16f7dd35cd4",
      "name":"Baseswap escrowed token earn pool reward",
      "network":{
         "name":"BASE",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
         "chainId":8453
      },
      "protocol":{
         "name":"BASESWAP",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/protocol/baseswap.png",
         "slug":"baseswap",
         "primitives":[
            "POOLING",
            "FARMING",
            "CLAIMABLES"
         ],
         "website":"https://baseswap.fi",
         "company":{
            "name":"Baseswap",
            "slug":"baseswap"
         }
      },
      "rewards":[
         {
            "token":{
               "network":{
                  "name":"BASE",
                  "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
                  "chainId":8453
               },
               "logo":"https://raw.githubusercontent.com/trustwallet/assets/master/blockchains/base/assets/0xd9aAEc86B65D86f6A7B5B1b0c42FFA531710b6CA/logo.png",
               "name":"USD Base Coin",
               "symbol":"USDbC",
               "address":"0xd9aaec86b65d86f6a7b5b1b0c42ffa531710b6ca",
               "decimals":6,
               "type":"SINGLE",
               "totalSupply":96933331840573,
               "underlyingTokens":[
                  
               ],
               "protocol":null
            }
         }
      ]
   },
   {
      "id":"rwrd_frm_base-baseswap-0x86dbd5baae91ac576e8e5197eb2497603d0056ea",
      "name":"Baseswap Token earn pool reward",
      "network":{
         "name":"BASE",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
         "chainId":8453
      },
      "protocol":{
         "name":"BASESWAP",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/protocol/baseswap.png",
         "slug":"baseswap",
         "primitives":[
            "POOLING",
            "FARMING",
            "CLAIMABLES"
         ],
         "website":"https://baseswap.fi",
         "company":{
            "name":"Baseswap",
            "slug":"baseswap"
         }
      },
      "rewards":[
         {
            "token":{
               "network":{
                  "name":"BASE",
                  "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
                  "chainId":8453
               },
               "logo":"https://raw.githubusercontent.com/trustwallet/assets/master/blockchains/base/assets/0x4200000000000000000000000000000000000006/logo.png",
               "name":"Wrapped Ether",
               "symbol":"WETH",
               "address":"0x4200000000000000000000000000000000000006",
               "decimals":18,
               "type":"SINGLE",
               "totalSupply":48001133545454625685239,
               "underlyingTokens":[
                  
               ],
               "protocol":null
            }
         }
      ]
   },
   {
      "id":"rwrd_frm_base-baseswap-0x71f759af413739576e0b03f1e339d3580866d2ff",
      "name":"Baseswap Token earn pool reward",
      "network":{
         "name":"BASE",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
         "chainId":8453
      },
      "protocol":{
         "name":"BASESWAP",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/protocol/baseswap.png",
         "slug":"baseswap",
         "primitives":[
            "POOLING",
            "FARMING",
            "CLAIMABLES"
         ],
         "website":"https://baseswap.fi",
         "company":{
            "name":"Baseswap",
            "slug":"baseswap"
         }
      },
      "rewards":[
         {
            "token":{
               "network":{
                  "name":"BASE",
                  "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
                  "chainId":8453
               },
               "logo":"https://raw.githubusercontent.com/trustwallet/assets/master/blockchains/base/assets/0x4200000000000000000000000000000000000006/logo.png",
               "name":"Wrapped Ether",
               "symbol":"WETH",
               "address":"0x4200000000000000000000000000000000000006",
               "decimals":18,
               "type":"SINGLE",
               "totalSupply":48001133545454625685239,
               "underlyingTokens":[
                  
               ],
               "protocol":null
            }
         }
      ]
   },
   {
      "id":"rwrd_frm_base-baseswap-0x8d52e213d741684dec1d37a6ee7814ae32942c1e",
      "name":"BaseX earn pool reward",
      "network":{
         "name":"BASE",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
         "chainId":8453
      },
      "protocol":{
         "name":"BASESWAP",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/protocol/baseswap.png",
         "slug":"baseswap",
         "primitives":[
            "POOLING",
            "FARMING",
            "CLAIMABLES"
         ],
         "website":"https://baseswap.fi",
         "company":{
            "name":"Baseswap",
            "slug":"baseswap"
         }
      },
      "rewards":[
         {
            "token":{
               "network":{
                  "name":"BASE",
                  "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
                  "chainId":8453
               },
               "logo":"https://raw.githubusercontent.com/trustwallet/assets/master/blockchains/base/assets/0x0A074378461FB7ed3300eA638c6Cc38246db4434/logo.png",
               "name":"EDE",
               "symbol":"EDE",
               "address":"0x0a074378461fb7ed3300ea638c6cc38246db4434",
               "decimals":18,
               "type":"SINGLE",
               "totalSupply":3030000000000000000000000,
               "underlyingTokens":[
                  
               ],
               "protocol":null
            }
         }
      ]
   },
   {
      "id":"rwrd_frm_base-baseswap-0x55da9a8a85d37764934a8915621baa00fafdc3eb",
      "name":"BaseX earn pool reward",
      "network":{
         "name":"BASE",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
         "chainId":8453
      },
      "protocol":{
         "name":"BASESWAP",
         "logo":"https://github.com/decentri-fi/data/raw/master/logo/protocol/baseswap.png",
         "slug":"baseswap",
         "primitives":[
            "POOLING",
            "FARMING",
            "CLAIMABLES"
         ],
         "website":"https://baseswap.fi",
         "company":{
            "name":"Baseswap",
            "slug":"baseswap"
         }
      },
      "rewards":[
         {
            "token":{
               "network":{
                  "name":"BASE",
                  "logo":"https://github.com/decentri-fi/data/raw/master/logo/network/base.png",
                  "chainId":8453
               },
               "logo":"https://raw.githubusercontent.com/trustwallet/assets/master/blockchains/base/assets/0xd9aAEc86B65D86f6A7B5B1b0c42FFA531710b6CA/logo.png",
               "name":"USD Base Coin",
               "symbol":"USDbC",
               "address":"0xd9aaec86b65d86f6a7b5b1b0c42ffa531710b6ca",
               "decimals":6,
               "type":"SINGLE",
               "totalSupply":96933331840573,
               "underlyingTokens":[
                  
               ],
               "protocol":null
            }
         }
      ]
   }
]
```
{% endswagger-response %}
{% endswagger %}

## Baseswap Checklist

<table data-header-hidden><thead><tr><th width="298">Feature</th><th>Support</th></tr></thead><tbody><tr><td>Feature</td><td>Support</td></tr><tr><td>Masterchef Markets</td><td>✅</td></tr><tr><td>Masterchef Positions</td><td>✅</td></tr><tr><td>Masterchef Claimables</td><td>✅</td></tr></tbody></table>
