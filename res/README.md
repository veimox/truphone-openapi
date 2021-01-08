# Truphone TS lib

This package contains a TS library for the [Truphone API v2](https://docs.connect.truphone.com/apireference).

This package is built automatically from the project [truephone-openapi](https://github.com/veimox/truephone-openapi).

## How to build
```bash
npm install truephone

## How to use it

```ts
import { SIMCardManagementApi } from 'truphone'

let simApi = new SIMCardManagementApi();
let orderApi = new OrderManagementApi();
let productApi = new ProductCatalogueApi();
let subApi = new SubscriptionManagementApi();

simApi.getSimsV2().then(/*useme*/)

```

## References
* [How to create credentials](https://docs.connect.truphone.com/docs/authentication)
* [Truphone API v2](https://docs.connect.truphone.com/apireference)