## Valetudo nightly (2023-12-15T02:19:10.773Z)

### Features

- **vendor.roborock**: Dock dustbin consumable for all auto-empty docks [`e3d13fa`](https://github.com/Hypfer/Valetudo/commit/e3d13fa521b9944e9e2040f96847002f5feaa1e9)
- Set the embedded process priority to below normal for good measure [`eadc2a7`](https://github.com/Hypfer/Valetudo/commit/eadc2a7a047531722c1a59729fcb5cde5e565bfa)
- **mqtt**: Add device_class attribute to battery and WiFi sensors for Home Assistant  (#1910) [`aac0f51`](https://github.com/Hypfer/Valetudo/commit/aac0f51da1d8009cee8380dcee81dda8eafdf3f1)
- **vendor.dreame**: Edge mopping for the L10 Ultra [`744fe20`](https://github.com/Hypfer/Valetudo/commit/744fe20833deec24a069029a22df8df6a0465d9c)

### Fixes

- **ui**: Fix achievement display and keep SSE connections alive for additional 500ms after the last subscriber disconnected [`c20731d`](https://github.com/Hypfer/Valetudo/commit/c20731d86102b8a7b83def05c3b6d03f2b3fdf6f)
- **vendor.dreame**: Remove CollisionAvoidantNavigationControl from the x10+ since it is not supported by the firmware [`d4f37e4`](https://github.com/Hypfer/Valetudo/commit/d4f37e4ea518a6d2ddc457db89a73d9255dba159)
- **vendor.dreame**: Fix edge mopping quirk state reporting [`9e4617b`](https://github.com/Hypfer/Valetudo/commit/9e4617ba3589ff1e069a99237f07826a674291ed)

### Refactoring

- Minor code cleanup [`ddb49e7`](https://github.com/Hypfer/Valetudo/commit/ddb49e7112d8422ae9505e77b103c83ba924f793)
- Bump all dependencies to latest versions + minor code cleanup [`5a364ef`](https://github.com/Hypfer/Valetudo/commit/5a364efdeacae0dd1ce907bd16317e264501b58a)

### Chores

- **build**: Bump to NodeJS v20.10.0 [`25eaa76`](https://github.com/Hypfer/Valetudo/commit/25eaa76499d990f6d9b40898443c618117903b6e)
- Disallow some more footguns with eslint [`9d9213c`](https://github.com/Hypfer/Valetudo/commit/9d9213c84e366ed91447c73bb0834d08ecd1be08)
- **vendor.dreame**: Add test case with a ginormous map file from an industrial building [`0d5a7df`](https://github.com/Hypfer/Valetudo/commit/0d5a7df48b61b12b9216f3818a4f3271a9ec0a0a)
- **build**: Bump to NodeJS v18.18.2 [`ba90e9b`](https://github.com/Hypfer/Valetudo/commit/ba90e9b6601832f1f65b2993303f99f4e854b85f)
