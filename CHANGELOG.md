## [1.5.2](https://github.com/AllanOricil/nrg/compare/v1.5.1...v1.5.2) (2024-11-02)


### Bug Fixes

* **deps:** bump @allanoricil/nrg-nodes from 1.1.0 to 1.1.1 ([0f2060f](https://github.com/AllanOricil/nrg/commit/0f2060f659f12656ed2ebf8a0605e6cb1f5df87c))

## [1.5.1](https://github.com/AllanOricil/nrg/compare/v1.5.0...v1.5.1) (2024-10-28)


### Bug Fixes

* await can only be used inside an async function ([0e2e543](https://github.com/AllanOricil/nrg/commit/0e2e543c9db2d49568692bed846b25979876697f))
* error TS1064 ([09f7fc4](https://github.com/AllanOricil/nrg/commit/09f7fc479eb987ac1af086954bb7204a4c8f3771))
* upgrade esbuild from 0.23.1 to 0.24.0 ([3c8c81b](https://github.com/AllanOricil/nrg/commit/3c8c81b6b4f0e2fca46f4996ef1b332735fbebd7))


### Reverts

* feat: add custom html attributes id: for: i18n: ([3c4ff6b](https://github.com/AllanOricil/nrg/commit/3c4ff6bb84eb98f61a697b8dd9018142e84a255a))

# [1.5.0](https://github.com/AllanOricil/nrg/compare/v1.4.0...v1.5.0) (2024-10-13)


### Bug Fixes

* add provenance to releases ([0e15566](https://github.com/AllanOricil/nrg/commit/0e155665c3c037316c5b6d7e48b6bf06f98b37d6))


### Features

* **deps:** bump @allanoricil/nrg-nodes from 1.0.1 to 1.1.0 ([d82a25d](https://github.com/AllanOricil/nrg/commit/d82a25d1c3b54098dc58e88481bd27f468d84a81))

# [1.4.0](https://github.com/AllanOricil/nrg/compare/v1.3.1...v1.4.0) (2024-10-13)


### Features

* html is now wrapped with text/html instead of text/x-red ([59d0336](https://github.com/AllanOricil/nrg/commit/59d0336b53630407373325c4080de93e917be537))

## [1.3.1](https://github.com/AllanOricil/nrg/compare/v1.3.0...v1.3.1) (2024-10-11)


### Bug Fixes

* package.json & package-lock.json to reduce vulnerabilities ([0414349](https://github.com/AllanOricil/nrg/commit/041434978d77fef797427822fa395102d9365235))
* upgrade postcss from 8.4.45 to 8.4.47 ([20ad369](https://github.com/AllanOricil/nrg/commit/20ad3695ae96ea6c89aed0e2523ca3eb8588ffb3))

# [1.3.0](https://github.com/AllanOricil/nrg/compare/v1.2.5...v1.3.0) (2024-10-06)


### Features

* change @allanoricil/node-red-node by @allanoricil/nrg-nodes ([eb7e157](https://github.com/AllanOricil/nrg/commit/eb7e15744440fbe958fccf74c0bf3479ad18c905))

## [1.2.5](https://github.com/AllanOricil/nrg/compare/v1.2.4...v1.2.5) (2024-10-05)


### Bug Fixes

* build exceptions during watch mode won't kill the process anymore ([080352e](https://github.com/AllanOricil/nrg/commit/080352ec310315fd34bb3500fc5d5660ef30c290))

## [1.2.4](https://github.com/AllanOricil/nrg/compare/v1.2.3...v1.2.4) (2024-10-01)


### Bug Fixes

* **vulnerability:** body-parser vulnerable to denial of service when url encoding is enabled ([c8ad9fb](https://github.com/AllanOricil/nrg/commit/c8ad9fb36b3ef8b7c33420745395ff00be3ab0e3))
* **vulnerability:** fix DOM Clobbering Gadget found in rollup bundled scripts that leads to XSS ([214aeec](https://github.com/AllanOricil/nrg/commit/214aeecc0f6365765f57a91511deaf836359785d))
* **vulnerability:** kangax html-minifier REDoS vulnerability ([e4d3007](https://github.com/AllanOricil/nrg/commit/e4d3007768018a810b6dc4ca14e390034b9d7785))
* **vulnerability:** vite DOM Clobbering gadget found in vite bundled scripts that leads to XSS ([c0b3b63](https://github.com/AllanOricil/nrg/commit/c0b3b63d42111b5af4693d6b7791dd12cf918d46))

## [1.2.3](https://github.com/AllanOricil/nrg/compare/v1.2.2...v1.2.3) (2024-09-29)


### Bug Fixes

* windows can't start node-red when using bash ([7704825](https://github.com/AllanOricil/nrg/commit/7704825b295c96305c3c9efe7348a5a703fa8768))

## [1.2.2](https://github.com/AllanOricil/nrg/compare/v1.2.1...v1.2.2) (2024-09-29)


### Bug Fixes

* change log level verbose because this message is for debugging purposes only ([40a949a](https://github.com/AllanOricil/nrg/commit/40a949a78705f7cf8c80e9f2936b68dbac017033))

## [1.2.1](https://github.com/AllanOricil/nrg/compare/v1.2.0...v1.2.1) (2024-09-29)


### Bug Fixes

* error: R] Could not resolve "./clientindex.js" when building in Windows ([5d11c00](https://github.com/AllanOricil/nrg/commit/5d11c00a02f549a9f75868bae430784c8a9c36c1))

# [1.2.0](https://github.com/AllanOricil/nrg/compare/v1.1.0...v1.2.0) (2024-09-28)


### Bug Fixes

* upgrade esbuild from 0.21.5 to 0.23.1 ([5faa505](https://github.com/AllanOricil/nrg/commit/5faa5057efc05707db575979e64fccb3dc7c3ec5))


### Features

* if package root can't be found, a .nrg folder is created in the users home directory ([d11f89c](https://github.com/AllanOricil/nrg/commit/d11f89cad27bface38b353e7158bb06ca45d5410))

# [1.1.0](https://github.com/AllanOricil/nrg/compare/v1.0.1...v1.1.0) (2024-09-18)


### Features

* add custom html attributes id: for: i18n: ([0e67ad6](https://github.com/AllanOricil/nrg/commit/0e67ad672f0ffa58f12cb2a90238cf322551d71c))
