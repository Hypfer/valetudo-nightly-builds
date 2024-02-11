## Valetudo nightly (2024-02-11T02:14:44.087Z)

### Features

- **ntpClient**: Double wait time to next attempt on each sync error [`6b15920`](https://github.com/Hypfer/Valetudo/commit/6b15920dab633aa66f0df07f987a7d9015342ef0)
- **ntpClient**: Use valetudo.pool.ntp.org as the default timeserver [`1a3a9f8`](https://github.com/Hypfer/Valetudo/commit/1a3a9f8b81eb923a9d7ee7858db9acab49aa88d2)
- **mqtt**: Publish ValetudoEvents to MQTT and allow interacting with it via MQTT [`cc2ecc3`](https://github.com/Hypfer/Valetudo/commit/cc2ecc3c000fa008a8711069619f8f65e0e93b53)
- **ui**: Display current robot time in NTPConnectivity view [`3880f8b`](https://github.com/Hypfer/Valetudo/commit/3880f8bf3a0fe40bb18a6da32ff91712ed072617)
- **vendor.dreame**: Add drain internal water tank quirk [`25f428f`](https://github.com/Hypfer/Valetudo/commit/25f428fd12843c2aa6de19746f572790c19be1f1)
- **vendor.dreame**: Add implementation for the R2211 [`9b01829`](https://github.com/Hypfer/Valetudo/commit/9b0182968e277c3a7dbc991650704da4eb45c4ae)

### Fixes

- **vendor.dreame**: Add error code mapping for code 121 [`dbbb58a`](https://github.com/Hypfer/Valetudo/commit/dbbb58aacae6706f235b87c1018cf1f4aa855866)
- Gracefully handle development on systems with bonded network interfaces [`9969307`](https://github.com/Hypfer/Valetudo/commit/9969307aef5ad4bf3b1ba81a51e4f36caccd06b7)
- **vendor.dreame**: Fix mop dock drying time quirk [`7c87bf6`](https://github.com/Hypfer/Valetudo/commit/7c87bf65379a7b9afd41ebd2bd6ce3cc9ca84bfe)
- **ui**: Improve map zoom range clipping [`ebf8e9f`](https://github.com/Hypfer/Valetudo/commit/ebf8e9fb55978615c9f644d219767e33b83cadd4)

### Chores

- Issue forms [`4dcee5c`](https://github.com/Hypfer/Valetudo/commit/4dcee5c20a2fd2b617508c87e65041657c0c9712)
