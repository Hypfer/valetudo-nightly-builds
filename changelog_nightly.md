## Valetudo nightly (2023-08-06T02:16:10.521Z)

### Features

- **mqtt**: Expose battery state and status flag as home assistant sensor entities [`5f26145`](https://github.com/Hypfer/Valetudo/commit/5f2614580ed7390ea8467174c310a36b8ab99709)
- **vendor.roborock**: S8 Pro Ultra support [`0f390e0`](https://github.com/Hypfer/Valetudo/commit/0f390e0c6dfdee6cd1773765881906e2d355fbf1)
- **vendor.viomi**: Support outline cleaning mode (#1844) [`f68b995`](https://github.com/Hypfer/Valetudo/commit/f68b99586f69a7644f75cf4fff1e33ccd3f4a5ef)
- CarpetSensorModeControlCapability [`a4261b6`](https://github.com/Hypfer/Valetudo/commit/a4261b641e21a3fa8674c68042f1114a21181065)
- CollisionAvoidantNavigationControlCapability [`e22e532`](https://github.com/Hypfer/Valetudo/commit/e22e532982673fcc95ec6ece9740e078626ac51e)
- **vendor.dreame**: More quirks [`5a3ecc6`](https://github.com/Hypfer/Valetudo/commit/5a3ecc64c5f5499bb9cf2b43ce1e22850fb4622c)
- PetObstacleAvoidanceControlCapability [`7eae549`](https://github.com/Hypfer/Valetudo/commit/7eae549ee55331ddf888383cd3d0b83ab7421fb2)
- **vendor.roborock**: RoborockObstacleAvoidanceControlCapability [`bd1febe`](https://github.com/Hypfer/Valetudo/commit/bd1febe337192a31185a1bb316793d029da4abff)
- Return of the ObstacleAvoidanceControlCapability [`e48aa7e`](https://github.com/Hypfer/Valetudo/commit/e48aa7e78de3ddd8d27056fe15dc61387f15b89b)
- **vendor.roborock**: S8 support + map parser cleanup [`12aa3a7`](https://github.com/Hypfer/Valetudo/commit/12aa3a73371cfd55d6ffa0a99575ba19ae523e73)
- **vendor.dreame**: L10 Ultra [`4e4b7ae`](https://github.com/Hypfer/Valetudo/commit/4e4b7ae2641fff08bb91197b704e4ebf977901c9)

### Fixes

- **vendor.roborock**: Remove invalid quirk for S8 series [`76bba87`](https://github.com/Hypfer/Valetudo/commit/76bba87a3976bdfefec899eb7d8d9b84449e7bba)
- **vendor.dreame**: The L10S Pro does not support the CollisionAvoidantNavigationControlCapability [`c3405bd`](https://github.com/Hypfer/Valetudo/commit/c3405bdb8ebbd930a21835152211b2e8363da705)

### Refactoring

- **vendor.dreame**: Hard-code miot IDs for capabilities that are exclusive to the gen2 miot schema [`ef93adf`](https://github.com/Hypfer/Valetudo/commit/ef93adf2d5259e7537f1983eed2848e0df030ef8)

### Chores

- Update PR template [`0ffa7b4`](https://github.com/Hypfer/Valetudo/commit/0ffa7b407a28859af8b0b3687976193922db97f0)
- **vendor.dreame**: Minor cleanup of confusing loglines [`eb73525`](https://github.com/Hypfer/Valetudo/commit/eb7352565f7c55d2dd783fedb1d2f9c7a2abc166)
- **build**: Include openAPI spec json as a release asset for prod and nightly [`db9f42e`](https://github.com/Hypfer/Valetudo/commit/db9f42ea8c0e727108a9680fc3c825753fd20131)
