Generated with discovered.json: 0x54708d6223b5f88881066a1eb09b1249621f95f5

# Diff at Tue, 01 Oct 2024 10:54:10 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@bd754dc73c66120164006054f8d25c5fae9cd910 block: 20862639
- current block number: 20862639

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20862639 (main branch discovery), not current.

```diff
    contract ERC1155Predicate (0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f) {
    +++ description: None
      values.$pastUpgrades:
+        [["2020-08-26T10:28:42.000Z",["0x46cA157573005281774be9be9a4187cce4ec1871"]],["2020-11-18T07:48:02.000Z",["0x62D7e87677ac7e3bd02c198e3FABeFFdBc5eB2A3"]],["2024-08-25T16:11:47.000Z",["0xb86357daD9c3567dD70862a5b49fFFaFb0F094Ac"]],["2024-08-27T11:02:23.000Z",["0xCFA65db73cB45D458d0a98006d3d558b5e1F021d"]]]
      values.$upgradeCount:
+        4
    }
```

```diff
    contract MintableERC1155Predicate (0x2d641867411650cd05dB93B59964536b1ED5b1B7) {
    +++ description: None
      values.$pastUpgrades:
+        [["2021-02-12T05:32:55.000Z",["0xbf3d5d13b3Cb79A6173394046973C34A60Ac8A41"]],["2021-04-21T11:45:46.000Z",["0x62414D03084EeB269E18C970a21f45D2967F0170"]],["2021-09-26T07:01:07.000Z",["0x4c2aA63BF1d867fbAD14f1d505481c16e4862201"]],["2022-03-02T10:12:36.000Z",["0xDb161A896Be50a020B636D6B60DA7c59817412a5"]],["2024-08-25T16:11:47.000Z",["0x985Dbac75cf625dD6baB03Da784CF0D51B4bEcef"]],["2024-08-27T11:02:23.000Z",["0xFD47E7d657b07B071C3362bBCe908a70895EE747"]]]
      values.$upgradeCount:
+        6
    }
```

```diff
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf) {
    +++ description: None
      values.$pastUpgrades:
+        [["2020-08-26T10:11:21.000Z",["0xC760DefB87E5194E62b282c2a76CBCe4766d7345"]],["2020-11-18T07:48:02.000Z",["0x608669d4914Eec1E20408Bc4c9eFFf27BB8cBdE5"]],["2024-08-25T16:11:47.000Z",["0xb774EBbeF817390483FEA5bEd0F0cB0EDEBE4065"]],["2024-08-27T11:02:23.000Z",["0xB1fd4ae726c64A793588001EB465c46BD1BdF1cB"]]]
      values.$upgradeCount:
+        4
    }
```

```diff
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908) {
    +++ description: None
      values.$pastUpgrades:
+        [["2020-07-16T12:32:01.000Z",["0x9a6bC66Ce2E008D59654bc0053Ce2d01f09C8B90"]],["2020-10-27T11:43:55.000Z",["0xf58Ec2F599EC32f2aE104984F41C1fB1377ECEBa"]],["2021-03-26T16:24:09.000Z",["0xB955EE20A7F1D6F9bD68805e6EefE2cBc5d8220D"]],["2021-03-26T17:05:24.000Z",["0xd8EeB76bf9FEc7Efe3772383d5f38fd02243E56C"]],["2021-06-18T13:08:09.000Z",["0xd6F5c46d4E1a02f9D145cEe41d2F8AF30D8d2d76"]],["2022-01-26T07:47:11.000Z",["0x644A0A4a4a9892f57Af7dFF1Db23cE2A235A255e"]],["2022-11-15T16:28:23.000Z",["0xbA9Ac3C9983a3e967f0f387c75cCbD38Ad484963"]],["2024-09-04T16:31:35.000Z",["0x97a3500083348A147F419b8a65717909762c389f"]]]
      values.$upgradeCount:
+        8
    }
```

```diff
    contract EventsHub (0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b) {
    +++ description: None
      values.$pastUpgrades:
+        [["2021-03-26T16:01:24.000Z",["0x762540dB57aBdB6d32E5B5b8856986C0418A3b82"]],["2021-12-02T06:09:51.000Z",["0x0672777617CAA1E778083a4f74eBC997262C9EdD"]]]
      values.$upgradeCount:
+        2
    }
```

```diff
    contract EtherPredicate (0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30) {
    +++ description: None
      values.$pastUpgrades:
+        [["2020-08-26T10:33:28.000Z",["0xb6a508B418d49080Ce4AE4F140e585A0f95C1326"]],["2020-11-18T07:48:02.000Z",["0x499a865ac595e6167482d2bd5A224876baB85ab4"]],["2021-09-26T07:01:07.000Z",["0x54006763154c764da4AF42a8c3cfc25Ea29765D5"]],["2024-08-25T16:11:47.000Z",["0x3129B90fB7bF58A0B36226f2e6547B89C0BbdE42"]],["2024-08-27T11:02:23.000Z",["0xeB185ED8f664D105903EF434E5becd214a8AC874"]]]
      values.$upgradeCount:
+        5
    }
```

```diff
    contract MintableERC721Predicate (0x932532aA4c0174b8453839A6E44eE09Cc615F2b7) {
    +++ description: None
      values.$pastUpgrades:
+        [["2020-08-26T10:15:37.000Z",["0x3Bf44AD2e36f39572175C72C1D0Fa85933c6E0b6"]],["2020-11-18T07:48:02.000Z",["0x9b02a268fBb66Eb24AC9557DAEbA7aa6f04A89c2"]],["2021-02-24T11:40:48.000Z",["0xa0451a72f243A5173ea604B43B5F61EE76376551"]],["2021-03-12T06:45:22.000Z",["0x71A1666727Ea5A9B32C23cB09ABa29954e7a4a78"]],["2021-04-09T07:18:40.000Z",["0x58aDFa7960bf7Cf39965B46D796Fe66CD8f38283"]],["2022-11-15T05:50:59.000Z",["0x7FBd00c577cAA70318BCF1c6c11e23732823b387"]],["2024-08-25T16:11:47.000Z",["0x34AF15A166def1d89D38a70120Ea33CD8cc10C45"]],["2024-08-27T11:02:23.000Z",["0xba31389292f7EdfC7b60B937b97014b4C354689b"]]]
      values.$upgradeCount:
+        8
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      values.$pastUpgrades:
+        [["2021-02-12T03:43:02.000Z",["0xFdc26CDA2d2440d0E83CD1DeE8E8bE48405806DC"]],["2021-09-26T07:01:07.000Z",["0x0f92D459B20D21F6bf9E02056EA9165d3f78bA62"]],["2024-08-25T16:11:47.000Z",["0xab00328234bC22430c78847094A68a6836574fFB"]],["2024-08-27T11:02:23.000Z",["0x94D40724d6aA4AB313065006E4bA8CA448dcDfae"]]]
      values.$upgradeCount:
+        4
    }
```

