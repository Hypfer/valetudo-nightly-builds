## Valetudo nightly (2022-07-19T03:09:59.825Z)

### Features

- **vendor.dreame**: Add mop-only quirk for newer firmwares [`a33afe3`](https://github.com/Hypfer/Valetudo/commit/a33afe351c1b868919bc7b036e2e02a05b8e581c)
- **vendor.dreame**: Add Mop Dock UV-C Toggle Quirk [`7ce4abe`](https://github.com/Hypfer/Valetudo/commit/7ce4abe7353567fd3db6a7a9cc1c767d68a9db93)

### Fixes

- **miio**: Gracefully handle connectivity issues when receiving fds uploads [`8aab94f`](https://github.com/Hypfer/Valetudo/commit/8aab94fa2ab01479997968904e9312fbc8111a83)
- **vendor.dreame**: Ignore timezone update message [`5ecf7fa`](https://github.com/Hypfer/Valetudo/commit/5ecf7fa0842c498a2ad8abfd792a71b420ce34bf)
- **ui**: Allow sending home basic control command while paused [`0dfb4ba`](https://github.com/Hypfer/Valetudo/commit/0dfb4ba59bd1334f994beea211ac17fdf5323f1f)
- **vendor.dreame**: Fix maps for newer firmwares [`5f67103`](https://github.com/Hypfer/Valetudo/commit/5f6710348fd304046a201c2423490555e44d3b20)
- **webserver**: Fix openapi schema for MapSegmentEditCapability [`f106735`](https://github.com/Hypfer/Valetudo/commit/f106735cbae0eed2ebfebaa6843c7da976c5127e)

### Refactoring

- **webserver**: Response cleanup [`839310a`](https://github.com/Hypfer/Valetudo/commit/839310ab0941941d68ea4ba0c1fbfc17b8924443)
- **webserver**: Actually make use of the openapi schema validation [`6e2d2e1`](https://github.com/Hypfer/Valetudo/commit/6e2d2e1904040aa891dda5d35909654553e04eb7)
- Introduce RobotFirmwareError and refactor CapabilityRouter for unified error logs [`1d2ad47`](https://github.com/Hypfer/Valetudo/commit/1d2ad47e9d49eac71f0621d2aa0444acf871acec)

### Chores

- **ui**: Add missing rel="noopener" tag to menu bar [`a7e6920`](https://github.com/Hypfer/Valetudo/commit/a7e6920c7924b5db43b9eb086a434fddaa276d75)
- **build**: Bump to NodeJS v18.5.0 [`66712f9`](https://github.com/Hypfer/Valetudo/commit/66712f91dd3f16c24b0b22b334a37ecfeb983df9)
- Update wording in VoicepackHelp.ts [`05a6b89`](https://github.com/Hypfer/Valetudo/commit/05a6b89848b5c1e9a04f4a822da58e03cd89b5f8)
- Update issue template [`cebca05`](https://github.com/Hypfer/Valetudo/commit/cebca057ceb05d202f3f76211a2e63290f39b002)
