## Valetudo nightly (2025-01-06T09:25:13.042Z)
### Breaking Changes

- **vendor.dreame**: The mop consumable has been removed from X/L40 firmwares and equivalent [`d7f8e75`](https://github.com/Hypfer/Valetudo/commit/d7f8e753c0e6bfcc5bcac9cf6cc196100267f3c6)
- The sensor consumable type is now a subtype of the new type cleaning [`b798ebb`](https://github.com/Hypfer/Valetudo/commit/b798ebb2de3817228da80fabdbfe7b08026f3bd2)

### Features

- **vendor.dreame**: Introduce Side Brush on Carpet quirk [`f795e2e`](https://github.com/Hypfer/Valetudo/commit/f795e2e6cc6c59265f22abd09998b5986803cf2d)
- **vendor.dreame**: Wheel consumable monitoring [`1eda6ef`](https://github.com/Hypfer/Valetudo/commit/1eda6ef56fc2406e7ddd964ad2feb5abcb7628eb)
- **core**: Introduce wheel consumable subtype [`6161901`](https://github.com/Hypfer/Valetudo/commit/6161901d0b3903fd3810f5f40f6de3753b45d6b8)
- **updater**: Add unnecessary NullUpdateProvider for good measure [`1b9dc20`](https://github.com/Hypfer/Valetudo/commit/1b9dc20f6d50d8536b48949fbb26a4c17da141e6)
- **updater**: Introduce a working version comparison to the nightly update channel [`2cb8efc`](https://github.com/Hypfer/Valetudo/commit/2cb8efc3f4dccfca2e394688a4d1b32ebe73d75a)
- **ui**: Shuffle the MQTT settings around [`a96ab06`](https://github.com/Hypfer/Valetudo/commit/a96ab06546df8c3994231b0f8fc7bec22ee53b70)
- **mqtt**: Remove obsolete addICBINVMapProperty setting [`6dec70f`](https://github.com/Hypfer/Valetudo/commit/6dec70f75ee09519198ae554c0ed99b5b2e64ed2)
- **vendor.dreame**: MOVA P10 Pro Ultra [`df0609e`](https://github.com/Hypfer/Valetudo/commit/df0609ed255c9a5ca95a19fb7ea5f0ecc4139bfd)
- **vendor.dreame**: Introduce clean route quirk [`7b3dfb0`](https://github.com/Hypfer/Valetudo/commit/7b3dfb06e1542cfff752cb75ece0652930429ba4)
- **vendor.roborock**: Add error mapping for error codes 27 35 [`9d3df05`](https://github.com/Hypfer/Valetudo/commit/9d3df057be7a34e9040569cdcad1405de14f0683)
- **ui**: Trim host field inputs [`a07503b`](https://github.com/Hypfer/Valetudo/commit/a07503b1e8443c3c45ea338f2c6ef173894eea34)
- **mqtt**: Optionally expose PetObstacleAvoidance, CarpetModeControl and CarpetSensorModeControl capabilities [`2cc0ab5`](https://github.com/Hypfer/Valetudo/commit/2cc0ab52e601411aab7c26ff6975a4d5c38f45ff)
- **mqtt**: Publish Dock Status to MQTT [`ee76222`](https://github.com/Hypfer/Valetudo/commit/ee76222a415e0cf72f91662e3230907c27027af2)

### Fixes

- **vendor.dreame**: Newer dreames may store obstacle images elsewhere [`b8477fb`](https://github.com/Hypfer/Valetudo/commit/b8477fbdb66b4b24d391764ab5ada80196a387bd)
- **mqtt**: Attempt to fix the reconfigure mutex never being left [`1af75e0`](https://github.com/Hypfer/Valetudo/commit/1af75e00341840d4f6a02d4ba1773b926d4b32d4)
- **docs**: Wording [`fd89128`](https://github.com/Hypfer/Valetudo/commit/fd89128ce6200c6835072e883c6597820b1068bb)
- **ui**: Add missing word in welcomeDialog [`c78e8c2`](https://github.com/Hypfer/Valetudo/commit/c78e8c2775018a2dd1f67335469dd30528287b08)
- **vendor.dreame**: Hide obstacles of type 200 [`88c0af5`](https://github.com/Hypfer/Valetudo/commit/88c0af5c8bb24f45edfab8d4b53c7b7e6165c6a1)
- **mqtt**: Fix Home Assistant object_id generation [`d77480c`](https://github.com/Hypfer/Valetudo/commit/d77480c1923d2c1edca4dfc87e7022832ccda290)

### Refactoring

- **mqtt**: Minor cleanup [`8f22341`](https://github.com/Hypfer/Valetudo/commit/8f22341b65a6246307b2afba0220ebf191ad8a1c)