```diff
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77) {
    +++ description: None
      values.$pastUpgrades:
+        [["2020-08-26T10:09:10.000Z",["0xD4888faB8bd39A663B63161F5eE1Eae31a25B653"]],["2020-11-18T07:48:02.000Z",["0x0BfF34272aF650632236703a3D6d8e3c133421Cb"]],["2021-01-22T18:50:08.000Z",["0x4015ccad9218b109d3339B356392C6EE8438e5d0"]],["2021-02-24T11:42:20.000Z",["0xEcFdefe1D67f93d3C154B67FD9d4ba62aB820DeA"]],["2021-04-28T11:52:47.000Z",["0x296AC8fb39279BbcFF6eDc9FddF1d2f4aEa1631b"]],["2021-08-05T09:27:28.000Z",["0x7CfA0f105a4922E89666D7D63689d9C9b1eA7a19"]],["2021-09-26T07:01:07.000Z",["0x6866FE89723713282BF6aB2fb8f03b0ee1833ABE"]],["2021-09-26T07:01:07.000Z",["0x6aBB753C1893194DE4a83c6e8B4EadFc105Fd5f5"]],["2022-08-21T07:40:43.000Z",["0x37D26DC2890b35924b40574BAc10552794771997"]],["2024-08-25T16:11:47.000Z",["0x1633012a2cB27eFBC2944f2E43b9197Bc3964359"]],["2024-08-27T11:02:23.000Z",["0x8F372f5404514cec63A3F88BAac772Cc620F2281"]]]
      values.$upgradeCount:
+        11
    }
```

```diff
    contract ChainExitERC1155Predicate (0xDB2382413bCb9c2F1B6b62B52238558266361D68) {
    +++ description: None
      values.$pastUpgrades:
+        [["2021-08-30T06:28:28.000Z",["0xf17461C73d32f7545ADfdd478a6eC5a382F5A58f"]]]
      values.$upgradeCount:
+        1
    }
```

```diff
    contract ERC721Predicate (0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD) {
    +++ description: None
      values.$pastUpgrades:
+        [["2020-08-26T10:13:28.000Z",["0x9aaae29879c95eD732babaBEa4cAe20A6D931DbB"]],["2020-11-18T07:48:02.000Z",["0xf3f08b74B63d0C008Cea903ee59b346bF1d5e4Cd"]],["2021-03-12T06:45:22.000Z",["0x637315199D6dcB7190BbfAcFB1E1cCe7f9632714"]],["2021-04-09T07:18:40.000Z",["0xB272B6D99858B0EfB079946942006727fe105201"]],["2022-05-26T10:17:23.000Z",["0xd515C8fF03eC79e7d5B3410c036f738e7f396C90"]],["2024-08-25T16:11:47.000Z",["0x9F5B43C0d6d57a76E5B24CE05E11b70C3C7eA8Ec"]],["2024-08-27T11:02:23.000Z",["0x02Bc987f54B54bf18Ca6E20a13e57508ec561072"]]]
      values.$upgradeCount:
+        7
    }
```

Generated with discovered.json: 0xc9692571aec67bd25ab9438b82272a7c15a33947

# Diff at Mon, 30 Sep 2024 09:42:21 GMT:

- author: sekuba (<sekuba@users.noreply.github.com>)
- comparing to: main@eec6993b988ab9a9f325d04da2e9717ed24ad0b9 block: 20719990
- current block number: 20862639

## Description

1 Polygon validator unstaked (removed).

## Watched changes

```diff
    contract StakingNFT (0x47Cbe25BbDB40a774cC37E1dA92d10C2C7Ec897F) {
    +++ description: None
      values.totalSupply:
-        127
+        126
    }
```

Generated with discovered.json: 0x3d35e33e8d7c7a42b99c510b19d0ecafea220295

# Diff at Tue, 10 Sep 2024 11:43:09 GMT:

- author: sekuba (<sekuba@users.noreply.github.com>)
- comparing to: main@07425576ea2ee80a2328e3024a4ec30d3118550a block: 20685291
- current block number: 20719990

## Description

Merge polygonpos and -plasma discoveries into this one.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20685291 (main branch discovery), not current.

```diff
    contract ERC1155Predicate (0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"]},"MANAGER_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"]}}
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract CustomPredicate (0x10ebE6EC94922F1c213E4C363C3BB66D4A9E9d35) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"]},"MANAGER_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"]}}
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract ERC20EscrowPredicate (0x21ada4D8A799c4b0ADF100eB597a6f1321bCD3E4) {
    +++ description: None
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract MintableERC1155Predicate (0x2d641867411650cd05dB93B59964536b1ED5b1B7) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"]},"MANAGER_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"]}}
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf) {
    +++ description: None
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract PolygonERC20MintBurnPredicate (0x436f5Ba0DCf22f991475fC7A6DE75DAAE2f40cB5) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":[]}}
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract EtherPredicate (0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30) {
    +++ description: None
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract MintableERC721Predicate (0x932532aA4c0174b8453839A6E44eE09Cc615F2b7) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"]},"MANAGER_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"]}}
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract ChainExitERC1155Predicate (0xDB2382413bCb9c2F1B6b62B52238558266361D68) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0x63ec5767F54F6943750A70eB6117EA2D9Ca77313"]},"MANAGER_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0x63ec5767F54F6943750A70eB6117EA2D9Ca77313","0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"]}}
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
    contract ERC721Predicate (0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"]},"MANAGER_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"]}}
      template:
+        "polygonposbridge/predicate"
    }
```

```diff
+   Status: CREATED
    contract WithdrawManager (0x2A88696e0fFA76bAA1338F2C74497cC013495922)
    +++ description: None
```

```diff
+   Status: CREATED
    contract DepositManager (0x401F6c983eA34274ec46f84D70b31C151321188b)
    +++ description: None
```

```diff
+   Status: CREATED
    contract RootChainInitialImplementation (0x5A09cD4601b66bc107D377AB81E0dbb5dFABaA84)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ExitNFT (0xDF74156420Bd57ab387B195ed81EcA36F9fABAca)
    +++ description: None
```

Generated with discovered.json: 0x791f279bb075629857db0e605c5766289c93b59c

# Diff at Thu, 05 Sep 2024 15:30:36 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@d01da0bcdde8e77051659c9718e449a44f5f957a block: 20669997
- current block number: 20685291

## Description

