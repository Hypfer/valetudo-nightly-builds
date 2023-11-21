## Valetudo nightly (2023-11-21T02:19:22.743Z)

### Features

- **vendor.roborock**: Dock dustbin consumable for all auto-empty docks [`e3d13fa`](https://github.com/Hypfer/Valetudo/commit/e3d13fa521b9944e9e2040f96847002f5feaa1e9)
- Set the embedded process priority to below normal for good measure [`eadc2a7`](https://github.com/Hypfer/Valetudo/commit/eadc2a7a047531722c1a59729fcb5cde5e565bfa)
- **mqtt**: Add device_class attribute to battery and WiFi sensors for Home Assistant  (#1910) [`aac0f51`](https://github.com/Hypfer/Valetudo/commit/aac0f51da1d8009cee8380dcee81dda8eafdf3f1)
- **vendor.dreame**: Edge mopping for the L10 Ultra [`744fe20`](https://github.com/Hypfer/Valetudo/commit/744fe20833deec24a069029a22df8df6a0465d9c)

### Fixes

- **vendor.dreame**: Remove CollisionAvoidantNavigationControl from the x10+ since it is not supported by the firmware [`d4f37e4`](https://github.com/Hypfer/Valetudo/commit/d4f37e4ea518a6d2ddc457db89a73d9255dba159)
- **vendor.dreame**: Fix edge mopping quirk state reporting [`9e4617b`](https://github.com/Hypfer/Valetudo/commit/9e4617ba3589ff1e069a99237f07826a674291ed)
