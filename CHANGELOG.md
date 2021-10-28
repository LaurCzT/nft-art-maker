### [2.1.0](https://github.com/juliancwirko/create-harold-app/releases/tag/v2.1.0) (2021-10-28)
- bring back `shuffleLayerConfigurations` it has a valid use case even if we wan't only basic fuctionality
- fix for preview generation

### [2.0.0](https://github.com/juliancwirko/create-harold-app/releases/tag/v2.0.0) (2021-10-23)
- changes in the output JSON file
- replace sha1 with sha256, which is now also used for provenance hash
- there will be a possibility to download the image (PNG or SVG) and validate the sha256 hash. You can save this hash on a blockchain with other info like block number and timestamp etc.
- there will also be a possibility to validate provenance hash (hash of hashes)
- it can still get breaking changes in the future. In such a case, there will always be a major version

### [1.0.1](https://github.com/juliancwirko/create-harold-app/releases/tag/v1.0.1) (2021-10-17)
- initial code