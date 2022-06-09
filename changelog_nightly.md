## Valetudo nightly (2022-06-09T02:57:53.077Z)

### Features

- **updater**: Add changelog to nightly update provider [`3a874db`](https://github.com/Hypfer/Valetudo/commit/3a874db088f445d03e71f08f9125ac5ce9cbc4d6)
- **mqtt**: Deduplicate mqtt map data as well [`269aa30`](https://github.com/Hypfer/Valetudo/commit/269aa3004f3925e26afe66139109b201133afcfe)

### Fixes

- **ui**: Fix map SSE EventSource not reconnecting on error [`d84efd5`](https://github.com/Hypfer/Valetudo/commit/d84efd586122aff81cab8524517cc2c5a0b7b37b)
- **ui**: fix circular chunk dependency [`271e53c`](https://github.com/Hypfer/Valetudo/commit/271e53c6fa6aa659f94e14e4fd10934901857b82)
- **ui**: Fix map not properly redrawing on visibility state change [`bd77d2e`](https://github.com/Hypfer/Valetudo/commit/bd77d2e22adc33813fb4ab5e3897e6b58d5340e2)
- **utils**: hash key instead of value (#1503) [`bae09ab`](https://github.com/Hypfer/Valetudo/commit/bae09ab9f1d09ca98cd54272aab96afac05e52cb)
- **miio**: Fix ERR_HTTP_HEADERS_SENT exception (#1501) [`a47f3b9`](https://github.com/Hypfer/Valetudo/commit/a47f3b9c97c4abd3f8a5c9a61750312ffce05800)
- **vendor.dreame**: The STYTJO6ZHM does not feature a watertank [`9b75974`](https://github.com/Hypfer/Valetudo/commit/9b7597420084cd579ce9990667d1118c8d5a27ed)
- **vendor.roborock**: copy statusflag from previous state on state update (#1497) [`84de0ef`](https://github.com/Hypfer/Valetudo/commit/84de0ef9d869f5150c504fa13bcd49956c71bf4c)

### Refactoring

- **vendor.roborock**: Improve logic legibility in ZoneCleaningCapability [`560a50e`](https://github.com/Hypfer/Valetudo/commit/560a50edfca23c6a80378f0bed9cc3c1a533d8bc)
- **ui**: Port map color finder to typescript [`6c1b126`](https://github.com/Hypfer/Valetudo/commit/6c1b126138f4e8b751913eb4d4c411a22d7f492c)
- **ui**: Make use of webpack 5 and convert the map layer render webworker to typescript [`d17b66d`](https://github.com/Hypfer/Valetudo/commit/d17b66d6be3381a9c14cf3dfe118f560bd5ed408)
- **ui**: Port map touch handling to typescript [`9548012`](https://github.com/Hypfer/Valetudo/commit/95480129dbf4d72eb2e87a7a0ac1d9c18e429369)
- **ui**: Do not monkey patch the 2d context of the map renderer [`212e4f5`](https://github.com/Hypfer/Valetudo/commit/212e4f541b14a9d5a55d4fe10d54a5c173fc2800)
- **ui**: Remove unnecessary nullchecks in the map component [`96ba8cf`](https://github.com/Hypfer/Valetudo/commit/96ba8cf83f6a4d0c9235359b77414e0cbd70d658)
- **vendor.dreame**: Improve mop dock settings handling [`412a65a`](https://github.com/Hypfer/Valetudo/commit/412a65ab4c5cf3c7ba061ea59d61c88c1d345e34)
- **miio**: Unify previously duplicated map poll code [`356d144`](https://github.com/Hypfer/Valetudo/commit/356d144b9cd15840ccd32c2b2a0a21cb0fa011a8)

### Chores

- Fix nightly changelog generation [`2c73de3`](https://github.com/Hypfer/Valetudo/commit/2c73de3cb7d4a564c4b3306e37a5bfa3f3755ff2)
- Minor misc code cleanups [`3c3c561`](https://github.com/Hypfer/Valetudo/commit/3c3c5617dfac3b8a48f43e695c005d95593857ac)
- More dependency changes [`0becd44`](https://github.com/Hypfer/Valetudo/commit/0becd4490b397539de3a8a6593e547cbc4fcba15)
- Delete obsolete Events.js [`5176cce`](https://github.com/Hypfer/Valetudo/commit/5176cce43a9dff88d7acfc39038b3b4e7c303a86)
- Bump dependencies [`8ae420c`](https://github.com/Hypfer/Valetudo/commit/8ae420c1576331dd26acfdf2d3e7a83ff05ebf06)
- bump GitHub codeql action to v2 [`643dcc5`](https://github.com/Hypfer/Valetudo/commit/643dcc581c556797bc6b989dde25671e9ad55378)
- **vendor.dreame**: Add documentation on the mop dock settings data format [`881f717`](https://github.com/Hypfer/Valetudo/commit/881f717ac37505c7f113b6c82f6754837e8a9d43)
- typo fix [`41055d1`](https://github.com/Hypfer/Valetudo/commit/41055d1c9a4615fe9664487e66ec7e9a81773428)
