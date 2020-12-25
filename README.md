## How to contribute

1. Fork the repo to your account
2. Clone the repo from your own account, rather than the origin one

```
git clone git@github.com:xxxxxxxx/asset-profile.git
```

3. Create and switch to a new branch named by your token symbol
4. Add a new dir, which named by the asset_id in mixin, you can find it in [https://mixin.one/snapshots](https://mixin.one/snapshots)

```
c6d0c728-2624-429b-8e0d-d9d19b6592fa
```

To get your token asset_id within mixin network. Herewith to do asf :

- Download Mixin Messanger app ( https://mixin.one/messenger )
- After completed created pin wallet winthin Mixin Messanger. Send/deposit your token to mixin messanger wallet. If erc20 token, send your token to your ethereum address in Mixin Messanger. Once your token deposit successfully inside Mixin Messanger wallet. Klik on it and copy the transaction id.

Faste your transaction id in ( search transaction field ) at https://mixin.one/snapshots than enter. Afterward, you will be redirected to another page eq : https://mixin.one/snapshots/37568840-72ee-4b51-bbc0-16a6cfd1de99. And in the bottom of page. you will see ASSET name. Click the link below of ASSET, the result will be as example here https://mixin.one/snapshots/4d977d4e-af34-360e-ba03-f546a3f14fcb .

The random word and number ( example : 4d977d4e-af34-360e-ba03-f546a3f14fcb ). That is your token asset_id in mixin network.

5. Add a file named index.json, and fulfill the content by following the schema of `index.json`, you can get cmc_id from https://api.coinmarketcap.com/v1/ticker/?limit=0, which is `id` of the asset in coinmarketcap.
6. Add the logo named `icon.png`
7. Besides, if you find that your token has been added, you can modify the related file and logo as well
8. Commit the changes
9. Push to your own repo
10. Make a pull request with detailed description
11. We will review your PR as soon as possible, and then merge it into the master branch when everything is fine

## Requirements

### The Effectiveness of Information

You're totally responsible for your commit, so please make sure that the information and logo are real and valid.

### Logo design

- Size: 520x520 pixels.
- Image must be round and the background shouldn’t be transparent and white.
- Brand identity.
