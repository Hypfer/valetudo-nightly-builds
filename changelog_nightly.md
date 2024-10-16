## Valetudo nightly (2024-10-18T02:45:35.808Z)

### Features

- **vendor.dreame**: D10s Pro/Plus also support Obstacle Images [`63279c4`](https://github.com/Hypfer/Valetudo/commit/63279c44a0362e8b75e9729c63c655a6d7863089)
- **vendor.dreame**: Add quirk for triggering the mop dock cleaning procedure [`76280bd`](https://github.com/Hypfer/Valetudo/commit/76280bdfc6c75bdfb6a6be72c53e631a35b60f8c)
- **vendor.dreame**: ObstacleImagesCapability [`67ee71c`](https://github.com/Hypfer/Valetudo/commit/67ee71ce58528e78eb0664f4980ede54f5625b28)
- **ui**: ObstacleImagesCapability [`30b5fc8`](https://github.com/Hypfer/Valetudo/commit/30b5fc8a3d248e16c7868d3343688632a4ca3435)
- **core**: ObstacleImagesCapability [`f9fa9d0`](https://github.com/Hypfer/Valetudo/commit/f9fa9d0b6027ae188fe219faa5b24e9ae840bfa1)
- Display the actual CPU usage instead of the system load [`d0f754b`](https://github.com/Hypfer/Valetudo/commit/d0f754bc1029b10859648980349fb5bfacb21505)
- **ui**: Draw half-transparent path in virtual restrictions edit map to make placing restrictions correctly easier [`ca077b6`](https://github.com/Hypfer/Valetudo/commit/ca077b66c345599293b721afadf40444945838b9)

### Fixes

- **ui**: Fix zoom level after zooming in and back out again not ending up where it started [`2e5a9c2`](https://github.com/Hypfer/Valetudo/commit/2e5a9c20bcdb19e43fecb5a62c99027c8dcaf734)
- **vendor.dreame**: Fix MopDockCleanManualTriggerCapability for everything that is not a pure mop [`3513cbc`](https://github.com/Hypfer/Valetudo/commit/3513cbc698cdc27fee86c9dda12f0f98e5eba957)
- **webserver**: Valetudo router rate limits should be global [`7a6eb1e`](https://github.com/Hypfer/Valetudo/commit/7a6eb1ee0b85bbafd7776d513b505ba2f01f1dd1)
- **vendor.dreame**: Fix Mop Dock Water Heater quirk [`20917a7`](https://github.com/Hypfer/Valetudo/commit/20917a705691586f369e511d9eeb3e560335ba58)
- A config reset should not reset the robot config [`28d674f`](https://github.com/Hypfer/Valetudo/commit/28d674f4e5d3dcda97807c855c018c35e1f7f9bb)
- **ui**: Fix cutting line being invisible when using the light theme [`a2a1d40`](https://github.com/Hypfer/Valetudo/commit/a2a1d4061d605bd60c148a6464a1945ff59595bb)

### Refactoring

- **vendor.dreame**: Add more AI classifier IDs and pull the constant into DreameUtils [`0928cf0`](https://github.com/Hypfer/Valetudo/commit/0928cf01aff8b374dd9759a5252b6b63b9dc33a5)
- **webserver**: Use rate limiters instead of semaphore in ObstacleImagesCapabilityRouter [`90e5ab9`](https://github.com/Hypfer/Valetudo/commit/90e5ab935fc8a9d73365f0babcaab0b93054bf2e)

### Chores

- Bump dependencies [`5559f88`](https://github.com/Hypfer/Valetudo/commit/5559f88ab2a3367603f904a164f5a388bc7ccd98)
- Upgrade react-router v5 to v6 [`fb600a8`](https://github.com/Hypfer/Valetudo/commit/fb600a8ef5ab65e208e20ff1ddf8a77a85388bc0)
- Bump dependencies [`79deca1`](https://github.com/Hypfer/Valetudo/commit/79deca12ea907228d40298ed6fff1a133ae780e3)
- Fix the wrong link in the right place [`2152e20`](https://github.com/Hypfer/Valetudo/commit/2152e20b6eb34eed0bad02cd3fba6f34a1495a86)
- Bump some transitive dependencies [`dc3b96e`](https://github.com/Hypfer/Valetudo/commit/dc3b96e87d0f9a3c5fdcacf299ab33d42bfad691)
- **ui**: Resolve issues detected by sonarcloud [`b56ed1c`](https://github.com/Hypfer/Valetudo/commit/b56ed1ca6e29cde2ad2326c5bbc8c81a9b6146e6)
- Update PR template [`ddcf3e1`](https://github.com/Hypfer/Valetudo/commit/ddcf3e15909dce5e49815422566b8a8fbe6f48da)
