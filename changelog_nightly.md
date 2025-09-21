## Valetudo nightly (2025-09-21T02:51:22.740Z)
### Breaking Changes

- Merge AutoEmptyDockAutoEmptyControlCapability into AutoEmptyDockAutoEmptyIntervalControlCapability [`7d1aea3`](https://github.com/Hypfer/Valetudo/commit/7d1aea37f772f0d9db4532420d5d8211174a0976)

### Features

- **mqtt**: Add missing deviceClass + stateClass attributes, update enums and fix units for HA [`921dd13`](https://github.com/Hypfer/Valetudo/commit/921dd13b82f384a4f186300a0fbbea45395db4b9)
- **vendor.midea**: Improve state reporting [`0afc47e`](https://github.com/Hypfer/Valetudo/commit/0afc47e9a3c17e7fdb7a8648f4fe4a0582cbfbdf)
- **vendor.midea**: MopExtensionFurnitureLegHandlingControlCapability [`7c0fc3a`](https://github.com/Hypfer/Valetudo/commit/7c0fc3a09416e665a19f79f1a2a936638c3a8111)
- **vendor.dreame**: MopExtensionFurnitureLegHandlingControlCapability [`92cd7f6`](https://github.com/Hypfer/Valetudo/commit/92cd7f6475164d3a6cd15e6a8a696aece35e9c22)
- **core**: MopExtensionFurnitureLegHandlingControlCapability [`e6615d2`](https://github.com/Hypfer/Valetudo/commit/e6615d266c4dad3fb4cf45eb6861a9ac29d6f6b1)
- **ui**: Improved MopExtension and MopTwist icons [`fd83cd3`](https://github.com/Hypfer/Valetudo/commit/fd83cd3fc5afc186dc32845029110dc106e3329b)
- **webserver**: You know the rules and so do I [`0dcca1d`](https://github.com/Hypfer/Valetudo/commit/0dcca1df2f870007738fc267932e18ef6864bbca)
- **vendor.midea**: MopTwistControlCapability [`72444e6`](https://github.com/Hypfer/Valetudo/commit/72444e6fe12275b332760a7bd5969d936f15d710)
- **vendor.dreame**: MopTwistControlCapability [`ea236ab`](https://github.com/Hypfer/Valetudo/commit/ea236abc1ea61874a5cc2b9b9e29e8bf30a6938d)
- **core**: MopTwistControlCapability [`92ee9a5`](https://github.com/Hypfer/Valetudo/commit/92ee9a5f183f53064e98744c569843ea8b0172d3)
- **vendor.midea**: Pet obstacle avoidance and stain cleaning [`0ea2a50`](https://github.com/Hypfer/Valetudo/commit/0ea2a50a4ddcdf76462559c4e0f647c3b95d1f2d)
- **vendor.midea**: Everything carpet [`f94f3c1`](https://github.com/Hypfer/Valetudo/commit/f94f3c1101bbdf764f5b51a26a6c0abe6d0c873a)
- **vendor.midea**: MopDockMopWashTemperatureControlCapability [`52c8c4b`](https://github.com/Hypfer/Valetudo/commit/52c8c4b290d8700634a1854b796f6b5973a98b22)
- **vendor.dreame**: MopDockMopWashTemperatureControlCapability [`53ff4fa`](https://github.com/Hypfer/Valetudo/commit/53ff4fa841a071a16a1427864215d60fbdce3b48)
- **core**: MopDockMopWashTemperatureControlCapability [`de62cbf`](https://github.com/Hypfer/Valetudo/commit/de62cbf8121b5e193488bf96a53d670f2719f554)
- **vendor.midea**: Auto empty controls [`ae01b69`](https://github.com/Hypfer/Valetudo/commit/ae01b6950368122678941a4deaa93be2b6d18fcb)
- **vendor.midea**: Obstacles galore [`17ebfae`](https://github.com/Hypfer/Valetudo/commit/17ebfae6a8e211018bab0e8e8a56b94ac19eeeb5)
- **ui**: Improve MopExtensionControl Icon [`757e682`](https://github.com/Hypfer/Valetudo/commit/757e6827ce54b47fcb19c6f0aa01afe556b05476)

### Fixes

- **vendor.midea**: Do not fail fast [`5715fb0`](https://github.com/Hypfer/Valetudo/commit/5715fb02f2d6b75b0e0c5e46557c0556f4c52375)
- **ui**: MopDockMopWashTemperatureControl should be a dockListItems [`493c570`](https://github.com/Hypfer/Valetudo/commit/493c57010d5cefe0eaa4ae4eefb7081eecda97bf)
- **vendor.midea**: Add missing return statement [`52b4625`](https://github.com/Hypfer/Valetudo/commit/52b462517b48ecd75abdc7c9ba68a35031e4cc5f)
- **vendor.dreame**: Fix connection timeout on startup on very recent firmwares [`15c1f80`](https://github.com/Hypfer/Valetudo/commit/15c1f801add4c7af61dc13378e30a224efb73383)
- **miio**: Fix super rare bug crashing the process [`0c6272f`](https://github.com/Hypfer/Valetudo/commit/0c6272f704c1d49e1fecf40ccc09be89e51ea03e)
- **vendor.midea**: Fail any requests instantly on initial startup [`a963fa1`](https://github.com/Hypfer/Valetudo/commit/a963fa17ee51382d4f406559e782d94c141cc3c7)
- **vendor.dreame**: Add another new modelId [`df46e2e`](https://github.com/Hypfer/Valetudo/commit/df46e2e69797851df1ae0d10b9e50c3aa21d8945)
- **vendor.dreame**: Add missing model ID [`87d0760`](https://github.com/Hypfer/Valetudo/commit/87d0760cccd364c168691de294c453fc72493b39)
- **vendor.roborock**: No-Op handle two more events [`0261f57`](https://github.com/Hypfer/Valetudo/commit/0261f57e5d696ab8671a61137972203c1207c364)
- **vendor.dreame**: Track emptying state of auto empty dock [`6f0fc2a`](https://github.com/Hypfer/Valetudo/commit/6f0fc2a4535cca3a5985f4990a6dec652895eb13)

### Refactoring

- **vendor.dreame**: Group all the ephemeral state into an object [`2fdef9f`](https://github.com/Hypfer/Valetudo/commit/2fdef9fed7eed04deb763e97c427f87b8c90d0d0)
- **vendor.midea**: Move specific capabilities into actual implementation class [`c0d1640`](https://github.com/Hypfer/Valetudo/commit/c0d1640ae3c111e615f97b10e343f2b34b085297)
- **MockRobot**: Smurf for consistency [`5d40584`](https://github.com/Hypfer/Valetudo/commit/5d405842d2bcda8ae51afe95c4e77aac7e21e232)
- **vendor.midea**: Rename implementation class for J15PU [`785e6b8`](https://github.com/Hypfer/Valetudo/commit/785e6b87cbefa661b021d14e5b6d575b3cbc7f68)

### Chores

- Fix CI [`c53dd66`](https://github.com/Hypfer/Valetudo/commit/c53dd66c6be48176163405aafc1b55212097aea0)
- **assets**: Commit working state [`b1eb76b`](https://github.com/Hypfer/Valetudo/commit/b1eb76b26af8b4da84d09fa50f289a0f1643b43f)
- **vendor.midea**: Minor cleanup [`ed34e36`](https://github.com/Hypfer/Valetudo/commit/ed34e36e4ebcb0ea2bc911743e8a5ddb13982abe)
