## Valetudo nightly (2024-11-08T02:42:52.354Z)

### Features

- **vendor.dreame**: Introduce water hookup test quirk [`cf20143`](https://github.com/Hypfer/Valetudo/commit/cf20143b75b876ba730fe52c3b8bf5fb75c9d9cb)

### Fixes

- **vendor.dreame**: Fix water hookup test quirk success state raising an error [`74731a6`](https://github.com/Hypfer/Valetudo/commit/74731a6bd491ca30717ca208ca666bf20b20a0d5)
- Fix breakage caused by splitting changes into multiple commits [`dd6eac0`](https://github.com/Hypfer/Valetudo/commit/dd6eac067bceaea7a1e54d98c56853a91534a8f6)
- **timers**: Allow execution of timers if time is plausible [`bf9ecb6`](https://github.com/Hypfer/Valetudo/commit/bf9ecb627be68fbce0e610ae1a710d529a037cf5)

### Refactoring

- Bake-in specifically crafted build_metadata file instead of random other files [`436fae6`](https://github.com/Hypfer/Valetudo/commit/436fae629385a23b2f6c9d91468e9d583f820a2b)
- Remove unnecessary second call to process.memoryUsage.rss() every 2.5s [`8e336f6`](https://github.com/Hypfer/Valetudo/commit/8e336f6f9306c686569154c67d16d6620ecfcc2a)

### Chores

- Bump some dependencies [`89d1fb1`](https://github.com/Hypfer/Valetudo/commit/89d1fb1dbb0a5c164e608b5dfe7bab187d75a51b)
