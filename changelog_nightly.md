## Valetudo nightly (2025-08-23T02:48:46.531Z)
### Breaking Changes

- Drop ConsumableStateAttribute in favor of ValetudoConsumable entity [`ddc9918`](https://github.com/Hypfer/Valetudo/commit/ddc99180327570760299f6a627013328efe3b477)

### Features

- **ui**: Further improve UX of AI Assistant [`d575e2f`](https://github.com/Hypfer/Valetudo/commit/d575e2f31414a57d4b226d99a12edaeab3e38758)
- **ui**: Introduce Valetudo AI Assistant [`da4c8c4`](https://github.com/Hypfer/Valetudo/commit/da4c8c4040c8a5c955edba5af7cc71e1e6c16072)
- **vendor.dreame**: CameraLightControlCapability [`cefa92b`](https://github.com/Hypfer/Valetudo/commit/cefa92b8eeea6bd7bfabc2ca8de4eb49b975052b)
- **core**: CameraLightControlCapability [`994c3f9`](https://github.com/Hypfer/Valetudo/commit/994c3f97a2f651a2c4fd8673f785cba9847f0c51)
- **vendor.dreame**: MopExtensionControlCapability [`1189bd9`](https://github.com/Hypfer/Valetudo/commit/1189bd9f9c1e3f0c36917c39f075ac54c5c6c655)
- **core**: MopExtensionControlCapability [`ccc3073`](https://github.com/Hypfer/Valetudo/commit/ccc307379e97199c70519078a541a3889942f17a)

### Fixes

- **ui**: Fix ValetudoSplash showing scrollbars with some specific browser window dimensions [`47e129c`](https://github.com/Hypfer/Valetudo/commit/47e129c035ac7f046b131936f9a821c6cbea30ca)
- **ui**: Actually reading docs helps build better software [`6bec34d`](https://github.com/Hypfer/Valetudo/commit/6bec34db1cbdbf3ec3ec301ad2df8d1cc2b672e9)
- **ui**: Improve mobile UX of AI Assistant [`f6b08e6`](https://github.com/Hypfer/Valetudo/commit/f6b08e679f0953cc2e60422f7961fe08e7ceaf35)
- **ui**: Only show AppBar Subheaders when there are items for it [`453ac70`](https://github.com/Hypfer/Valetudo/commit/453ac70f53921dbe70e527530eaa995ba8553316)
- **core**: Remove ip from default config [`3746d26`](https://github.com/Hypfer/Valetudo/commit/3746d267a703af422c5793edb8644be5f5fe2d33)
- **vendor.viomi**: Remove redundant second emitMapUpdated on map reset [`f29592f`](https://github.com/Hypfer/Valetudo/commit/f29592f6efb1493c202ecd1d7e1aa1e4d9820fa5)
- **webserver**: Fetching the map should not poll the state [`81801d6`](https://github.com/Hypfer/Valetudo/commit/81801d68b57b3a6be012d431a2ee8e59d280cc38)
- **ui**: Add feedback when saving virtual restrictions [`69e47ab`](https://github.com/Hypfer/Valetudo/commit/69e47ab9be2a5794a5e786d20675a0ab7e39c5e9)

### Refactoring

- **mqtt**: Simplify segment ID validation [`649eb4e`](https://github.com/Hypfer/Valetudo/commit/649eb4e6230b03991489f113517dd4f96fa7a2a9)
- **core**: Use native crypto.randomUUID where possible [`b456a2b`](https://github.com/Hypfer/Valetudo/commit/b456a2b516b77bdb25e91d24c64868913c4bd66b)
- **core**: Move map polling orchestration logic into ValetudoRobot base class [`b12fb03`](https://github.com/Hypfer/Valetudo/commit/b12fb031361be55710c80a51e2ecf657f74af58d)

### Chores

- Return await cleanup [`89b7882`](https://github.com/Hypfer/Valetudo/commit/89b7882b90e080ad740322d7c89482da0f841177)
- Variable naming cleanup [`d67cabc`](https://github.com/Hypfer/Valetudo/commit/d67cabc51574fad608040608b03f49266ceac15d)
- spelling [`aaf0fc3`](https://github.com/Hypfer/Valetudo/commit/aaf0fc3f149b977ac492fc86ee592df75a63aee1)