[PIP-42](https://github.com/maticnetwork/Polygon-Improvement-Proposals/blob/63c54e7cf534bed44e034fe32a05ff0fafe75a47/PIPs/PIP-42.md) is executed onchain. This upgrade adds POL as a staking token in a backwards-compatible way.

### ValidatorShare.sol
- POL compatibility via new functions like `buyVoucherPOL()` and `sellVoucher_newPOL()`
- permit compatibility (POL supports permit)

### StakeManager.sol
- POL compatibility via new functions with -POL suffix
- contract can convert POL to MATIC and vice versa within a call via the new migration contract
- `slash()` now just always reverts

## Watched changes

```diff
    contract Registry (0x33a02E6cC863D393d6Bf231B697b82F6e499cA71) {
    +++ description: None
      values.getValidatorShareAddress:
-        "0xf98864DA30a5bd657B13e70A57f5718aBf7BAB31"
+        "0x053FA9b934b83E1E0ffc7e98a41aAdc3640bB462"
    }
```

```diff
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908) {
    +++ description: None
      values.$implementation:
-        "0xbA9Ac3C9983a3e967f0f387c75cCbD38Ad484963"
+        "0x97a3500083348A147F419b8a65717909762c389f"
      values.implementation:
-        "0xbA9Ac3C9983a3e967f0f387c75cCbD38Ad484963"
+        "0x97a3500083348A147F419b8a65717909762c389f"
      values.token:
-        "0x7D1AfA7B718fb893dB30A3aBc0Cfc608AaCfeBB0"
+        "0x455e53CBB86018Ac2B8092FdCd39d8444aFFC3F6"
      values.migration:
+        "0x29e7DF7b6A1B2b07b731457f499E1696c60E2C4e"
      values.tokenMatic:
+        "0x7D1AfA7B718fb893dB30A3aBc0Cfc608AaCfeBB0"
    }
```

```diff
-   Status: DELETED
    contract ValidatorShareImpl (0xf98864DA30a5bd657B13e70A57f5718aBf7BAB31)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ValidatorShare (0x053FA9b934b83E1E0ffc7e98a41aAdc3640bB462)
    +++ description: None
```

## Source code changes

```diff
.../StakeManager/StakeManager.sol                  | 586 ++++++++++++---------
 .../ValidatorShare.sol}                            | 197 +++++--
 2 files changed, 477 insertions(+), 306 deletions(-)
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20669997 (main branch discovery), not current.

```diff
-   Status: DELETED
    contract MaticToken (0x7D1AfA7B718fb893dB30A3aBc0Cfc608AaCfeBB0)
    +++ description: None
```

Generated with discovered.json: 0x6ecd5c52754a9bec3cceb909e212d746d9013042

# Diff at Tue, 03 Sep 2024 12:18:09 GMT:

- author: Bartek Kiepuszewski (<bkiepuszewski@gmail.com>)
- comparing to: main@4aa95146cde1555bcce17311b090748c26bb20f8 block: 20632909
- current block number: 20669997

## Description

TimeLock (with zero minDelay) has been restored

## Watched changes

```diff
    contract ERC1155Predicate (0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.proxyOwner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract MintableERC1155Predicate (0x2d641867411650cd05dB93B59964536b1ED5b1B7) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.proxyOwner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.proxyOwner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.owner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract EventsHub (0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.owner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract Governance (0x6e7a5820baD6cebA8Ef5ea69c0C92EbbDAc9CE48) {
    +++ description: None
      values.owner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract EtherPredicate (0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.proxyOwner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract RootChain (0x86E4Dc95c7FBdBf52e33D563BbDB00823894C287) {
    +++ description: None
      values.owner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract MintableERC721Predicate (0x932532aA4c0174b8453839A6E44eE09Cc615F2b7) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.proxyOwner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.proxyOwner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.proxyOwner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract ERC721Predicate (0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.$admin:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
      values.proxyOwner:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
+        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
    }
```

```diff
    contract PolygonMultisig (0xFa7D2a996aC6350f4b56C043112Da0366a59b74c) {
    +++ description: None
      receivedPermissions.10:
-        {"permission":"upgrade","target":"0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"}
      receivedPermissions.9:
-        {"permission":"upgrade","target":"0xDB2382413bCb9c2F1B6b62B52238558266361D68"}
      receivedPermissions.8:
-        {"permission":"upgrade","target":"0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"}
      receivedPermissions.7:
-        {"permission":"upgrade","target":"0x9923263fA127b3d1484cFD649df8f1831c2A74e4"}
      receivedPermissions.6:
-        {"permission":"upgrade","target":"0x932532aA4c0174b8453839A6E44eE09Cc615F2b7"}
      receivedPermissions.5:
-        {"permission":"upgrade","target":"0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30"}
      receivedPermissions.4:
-        {"permission":"upgrade","target":"0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b"}
      receivedPermissions.3:
-        {"permission":"upgrade","target":"0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908"}
      receivedPermissions.2:
-        {"permission":"upgrade","target":"0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf"}
      receivedPermissions.1:
-        {"permission":"upgrade","target":"0x2d641867411650cd05dB93B59964536b1ED5b1B7"}
      receivedPermissions.0.target:
-        "0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f"
+        "0xDB2382413bCb9c2F1B6b62B52238558266361D68"
    }
```

```diff
+   Status: CREATED
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf)
    +++ description: None
```

## Source code changes

```diff
.../polygon-pos/ethereum/.flat/Timelock.sol        | 675 +++++++++++++++++++++
 1 file changed, 675 insertions(+)
```

Generated with discovered.json: 0xd48fcc3b5c0b6352327c6b5763773d9faf2bfd73

# Diff at Fri, 30 Aug 2024 07:54:44 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@6c1bd1f41fadf5f2cb1c1805b5a2c6138a3ed35a block: 20632909
- current block number: 20632909

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20632909 (main branch discovery), not current.

```diff
    contract PolygonMultisig (0xFa7D2a996aC6350f4b56C043112Da0366a59b74c) {
    +++ description: None
      receivedPermissions.10.via:
-        []
      receivedPermissions.9.via:
-        []
      receivedPermissions.8.via:
-        []
      receivedPermissions.7.via:
-        []
      receivedPermissions.6.via:
-        []
      receivedPermissions.5.via:
-        []
      receivedPermissions.4.via:
-        []
      receivedPermissions.3.via:
-        []
      receivedPermissions.2.via:
-        []
      receivedPermissions.1.via:
-        []
      receivedPermissions.0.via:
-        []
    }
```

Generated with discovered.json: 0x893b501f63dab947ae9659982771bf04d7fb29a1

# Diff at Thu, 29 Aug 2024 09:45:12 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@b4b2da50e6cfefe1b7675065f33cc39284a27e44 block: 20628344
- current block number: 20632909

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20628344 (main branch discovery), not current.

```diff
-   Status: DELETED
    contract WithdrawManager (0x2A88696e0fFA76bAA1338F2C74497cC013495922)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ExitNFT (0xDF74156420Bd57ab387B195ed81EcA36F9fABAca)
    +++ description: None
```

Generated with discovered.json: 0x662970b1bf0b32ad873da4a0f522ee69aef1a773

# Diff at Wed, 28 Aug 2024 16:41:41 GMT:

- author: Bartek Kiepuszewski (<bkiepuszewski@gmail.com>)
- comparing to: main@ec0c665426c9791ef4860f527c8da5a8193eb4c2 block: 20612504
- current block number: 20628344

## Description

Predicates changed as ABI for exits got a new parameter. Insignificant change wrt to risks

## Watched changes

```diff
    contract ERC1155Predicate (0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f) {
    +++ description: None
      values.$implementation:
-        "0xb86357daD9c3567dD70862a5b49fFFaFb0F094Ac"
+        "0xCFA65db73cB45D458d0a98006d3d558b5e1F021d"
      values.implementation:
-        "0xb86357daD9c3567dD70862a5b49fFFaFb0F094Ac"
+        "0xCFA65db73cB45D458d0a98006d3d558b5e1F021d"
    }
```

```diff
    contract MintableERC1155Predicate (0x2d641867411650cd05dB93B59964536b1ED5b1B7) {
    +++ description: None
      values.$implementation:
-        "0x985Dbac75cf625dD6baB03Da784CF0D51B4bEcef"
+        "0xFD47E7d657b07B071C3362bBCe908a70895EE747"
      values.implementation:
-        "0x985Dbac75cf625dD6baB03Da784CF0D51B4bEcef"
+        "0xFD47E7d657b07B071C3362bBCe908a70895EE747"
    }
```

```diff
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf) {
    +++ description: None
      values.$implementation:
-        "0xb774EBbeF817390483FEA5bEd0F0cB0EDEBE4065"
+        "0xB1fd4ae726c64A793588001EB465c46BD1BdF1cB"
      values.implementation:
-        "0xb774EBbeF817390483FEA5bEd0F0cB0EDEBE4065"
+        "0xB1fd4ae726c64A793588001EB465c46BD1BdF1cB"
    }
```

```diff
    contract EtherPredicate (0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30) {
    +++ description: None
      values.$implementation:
-        "0x3129B90fB7bF58A0B36226f2e6547B89C0BbdE42"
+        "0xeB185ED8f664D105903EF434E5becd214a8AC874"
      values.implementation:
-        "0x3129B90fB7bF58A0B36226f2e6547B89C0BbdE42"
+        "0xeB185ED8f664D105903EF434E5becd214a8AC874"
    }
```

```diff
    contract MintableERC721Predicate (0x932532aA4c0174b8453839A6E44eE09Cc615F2b7) {
    +++ description: None
      values.$implementation:
-        "0x34AF15A166def1d89D38a70120Ea33CD8cc10C45"
+        "0xba31389292f7EdfC7b60B937b97014b4C354689b"
      values.implementation:
-        "0x34AF15A166def1d89D38a70120Ea33CD8cc10C45"
+        "0xba31389292f7EdfC7b60B937b97014b4C354689b"
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      values.$implementation:
-        "0xab00328234bC22430c78847094A68a6836574fFB"
+        "0x94D40724d6aA4AB313065006E4bA8CA448dcDfae"
      values.implementation:
-        "0xab00328234bC22430c78847094A68a6836574fFB"
+        "0x94D40724d6aA4AB313065006E4bA8CA448dcDfae"
    }
```

```diff
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77) {
    +++ description: None
      values.$implementation:
-        "0x1633012a2cB27eFBC2944f2E43b9197Bc3964359"
+        "0x8F372f5404514cec63A3F88BAac772Cc620F2281"
      values.implementation:
-        "0x1633012a2cB27eFBC2944f2E43b9197Bc3964359"
+        "0x8F372f5404514cec63A3F88BAac772Cc620F2281"
    }
```

```diff
    contract ERC721Predicate (0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD) {
    +++ description: None
      values.$implementation:
-        "0x9F5B43C0d6d57a76E5B24CE05E11b70C3C7eA8Ec"
+        "0x02Bc987f54B54bf18Ca6E20a13e57508ec561072"
      values.implementation:
-        "0x9F5B43C0d6d57a76E5B24CE05E11b70C3C7eA8Ec"
+        "0x02Bc987f54B54bf18Ca6E20a13e57508ec561072"
    }
```

## Source code changes

```diff
.../{.flat@20612504 => .flat}/ERC1155Predicate/ERC1155Predicate.sol  | 4 ++++
 .../{.flat@20612504 => .flat}/ERC20Predicate/ERC20Predicate.sol      | 4 ++++
 .../{.flat@20612504 => .flat}/ERC721Predicate/ERC721Predicate.sol    | 4 ++++
 .../{.flat@20612504 => .flat}/EtherPredicate/EtherPredicate.sol      | 5 +++++
 .../MintableERC1155Predicate/MintableERC1155Predicate.sol            | 4 ++++
 .../MintableERC20Predicate/MintableERC20Predicate.sol                | 4 ++++
 .../MintableERC721Predicate/MintableERC721Predicate.sol              | 4 ++++
 .../{.flat@20612504 => .flat}/RootChainManager/RootChainManager.sol  | 1 +
 8 files changed, 30 insertions(+)
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20612504 (main branch discovery), not current.

```diff
    contract ERC1155Predicate (0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract MintableERC1155Predicate (0x2d641867411650cd05dB93B59964536b1ED5b1B7) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract EventsHub (0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract EtherPredicate (0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract MintableERC721Predicate (0x932532aA4c0174b8453839A6E44eE09Cc615F2b7) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract ChainExitERC1155Predicate (0xDB2382413bCb9c2F1B6b62B52238558266361D68) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract ERC721Predicate (0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xFa7D2a996aC6350f4b56C043112Da0366a59b74c","via":[]}]
    }
```

```diff
    contract PolygonMultisig (0xFa7D2a996aC6350f4b56C043112Da0366a59b74c) {
    +++ description: None
      assignedPermissions:
-        {"upgrade":["0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f","0x2d641867411650cd05dB93B59964536b1ED5b1B7","0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf","0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908","0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b","0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30","0x932532aA4c0174b8453839A6E44eE09Cc615F2b7","0x9923263fA127b3d1484cFD649df8f1831c2A74e4","0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","0xDB2382413bCb9c2F1B6b62B52238558266361D68","0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"]}
      receivedPermissions:
+        [{"permission":"upgrade","target":"0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f","via":[]},{"permission":"upgrade","target":"0x2d641867411650cd05dB93B59964536b1ED5b1B7","via":[]},{"permission":"upgrade","target":"0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf","via":[]},{"permission":"upgrade","target":"0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908","via":[]},{"permission":"upgrade","target":"0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b","via":[]},{"permission":"upgrade","target":"0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30","via":[]},{"permission":"upgrade","target":"0x932532aA4c0174b8453839A6E44eE09Cc615F2b7","via":[]},{"permission":"upgrade","target":"0x9923263fA127b3d1484cFD649df8f1831c2A74e4","via":[]},{"permission":"upgrade","target":"0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","via":[]},{"permission":"upgrade","target":"0xDB2382413bCb9c2F1B6b62B52238558266361D68","via":[]},{"permission":"upgrade","target":"0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD","via":[]}]
    }
```

Generated with discovered.json: 0x56953e56a39e1e3fb701ecb601d4eda075c91bb0

# Diff at Mon, 26 Aug 2024 11:36:43 GMT:

- author: Bartek Kiepuszewski (<bkiepuszewski@gmail.com>)
- comparing to: main@c6cddecec9c1434aa3f47c8b7a73acab7954bc66 block: 20532676
- current block number: 20612504

## Description

- Timlock has been removed - now Polygon MultiSig is a direct owner
- ERC20PredicateBurnOnly and ERC1155Predicate contracts have been replaced
  by new implementation. We don't track these as escrows (they are burn-only)
  so ignored
- WithdrawManager is only used by the Plasma bridge, so its implementation
  upgrade is ignored here

## Watched changes

```diff
    contract ERC1155Predicate (0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.$implementation:
-        "0x62D7e87677ac7e3bd02c198e3FABeFFdBc5eB2A3"
+        "0xb86357daD9c3567dD70862a5b49fFFaFb0F094Ac"
      values.implementation:
-        "0x62D7e87677ac7e3bd02c198e3FABeFFdBc5eB2A3"
+        "0xb86357daD9c3567dD70862a5b49fFFaFb0F094Ac"
      values.proxyOwner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
-   Status: DELETED
    contract ERC20PredicateBurnOnly (0x158d5fa3Ef8e4dDA8a5367deCF76b94E7efFCe95)
    +++ description: None
```

```diff
    contract WithdrawManager (0x2A88696e0fFA76bAA1338F2C74497cC013495922) {
    +++ description: None
      values.$implementation:
-        "0x4ef5123a30e4CFeC02B3E2F5Ce97F1328B29f7de"
+        "0xA376680d32Cece9756D9f1087318400DA2fd83dF"
      values.implementation:
-        "0x4ef5123a30e4CFeC02B3E2F5Ce97F1328B29f7de"
+        "0xA376680d32Cece9756D9f1087318400DA2fd83dF"
      values.owner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract MintableERC1155Predicate (0x2d641867411650cd05dB93B59964536b1ED5b1B7) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.$implementation:
-        "0xDb161A896Be50a020B636D6B60DA7c59817412a5"
+        "0x985Dbac75cf625dD6baB03Da784CF0D51B4bEcef"
      values.implementation:
-        "0xDb161A896Be50a020B636D6B60DA7c59817412a5"
+        "0x985Dbac75cf625dD6baB03Da784CF0D51B4bEcef"
      values.proxyOwner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract Registry (0x33a02E6cC863D393d6Bf231B697b82F6e499cA71) {
    +++ description: None
      values.erc20Predicate:
-        "0x158d5fa3Ef8e4dDA8a5367deCF76b94E7efFCe95"
+        "0x626fb210bf50e201ED62cA2705c16DE2a53DC966"
      values.erc721Predicate:
-        "0x54150f44c785D412Ec262fe895Cc3B689c72F49B"
+        "0x36C2503d53C6948331144b85D1e74a3B96731d1b"
    }
```

```diff
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.$implementation:
-        "0x608669d4914Eec1E20408Bc4c9eFFf27BB8cBdE5"
+        "0xb774EBbeF817390483FEA5bEd0F0cB0EDEBE4065"
      values.implementation:
-        "0x608669d4914Eec1E20408Bc4c9eFFf27BB8cBdE5"
+        "0xb774EBbeF817390483FEA5bEd0F0cB0EDEBE4065"
      values.proxyOwner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
-   Status: DELETED
    contract ERC721PredicateBurnOnly (0x54150f44c785D412Ec262fe895Cc3B689c72F49B)
    +++ description: None
```

```diff
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.owner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract EventsHub (0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.owner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract Governance (0x6e7a5820baD6cebA8Ef5ea69c0C92EbbDAc9CE48) {
    +++ description: None
      values.owner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract EtherPredicate (0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.$implementation:
-        "0x54006763154c764da4AF42a8c3cfc25Ea29765D5"
+        "0x3129B90fB7bF58A0B36226f2e6547B89C0BbdE42"
      values.implementation:
-        "0x54006763154c764da4AF42a8c3cfc25Ea29765D5"
+        "0x3129B90fB7bF58A0B36226f2e6547B89C0BbdE42"
      values.proxyOwner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract RootChain (0x86E4Dc95c7FBdBf52e33D563BbDB00823894C287) {
    +++ description: None
      values.owner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract MintableERC721Predicate (0x932532aA4c0174b8453839A6E44eE09Cc615F2b7) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.$implementation:
-        "0x7FBd00c577cAA70318BCF1c6c11e23732823b387"
+        "0x34AF15A166def1d89D38a70120Ea33CD8cc10C45"
      values.implementation:
-        "0x7FBd00c577cAA70318BCF1c6c11e23732823b387"
+        "0x34AF15A166def1d89D38a70120Ea33CD8cc10C45"
      values.proxyOwner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.TRANSFER_WITH_METADATA_EVENT_SIG:
+        "0xf94915c6d1fd521cee85359239227480c7e8776d7caf1fc3bacad5c269b66a14"
      values.WITHDRAW_BATCH_EVENT_SIG:
+        "0xf871896b17e9cb7a64941c62c188a4f5c621b86800e3d15452ece01ce56073df"
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.$implementation:
-        "0x0f92D459B20D21F6bf9E02056EA9165d3f78bA62"
+        "0xab00328234bC22430c78847094A68a6836574fFB"
      values.implementation:
-        "0x0f92D459B20D21F6bf9E02056EA9165d3f78bA62"
+        "0xab00328234bC22430c78847094A68a6836574fFB"
      values.proxyOwner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.$implementation:
-        "0x37D26DC2890b35924b40574BAc10552794771997"
+        "0x1633012a2cB27eFBC2944f2E43b9197Bc3964359"
      values.implementation:
-        "0x37D26DC2890b35924b40574BAc10552794771997"
+        "0x1633012a2cB27eFBC2944f2E43b9197Bc3964359"
      values.proxyOwner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
-   Status: DELETED
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf)
    +++ description: None
```

```diff
    contract ChainExitERC1155Predicate (0xDB2382413bCb9c2F1B6b62B52238558266361D68) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.proxyOwner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract ERC721Predicate (0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD) {
    +++ description: None
      values.$admin:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.$implementation:
-        "0xd515C8fF03eC79e7d5B3410c036f738e7f396C90"
+        "0x9F5B43C0d6d57a76E5B24CE05E11b70C3C7eA8Ec"
      values.implementation:
-        "0xd515C8fF03eC79e7d5B3410c036f738e7f396C90"
+        "0x9F5B43C0d6d57a76E5B24CE05E11b70C3C7eA8Ec"
      values.proxyOwner:
-        "0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

```diff
    contract PolygonMultisig (0xFa7D2a996aC6350f4b56C043112Da0366a59b74c) {
    +++ description: None
      assignedPermissions:
+        {"upgrade":["0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f","0x2d641867411650cd05dB93B59964536b1ED5b1B7","0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf","0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908","0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b","0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30","0x932532aA4c0174b8453839A6E44eE09Cc615F2b7","0x9923263fA127b3d1484cFD649df8f1831c2A74e4","0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","0xDB2382413bCb9c2F1B6b62B52238558266361D68","0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"]}
    }
```

```diff
+   Status: CREATED
    contract ERC721PredicateBurnOnly (0x36C2503d53C6948331144b85D1e74a3B96731d1b)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ERC20PredicateBurnOnly (0x626fb210bf50e201ED62cA2705c16DE2a53DC966)
    +++ description: None
```

## Source code changes

```diff
.../ERC1155Predicate/ERC1155Predicate.sol          | 338 +++++++----
 .../ERC20Predicate/ERC20Predicate.sol              | 331 ++++++----
 .../ERC20PredicateBurnOnly.sol                     | 248 ++++----
 .../ERC721Predicate/ERC721Predicate.sol            |  23 +-
 .../ERC721PredicateBurnOnly.sol                    | 248 ++++----
 .../EtherPredicate/EtherPredicate.sol              |  17 +-
 .../MintableERC1155Predicate.sol                   |  39 +-
 .../MintableERC20Predicate.sol                     |  25 +-
 .../MintableERC721Predicate.sol                    | 142 ++++-
 .../RootChainManager/RootChainManager.sol          |  51 +-
 .../.flat@20532676/Timelock.sol => /dev/null       | 675 ---------------------
 .../WithdrawManager/WithdrawManager.sol            | 250 ++++----
 12 files changed, 1112 insertions(+), 1275 deletions(-)
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20532676 (main branch discovery), not current.

```diff
    contract ERC1155Predicate (0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract MintableERC1155Predicate (0x2d641867411650cd05dB93B59964536b1ED5b1B7) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract EventsHub (0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract EtherPredicate (0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract MintableERC721Predicate (0x932532aA4c0174b8453839A6E44eE09Cc615F2b7) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf) {
    +++ description: None
      receivedPermissions:
-        [{"permission":"upgrade","target":"0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f","via":[]},{"permission":"upgrade","target":"0x2d641867411650cd05dB93B59964536b1ED5b1B7","via":[]},{"permission":"upgrade","target":"0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf","via":[]},{"permission":"upgrade","target":"0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908","via":[]},{"permission":"upgrade","target":"0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b","via":[]},{"permission":"upgrade","target":"0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30","via":[]},{"permission":"upgrade","target":"0x932532aA4c0174b8453839A6E44eE09Cc615F2b7","via":[]},{"permission":"upgrade","target":"0x9923263fA127b3d1484cFD649df8f1831c2A74e4","via":[]},{"permission":"upgrade","target":"0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","via":[]},{"permission":"upgrade","target":"0xDB2382413bCb9c2F1B6b62B52238558266361D68","via":[]},{"permission":"upgrade","target":"0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD","via":[]}]
      assignedPermissions:
+        {"upgrade":["0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f","0x2d641867411650cd05dB93B59964536b1ED5b1B7","0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf","0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908","0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b","0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30","0x932532aA4c0174b8453839A6E44eE09Cc615F2b7","0x9923263fA127b3d1484cFD649df8f1831c2A74e4","0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","0xDB2382413bCb9c2F1B6b62B52238558266361D68","0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"]}
    }
```

```diff
    contract ChainExitERC1155Predicate (0xDB2382413bCb9c2F1B6b62B52238558266361D68) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract ERC721Predicate (0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

Generated with discovered.json: 0x01458911ac13541e146efb27aa563c6ac7b285d0

# Diff at Wed, 21 Aug 2024 10:05:04 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@2f6dde3357bf5d79196b6e94f79d853a6c4ec72b block: 20532676
- current block number: 20532676

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20532676 (main branch discovery), not current.

```diff
    contract ERC1155Predicate (0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract MintableERC1155Predicate (0x2d641867411650cd05dB93B59964536b1ED5b1B7) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract EventsHub (0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract EtherPredicate (0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract MintableERC721Predicate (0x932532aA4c0174b8453839A6E44eE09Cc615F2b7) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf) {
    +++ description: None
      assignedPermissions:
-        {"upgrade":["0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f","0x2d641867411650cd05dB93B59964536b1ED5b1B7","0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf","0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908","0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b","0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30","0x932532aA4c0174b8453839A6E44eE09Cc615F2b7","0x9923263fA127b3d1484cFD649df8f1831c2A74e4","0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","0xDB2382413bCb9c2F1B6b62B52238558266361D68","0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"]}
      receivedPermissions:
+        [{"permission":"upgrade","target":"0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f","via":[]},{"permission":"upgrade","target":"0x2d641867411650cd05dB93B59964536b1ED5b1B7","via":[]},{"permission":"upgrade","target":"0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf","via":[]},{"permission":"upgrade","target":"0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908","via":[]},{"permission":"upgrade","target":"0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b","via":[]},{"permission":"upgrade","target":"0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30","via":[]},{"permission":"upgrade","target":"0x932532aA4c0174b8453839A6E44eE09Cc615F2b7","via":[]},{"permission":"upgrade","target":"0x9923263fA127b3d1484cFD649df8f1831c2A74e4","via":[]},{"permission":"upgrade","target":"0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","via":[]},{"permission":"upgrade","target":"0xDB2382413bCb9c2F1B6b62B52238558266361D68","via":[]},{"permission":"upgrade","target":"0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD","via":[]}]
    }
```

```diff
    contract ChainExitERC1155Predicate (0xDB2382413bCb9c2F1B6b62B52238558266361D68) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

```diff
    contract ERC721Predicate (0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf","via":[]}]
    }
```

Generated with discovered.json: 0x364bd3d2dcb91f84b0d8b117701e0b905c60133f

# Diff at Fri, 09 Aug 2024 12:01:26 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@bf40aa32f030fd312056ca0ef198c8550467d1d7 block: 20476663
- current block number: 20476663

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20476663 (main branch discovery), not current.

```diff
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf) {
    +++ description: None
      assignedPermissions.upgrade.10:
-        "0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b"
+        "0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"
      assignedPermissions.upgrade.9:
-        "0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908"
+        "0xDB2382413bCb9c2F1B6b62B52238558266361D68"
      assignedPermissions.upgrade.8:
-        "0x932532aA4c0174b8453839A6E44eE09Cc615F2b7"
+        "0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"
      assignedPermissions.upgrade.7:
-        "0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"
+        "0x9923263fA127b3d1484cFD649df8f1831c2A74e4"
      assignedPermissions.upgrade.6:
-        "0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f"
+        "0x932532aA4c0174b8453839A6E44eE09Cc615F2b7"
      assignedPermissions.upgrade.5:
-        "0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf"
+        "0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30"
      assignedPermissions.upgrade.4:
-        "0xDB2382413bCb9c2F1B6b62B52238558266361D68"
+        "0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b"
      assignedPermissions.upgrade.3:
-        "0x2d641867411650cd05dB93B59964536b1ED5b1B7"
+        "0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908"
      assignedPermissions.upgrade.2:
-        "0x9923263fA127b3d1484cFD649df8f1831c2A74e4"
+        "0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf"
      assignedPermissions.upgrade.1:
-        "0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30"
+        "0x2d641867411650cd05dB93B59964536b1ED5b1B7"
      assignedPermissions.upgrade.0:
-        "0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"
+        "0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f"
    }
```

Generated with discovered.json: 0xaacfa15e83d69426247c4a4ffb59e3c243023805

# Diff at Fri, 09 Aug 2024 10:11:28 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@1f0da1d0aab7bc6b3b5e54e7e93480bd98e57035 block: 20476663
- current block number: 20476663

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20476663 (main branch discovery), not current.

```diff
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf) {
    +++ description: None
      assignedPermissions.admin:
-        ["0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f","0x2d641867411650cd05dB93B59964536b1ED5b1B7","0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf","0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908","0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b","0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30","0x932532aA4c0174b8453839A6E44eE09Cc615F2b7","0x9923263fA127b3d1484cFD649df8f1831c2A74e4","0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","0xDB2382413bCb9c2F1B6b62B52238558266361D68","0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"]
      assignedPermissions.upgrade:
+        ["0xA0c68C638235ee32657e8f720a23ceC1bFc77C77","0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30","0x9923263fA127b3d1484cFD649df8f1831c2A74e4","0x2d641867411650cd05dB93B59964536b1ED5b1B7","0xDB2382413bCb9c2F1B6b62B52238558266361D68","0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf","0x0B9020d4E32990D67559b1317c7BF0C15D6EB88f","0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD","0x932532aA4c0174b8453839A6E44eE09Cc615F2b7","0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908","0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b"]
    }
```

```diff
    contract PolygonMultisig (0xFa7D2a996aC6350f4b56C043112Da0366a59b74c) {
    +++ description: None
      values.$multisigThreshold:
-        "5 of 9 (56%)"
      values.getOwners:
-        ["0xA7499Aa6464c078EeB940da2fc95C6aCd010c3Cc","0x1aE033D45ce93bbB0dDBF71a0Da9de01FeFD8529","0x0D2600C228D9Bcc9757B64bBb232F86A912B7b03","0xD0FD9303fe99EdFAF5eD4A2c1657a347d8053C9a","0x39415255619783A2E71fcF7d8f708A951d92e1b6","0xb771380f912E4b5F6beDdf81314C383c13F16ab5","0x803B74766D8f79195D4DaeCF6f2aac31Dba78F25","0x80D63799b1e08a80f73FB7a83264b5c31600bF3a","0x8Eab5aEfe2755E1bAD2052944Ea096AEbdA1d602"]
      values.getThreshold:
-        5
      values.$members:
+        ["0xA7499Aa6464c078EeB940da2fc95C6aCd010c3Cc","0x1aE033D45ce93bbB0dDBF71a0Da9de01FeFD8529","0x0D2600C228D9Bcc9757B64bBb232F86A912B7b03","0xD0FD9303fe99EdFAF5eD4A2c1657a347d8053C9a","0x39415255619783A2E71fcF7d8f708A951d92e1b6","0xb771380f912E4b5F6beDdf81314C383c13F16ab5","0x803B74766D8f79195D4DaeCF6f2aac31Dba78F25","0x80D63799b1e08a80f73FB7a83264b5c31600bF3a","0x8Eab5aEfe2755E1bAD2052944Ea096AEbdA1d602"]
      values.$threshold:
+        5
      values.multisigThreshold:
+        "5 of 9 (56%)"
    }
```

Generated with discovered.json: 0xfe133444b6608c15f9e11dfb4d0676627004fd3b

# Diff at Wed, 07 Aug 2024 12:22:45 GMT:

- author: Bartek Kiepuszewski (<bkiepuszewski@gmail.com>)
- comparing to: main@048ee50ddf07f7a442b6e0eff57ad2af666cf872 block: 20175273
- current block number: 20476663

## Description

Provide description of changes. This section will be preserved.

## Watched changes

```diff
    contract StakingNFT (0x47Cbe25BbDB40a774cC37E1dA92d10C2C7Ec897F) {
    +++ description: None
      values.totalSupply:
-        126
+        127
    }
```

```diff
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908) {
    +++ description: None
      values.NFTCounter:
-        174
+        175
      values.totalHeimdallFee:
-        "10101939209428901681108"
+        "10132939209428901681108"
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      values.accessControl.DEFAULT_ADMIN_ROLE.members.1:
-        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.accessControl.DEFAULT_ADMIN_ROLE.members.0:
-        "0x63ec5767F54F6943750A70eB6117EA2D9Ca77313"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
      values.accessControl.MANAGER_ROLE.members.1:
-        "0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"
      values.accessControl.MANAGER_ROLE.members.0:
-        "0x63ec5767F54F6943750A70eB6117EA2D9Ca77313"
+        "0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"
    }
```

```diff
    contract StakingInfo (0xa59C847Bd5aC0172Ff4FE912C5d29E5A71A7512B) {
    +++ description: None
      values.owner:
-        "0xA2D9846c352cA61dCb20D6AaD40Cec1d1b228a78"
+        "0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"
    }
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20175273 (main branch discovery), not current.

```diff
    contract ERC20EscrowPredicate (0x21ada4D8A799c4b0ADF100eB597a6f1321bCD3E4) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":[]}}
    }
```

```diff
    contract PolygonERC20MintBurnPredicate (0x436f5Ba0DCf22f991475fC7A6DE75DAAE2f40cB5) {
    +++ description: None
      name:
-        "ERC20MintBurnPredicate"
+        "PolygonERC20MintBurnPredicate"
    }
```

```diff
    contract EtherPredicate (0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"]},"MANAGER_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"]}}
    }
```

```diff
    contract RootChain (0x86E4Dc95c7FBdBf52e33D563BbDB00823894C287) {
    +++ description: None
      values.constructorArgs:
+        {"_proxyTo":"0x5A09cD4601b66bc107D377AB81E0dbb5dFABaA84","_registry":"0x33a02E6cC863D393d6Bf231B697b82F6e499cA71","_heimdallId":"heimdall-137"}
    }
```

```diff
    contract MintableERC721Predicate (0x932532aA4c0174b8453839A6E44eE09Cc615F2b7) {
    +++ description: None
      name:
-        "UnstoppableDomainsPredicate"
+        "MintableERC721Predicate"
    }
```

```diff
    contract MintableERC20Predicate (0x9923263fA127b3d1484cFD649df8f1831c2A74e4) {
    +++ description: None
      values.accessControl:
+        {"DEFAULT_ADMIN_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0x63ec5767F54F6943750A70eB6117EA2D9Ca77313","0xFa7D2a996aC6350f4b56C043112Da0366a59b74c"]},"MANAGER_ROLE":{"adminRole":"DEFAULT_ADMIN_ROLE","members":["0x63ec5767F54F6943750A70eB6117EA2D9Ca77313","0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"]}}
    }
```

```diff
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf) {
    +++ description: None
      assignedPermissions.admin.10:
+        "0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"
      assignedPermissions.admin.9:
+        "0xDB2382413bCb9c2F1B6b62B52238558266361D68"
      assignedPermissions.admin.8:
-        "0xE6F45376f64e1F568BD1404C155e5fFD2F80F7AD"
+        "0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"
      assignedPermissions.admin.7:
-        "0xDB2382413bCb9c2F1B6b62B52238558266361D68"
+        "0x9923263fA127b3d1484cFD649df8f1831c2A74e4"
      assignedPermissions.admin.6:
-        "0xA0c68C638235ee32657e8f720a23ceC1bFc77C77"
+        "0x932532aA4c0174b8453839A6E44eE09Cc615F2b7"
      assignedPermissions.admin.5:
-        "0x9923263fA127b3d1484cFD649df8f1831c2A74e4"
+        "0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30"
      assignedPermissions.admin.4:
-        "0x932532aA4c0174b8453839A6E44eE09Cc615F2b7"
+        "0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b"
      assignedPermissions.admin.3:
-        "0x8484Ef722627bf18ca5Ae6BcF031c23E6e922B30"
+        "0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908"
    }
```

```diff
+   Status: CREATED
    contract SlashingManager (0x01F645DcD6C796F6BC6C982159B32fAaaebdC96A)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ERC20PredicateBurnOnly (0x158d5fa3Ef8e4dDA8a5367deCF76b94E7efFCe95)
    +++ description: None
```

```diff
+   Status: CREATED
    contract WithdrawManager (0x2A88696e0fFA76bAA1338F2C74497cC013495922)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Registry (0x33a02E6cC863D393d6Bf231B697b82F6e499cA71)
    +++ description: None
```

```diff
+   Status: CREATED
    contract StakingNFT (0x47Cbe25BbDB40a774cC37E1dA92d10C2C7Ec897F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ERC721PredicateBurnOnly (0x54150f44c785D412Ec262fe895Cc3B689c72F49B)
    +++ description: None
```

```diff
+   Status: CREATED
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908)
    +++ description: None
```

```diff
+   Status: CREATED
    contract EventsHub (0x6dF5CB08d3f0193C768C8A01f42ac4424DC5086b)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Governance (0x6e7a5820baD6cebA8Ef5ea69c0C92EbbDAc9CE48)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MaticToken (0x7D1AfA7B718fb893dB30A3aBc0Cfc608AaCfeBB0)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MaticWETH (0xa45b966996374E9e65ab991C6FE4Bfce3a56DDe8)
    +++ description: None
```

```diff
+   Status: CREATED
    contract StakingInfo (0xa59C847Bd5aC0172Ff4FE912C5d29E5A71A7512B)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ValidatorShareFactory (0xc4FA447A0e77Eff9717b09C057B40570813bb642)
    +++ description: None
```

```diff
+   Status: CREATED
    contract  (0xD9c7C4ED4B66858301D0cb28Cc88bf655Fe34861)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ExitNFT (0xDF74156420Bd57ab387B195ed81EcA36F9fABAca)
    +++ description: None
```

```diff
+   Status: CREATED
    contract StakeManagerExtension (0xef49Ea6996073752b6840CDA34773FFA78F78166)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ValidatorShareImpl (0xf98864DA30a5bd657B13e70A57f5718aBf7BAB31)
    +++ description: None
```

Generated with discovered.json: 0x84a918c8ec832eda854b0e2559e0f0fc7b33ca2f

# Diff at Wed, 26 Jun 2024 10:30:17 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@cb9200e010745e10244c0b3851b3acf21fe41f31 block: 19532088
- current block number: 20175273

## Description

The implementation of the GnosisSafe is upgraded to version 1.3.0.

## Watched changes

```diff
    contract PolygonMultisig (0xFa7D2a996aC6350f4b56C043112Da0366a59b74c) {
    +++ description: None
      upgradeability.masterCopy:
-        "0x34CfAC646f301356fAa8B21e94227e3583Fe3F5F"
+        "0xd9Db270c1B5E3Bd161E8c8503c55cEABeE709552"
      implementations.0:
-        "0x34CfAC646f301356fAa8B21e94227e3583Fe3F5F"
+        "0xd9Db270c1B5E3Bd161E8c8503c55cEABeE709552"
      values.domainSeparator:
-        "0x3bc292918071cc597c13d3994268d3c83097b8388d750481c8cbce67a284ed5c"
+        "0x1fedebc30994a7dba640edeed88b9bdc774c9f02b3797c8a6d3a2f17399477f4"
      values.getModules:
-        []
      values.NAME:
-        "Gnosis Safe"
      values.VERSION:
-        "1.1.1"
+        "1.3.0"
      values.getChainId:
+        1
    }
```

## Source code changes

```diff
.../PolygonMultisig/GnosisSafe.sol                 | 932 ++++++++++-----------
 1 file changed, 463 insertions(+), 469 deletions(-)
```

Generated with discovered.json: 0xc189443ef5863f0d6d62094fa2495d76a066f101

# Diff at Thu, 28 Mar 2024 10:43:30 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@dd32bb06b292cc8459fb09925454ee3a90f5c27e block: 17770180
- current block number: 19532088

## Description

Update discovery to include the multisig threshold.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 17770180 (main branch discovery), not current.

```diff
    contract PolygonMultisig (0xFa7D2a996aC6350f4b56C043112Da0366a59b74c) {
    +++ description: None
      upgradeability.threshold:
+        "5 of 9 (56%)"
    }
```

Generated with discovered.json: 0xacd709a0779fdac120b133ad8ef7a45438d5ed12
