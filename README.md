## How to contribute

1. Fork the repo to your account
2. Clone the repo from your account rather than the original one

```
git clone git@github.com:xxxxxxxx/asset-profile.git
```

3. Create and switch to a new branch named by your token symbol
4. Add a new dir named by the asset_id in the mixin; you can find it at [https://mixin.one/snapshots.](https://mixin.one/snapshots)

```
c6d0c728-2624-429b-8e0d-d9d19b6592fa
```

To get your token asset_id within the mixin network. Herewith to do asf :

- Download the Mixin Messanger app ( https://mixin.one/messenger )
- After completing created pin wallet within Mixin Messanger, send/deposit your token to the Mixin Messanger wallet. If erc20 token, send your token to your Ethereum address in Mixin Messanger. Once your token deposit is successfully inside the Mixin Messanger wallet. Click on it and copy the transaction id.

Paste your transaction id in ( search transaction field ) at https://mixin.one/snapshots, then enter. Afterward, you will be redirected to another page, eq: https://mixin.one/snapshots/37568840-72ee-4b51-bbc0-16a6cfd1de99. And at the bottom of the page. You will see the ASSET name. Click the link below of ASSET; the result will be as an example here https://mixin.one/snapshots/4d977d4e-af34-360e-ba03-f546a3f14fcb.

The random word and number ( example : 4d977d4e-af34-360e-ba03-f546a3f14fcb ). That is your token asset_id in mixin network.

5. Add a file named index.json, and fulfill the content by following the schema of `index.json`, you can get the coingecko id from https://api.coingecko.com/api/v3/simple/price?ids=bitcoin&vs_currencies=usd, which is the `id` of the asset in coingecko.
6. Add the logo named `icon.png`.
7. Besides, if you find that your token has been added, you can modify the related file and logo.
8. Commit the changes.
9. Push to your repo.
10. Make a pull request with a detailed description.
11. We will review your PR as soon as possible and merge it into the master branch when everything is fine.

## Requirements

### The Effectiveness of Information

You're responsible for your commitment, so please ensure that the information and logo are authentic and valid.

### Logo design

- Size: 520x520 pixels.
- The image must be round, and the background shouldn’t be transparent and white.
- Brand identity.

### Others

- Please make sure your icon is legal and copyright.
- Token with fake name or icon will not be accepted.
