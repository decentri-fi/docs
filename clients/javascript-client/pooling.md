# Pooling

### List markets by protocol

In order to list all lending markets for a specific protocol the following code can be used. The return value is of type **Array\<PoolingMarket>.**&#x20;

{% hint style="info" %}
If the protocol does not support pooling markets, an empty array will be returned.
{% endhint %}

```
import defitrack from "@defitrack/js-client";

const markets = await defitrack.pooling().markets("balancer")
```


