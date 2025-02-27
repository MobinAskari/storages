# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [2.5.1](https://github.com/grammyjs/storages/compare/v2.5.0...v2.5.1) (2025-02-27)

**Note:** Version bump only for package @grammyjs/storages

# [2.5.0](https://github.com/grammyjs/storages/compare/v2.4.2...v2.5.0) (2025-02-24)

### Bug Fixes

- **file:** don't throw deleting a file that does not exist ([#233](https://github.com/grammyjs/storages/issues/233)) ([b9d2adf](https://github.com/grammyjs/storages/commit/b9d2adf7f0a1b6bbbf6234839571caf2a9f06466))

### Features

- add autoParseDates option to RedisAdapter ([#231](https://github.com/grammyjs/storages/issues/231)) ([e65c9a0](https://github.com/grammyjs/storages/commit/e65c9a0378e3125533a726f2e86d81a813cc53fb))
- **free:** add readKeys method to free session storage adapter ([#242](https://github.com/grammyjs/storages/issues/242)) ([ee4016f](https://github.com/grammyjs/storages/commit/ee4016f23f1bd013d8e84e7c94028b0c44b11f35)), closes [/github.com/grammyjs/free-session-backend/blob/778a383057e7b8a244fdb2beee20542d8ce0867b/src/main.ts#L89](https://github.com//github.com/grammyjs/free-session-backend/blob/778a383057e7b8a244fdb2beee20542d8ce0867b/src/main.ts/issues/L89)
- **pocketbase:** add pocketbase storage adapter ([#218](https://github.com/grammyjs/storages/issues/218)) ([087df7a](https://github.com/grammyjs/storages/commit/087df7a2fa3e0b019db4d154db8cde09bf6cc5a1))

## [2.4.2](https://github.com/grammyjs/storages/compare/v2.4.1...v2.4.2) (2024-02-29)

### Bug Fixes

- add workaround for release action ([9646669](https://github.com/grammyjs/storages/commit/9646669e0b183e81d15246c69a8e07e24084885b))
- remove public from workflow ([4f56e00](https://github.com/grammyjs/storages/commit/4f56e00cec0c769054d968b0e37d5e7f47a06daa))

### Features

- recursive publish ([5012ed6](https://github.com/grammyjs/storages/commit/5012ed6e21f64a5f19188deab668af32c6d88ad6))

## [2.4.1](https://github.com/grammyjs/storages/compare/v2.4.0...v2.4.1) (2023-12-03)

**Note:** Version bump only for package @grammyjs/storages

# [2.4.0](https://github.com/grammyjs/storages/compare/v2.3.2...v2.4.0) (2023-10-09)

### Features

- **cloudflare:** add `d1` adapter ([#202](https://github.com/grammyjs/storages/issues/202)) ([b59428b](https://github.com/grammyjs/storages/commit/b59428bbac72521c31941969bef44062a50b4fa3))

## [2.3.2](https://github.com/grammyjs/storages/compare/v2.3.1...v2.3.2) (2023-09-05)

**Note:** Version bump only for package @grammyjs/storages

## [2.3.1](https://github.com/grammyjs/storages/compare/v2.3.0...v2.3.1) (2023-08-28)

### Bug Fixes

- **prisma:** silence the "Record to delete does not exist" error ([#186](https://github.com/grammyjs/storages/issues/186)) ([7ce1614](https://github.com/grammyjs/storages/commit/7ce16144b8d00ebb6ddfeabec06426d2eddcf3c9))
- **supabase:** use pinned supabase dependency ([de19f34](https://github.com/grammyjs/storages/commit/de19f341e165b20cb5b80e28f204648075dd2895))

# [2.3.0](https://github.com/grammyjs/storages/compare/v2.2.0...v2.3.0) (2023-05-31)

### Bug Fixes

- **denokv:** make tests idempotent ([b9e23b4](https://github.com/grammyjs/storages/commit/b9e23b45aee215e7e46d033d1b43a57720a60b30))
- **denokv:** script test ([c3e9889](https://github.com/grammyjs/storages/commit/c3e988981c79cd39a2a3416f7accae09823377c7))
- **dependency:** update dependency vitest to ^0.31.0 ([#173](https://github.com/grammyjs/storages/issues/173)) ([2ad2054](https://github.com/grammyjs/storages/commit/2ad20549052d034481011fdc61f0251eded9e44b))
- **typeorm:** use correct import of `ObjectId` for mongo ([cefaf34](https://github.com/grammyjs/storages/commit/cefaf3487ddde1213f200293f27fe87c3e80540e))

# [2.2.0](https://github.com/grammyjs/storages/compare/v2.1.4...v2.2.0) (2023-04-15)

### Features

- add Cloudflare Workers KV adapter ([#169](https://github.com/grammyjs/storages/issues/169)) ([efa162b](https://github.com/grammyjs/storages/commit/efa162bd85b0bb58b8fecf3e827b83126aeefde6))
- **denokv:** add `DenoKVAdapter` package ([#175](https://github.com/grammyjs/storages/issues/175)) ([e4bc891](https://github.com/grammyjs/storages/commit/e4bc891ffd25192afd71427700f4a81ceac65f36))

## [2.1.4](https://github.com/grammyjs/storages/compare/v2.1.3...v2.1.4) (2023-03-02)

### Bug Fixes

- **denodb:** again change denodb dependency to another url because it's again broken ([14ad651](https://github.com/grammyjs/storages/commit/14ad65134702ac3b4948bbf9321f7f5faf39df93))

## [2.1.3](https://github.com/grammyjs/storages/compare/v2.1.2...v2.1.3) (2023-03-02)

**Note:** Version bump only for package @grammyjs/storages

## [2.1.2](https://github.com/grammyjs/storages/compare/v2.1.1...v2.1.2) (2023-03-02)

### Bug Fixes

- **dependency:** update dependency vitest to ^0.29.0 ([d4a1970](https://github.com/grammyjs/storages/commit/d4a1970f51ab5cc9c25319488eac442c4e0220c9))
- **firestore:** correct path of exports in `package.json` ([972181a](https://github.com/grammyjs/storages/commit/972181a3ce3c6b484cfe5058f27d76a54304a926))

## [2.1.1](https://github.com/grammyjs/storages/compare/v2.1.0...v2.1.1) (2023-02-25)

### Bug Fixes

- **dependency:** update dependency vitest to ^0.28.0 ([564127a](https://github.com/grammyjs/storages/commit/564127afaa981b9ffc64ca215fcd3187d57b0232))

# [2.1.0](https://github.com/grammyjs/storages/compare/v2.0.2...v2.1.0) (2023-01-16)

### Bug Fixes

- **denodb:** pin `denodb` dependency to github version instead of released one ([7bc7095](https://github.com/grammyjs/storages/commit/7bc70954e8809c032b8b94300aa84fd7ae15d6ad))
- **dependency:** update dependency vitest to ^0.26.0 ([f77f620](https://github.com/grammyjs/storages/commit/f77f620561ef3ae186f17875fdb95c5a3991e962))
- **dependency:** update dependency vitest to ^0.27.0 ([3395170](https://github.com/grammyjs/storages/commit/33951704880ac3b3b99cf087f641291570b7e196))
- **utils:** add missed from to message object ([d19fe78](https://github.com/grammyjs/storages/commit/d19fe78f36cd01633607959db3f7f322b11c49b8))

### Features

- unpin grammy version from all packages ([f814e3e](https://github.com/grammyjs/storages/commit/f814e3e675c31e599cfaa1c93975e8dd55d23be6))
