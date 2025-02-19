[coinbase-pro-node](../README.md) / [Exports](../modules.md) / Product

# Interface: Product

## Table of contents

### Properties

- [base\_currency](product.md#base_currency)
- [base\_increment](product.md#base_increment)
- [base\_max\_size](product.md#base_max_size)
- [base\_min\_size](product.md#base_min_size)
- [cancel\_only](product.md#cancel_only)
- [display\_name](product.md#display_name)
- [id](product.md#id)
- [limit\_only](product.md#limit_only)
- [margin\_enabled](product.md#margin_enabled)
- [max\_market\_funds](product.md#max_market_funds)
- [min\_market\_funds](product.md#min_market_funds)
- [post\_only](product.md#post_only)
- [quote\_currency](product.md#quote_currency)
- [quote\_increment](product.md#quote_increment)
- [status](product.md#status)
- [status\_message](product.md#status_message)
- [trading\_disabled](product.md#trading_disabled)

## Properties

### base\_currency

• **base\_currency**: *string*

Defined in: [product/ProductAPI.ts:7](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L7)

___

### base\_increment

• **base\_increment**: *string*

Defined in: [product/ProductAPI.ts:8](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L8)

___

### base\_max\_size

• **base\_max\_size**: *string*

Maximum order size

Defined in: [product/ProductAPI.ts:10](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L10)

___

### base\_min\_size

• **base\_min\_size**: *string*

Minimum order size

Defined in: [product/ProductAPI.ts:12](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L12)

___

### cancel\_only

• **cancel\_only**: *boolean*

Defined in: [product/ProductAPI.ts:13](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L13)

___

### display\_name

• **display\_name**: *string*

Defined in: [product/ProductAPI.ts:14](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L14)

___

### id

• **id**: *string*

Defined in: [product/ProductAPI.ts:15](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L15)

___

### limit\_only

• **limit\_only**: *boolean*

Defined in: [product/ProductAPI.ts:16](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L16)

___

### margin\_enabled

• **margin\_enabled**: *boolean*

Defined in: [product/ProductAPI.ts:17](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L17)

___

### max\_market\_funds

• **max\_market\_funds**: *string*

Defined in: [product/ProductAPI.ts:18](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L18)

___

### min\_market\_funds

• **min\_market\_funds**: *string*

Defined in: [product/ProductAPI.ts:19](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L19)

___

### post\_only

• **post\_only**: *boolean*

Defined in: [product/ProductAPI.ts:20](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L20)

___

### quote\_currency

• **quote\_currency**: *string*

Defined in: [product/ProductAPI.ts:21](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L21)

___

### quote\_increment

• **quote\_increment**: *string*

Increment steps for min/max order size. The order price must be a multiple of this increment (i.e. if the
increment is 0.01, order prices of 0.001 or 0.021 would be rejected).

Defined in: [product/ProductAPI.ts:26](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L26)

___

### status

• **status**: *online*

Defined in: [product/ProductAPI.ts:27](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L27)

___

### status\_message

• **status\_message**: *string*

Defined in: [product/ProductAPI.ts:28](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L28)

___

### trading\_disabled

• **trading\_disabled**: *boolean*

Defined in: [product/ProductAPI.ts:29](https://github.com/bennycode/coinbase-pro-node/blob/a54e177/src/product/ProductAPI.ts#L29)
