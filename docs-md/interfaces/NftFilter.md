[alchemy-sdk](../README.md) / [Exports](../modules.md) / NftFilter

# Interface: NftFilter

NFT to track on a [NftActivityWebhook](NftActivityWebhook.md) or [NftMetadataUpdateWebhook](NftMetadataUpdateWebhook.md).

## Table of contents

### Properties

- [contractAddress](NftFilter.md#contractaddress)
- [tokenId](NftFilter.md#tokenid)

## Properties

### contractAddress

• **contractAddress**: `string`

The contract address of the NFT.

#### Defined in

[src/types/types.ts:1344](https://github.com/alchemyplatform/alchemy-sdk-js/blob/873c9882/src/types/types.ts#L1344)

___

### tokenId

• `Optional` **tokenId**: [`BigNumberish`](../modules.md#bignumberish)

The token id of the NFT to track. If this field is omitted, defaults to
tracking all NFTs for the provided contract address.

#### Defined in

[src/types/types.ts:1349](https://github.com/alchemyplatform/alchemy-sdk-js/blob/873c9882/src/types/types.ts#L1349)
