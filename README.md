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
5. Add a file named index.json, and fulfill the content by following the schema of `index.json`, you can get cmc_id from https://api.coinmarketcap.com/v1/ticker/?limit=0, which is `id` of the asset in coinmarketcap.
6. Add the logo named `cover.png`
7. Besides, if you find that your token has been added, you can modify the related file and logo as well
8. Commit the changes
9. Push to your own repo
10. Make a pull request with detailed description
11. We will review your PR as soon as possible, and then merge it into the master branch when everything is fine

## Requirements
### The Effectiveness of Information
You're totally responsible for your commit, so please make sure that the information and logo are real and valid.

### Logo design
- Size: 520x520 pixels
- Transparent background PNG
- Brand identity
