# Changelog

All notable changes to this project will be documented in this file. See [commit-and-tag-version](https://github.com/absolute-version/commit-and-tag-version) for commit guidelines.

## [6.2.1](https://github.com/wagoid/commitlint-github-action/compare/v6.2.0...v6.2.1) (2025-01-14)

## [6.2.0](https://github.com/wagoid/commitlint-github-action/compare/v6.1.2...v6.2.0) (2024-12-16)


### Features

* handle merge_group event - get squashed commit ([#806](https://github.com/wagoid/commitlint-github-action/issues/806)) ([ef2cd3b](https://github.com/wagoid/commitlint-github-action/commit/ef2cd3b0d22642360cebe0fee208e9c725d4bb82))

## [6.1.2](https://github.com/wagoid/commitlint-github-action/compare/v6.1.1...v6.1.2) (2024-09-04)


### Bug Fixes

* using compareCommits for push event commit query ([#801](https://github.com/wagoid/commitlint-github-action/issues/801)) ([47ff131](https://github.com/wagoid/commitlint-github-action/commit/47ff1315a12847478779c4d002c30f406009e206))

## [6.1.1](https://github.com/wagoid/commitlint-github-action/compare/v6.1.0...v6.1.1) (2024-08-21)

## [6.1.0](https://github.com/wagoid/commitlint-github-action/compare/v6.0.2...v6.1.0) (2024-08-20)


### Features

* updating push event trigger to use rest API (OctoKit) vs push event ([70e22e9](https://github.com/wagoid/commitlint-github-action/commit/70e22e95384c0028a4a5a9679a729c3ac9224dcd))


### Bug Fixes

* updating unit tests with mocking push octokit list commits ([c3ab7fd](https://github.com/wagoid/commitlint-github-action/commit/c3ab7fd301c536b0e96211a1dde49b6aabbfa8fd))

## [6.0.2](https://github.com/wagoid/commitlint-github-action/compare/v6.0.1...v6.0.2) (2024-08-05)

## [6.0.1](https://github.com/wagoid/commitlint-github-action/compare/v6.0.0...v6.0.1) (2024-04-10)

## [6.0.0](https://github.com/wagoid/commitlint-github-action/compare/v5.5.1...v6.0.0) (2024-03-28)


### ⚠ BREAKING CHANGES

* `commitlint.config.js` is not supported anymore, please use `.mjs` extension

### Features

* upgrade to commitlint v19 ([732f0ad](https://github.com/wagoid/commitlint-github-action/commit/732f0ad7d5fc8650d54cbdbb9183a4e40f3e9ed8))

## [5.5.1](https://github.com/wagoid/commitlint-github-action/compare/v5.5.0...v5.5.1) (2024-03-28)


### Bug Fixes

* upgrade commitlint to latest v18 ([6ee28c9](https://github.com/wagoid/commitlint-github-action/commit/6ee28c93002746f39d5d3f364b4d02e3b10600a1)), closes [#760](https://github.com/wagoid/commitlint-github-action/issues/760)

## [5.5.0](https://github.com/wagoid/commitlint-github-action/compare/v5.4.5...v5.5.0) (2024-03-28)


### Features

* upgrade commitlint to latest version ([2ff45dc](https://github.com/wagoid/commitlint-github-action/commit/2ff45dc12063297947621e4f7e0b4e53b17fd6ed))


### Bug Fixes

* rollback update of commitlint to support configs that use commonjs ([06143b2](https://github.com/wagoid/commitlint-github-action/commit/06143b235b3cbc9b59880866cf547f9b7b52b79c))

## [5.4.6](https://github.com/wagoid/commitlint-github-action/compare/v5.4.5...v5.4.6) (2024-03-28)


### Features

* upgrade commitlint to latest version ([2ff45dc](https://github.com/wagoid/commitlint-github-action/commit/2ff45dc12063297947621e4f7e0b4e53b17fd6ed))



## [5.4.5](https://github.com/wagoid/commitlint-github-action/compare/v5.4.4...v5.4.5) (2024-01-08)



## [5.4.4](https://github.com/wagoid/commitlint-github-action/compare/v5.4.3...v5.4.4) (2023-11-01)


### chore

* **deps:** update node version to 20.9.0 ([a8947aa](https://github.com/wagoid/commitlint-github-action/commit/a8947aa26c352af658d2e36b9ac24f245ef5c0f1))
* **deps:** upgrade commitlint packages ([fc3ebae](https://github.com/wagoid/commitlint-github-action/commit/fc3ebae70922434a73e7e0abdf88ee1ed109bf1b))


### BREAKING CHANGES

* **deps:** action now runs on commitlint 18
* **deps:** action now runs on Node 20.9.0



## [5.4.3](https://github.com/wagoid/commitlint-github-action/compare/v5.4.2...v5.4.3) (2023-07-23)


### Bug Fixes

* make sure action passes when event doesn't have commits fixes [#746](https://github.com/wagoid/commitlint-github-action/issues/746) ([6249453](https://github.com/wagoid/commitlint-github-action/commit/624945381bc1ad25d7df26e7fe07ebfe98e763f1))



## [5.4.2](https://github.com/wagoid/commitlint-github-action/compare/v5.4.1...v5.4.2) (2023-07-22)


* feat!: use github event payload and API to list commits resolves #456 ([a31f4b5](https://github.com/wagoid/commitlint-github-action/commit/a31f4b57934da285bea117cbd95f5e32ec6f5536)), closes [#456](https://github.com/wagoid/commitlint-github-action/issues/456)


### Features

* list up to 100 commits at once resolves [#717](https://github.com/wagoid/commitlint-github-action/issues/717) ([2be323b](https://github.com/wagoid/commitlint-github-action/commit/2be323bc447ae46dae3c61171525e091f31d42c3))


### BREAKING CHANGES

* "firstParent" option has been removed



## [5.4.1](https://github.com/wagoid/commitlint-github-action/compare/v5.4.0...v5.4.1) (2023-04-11)


### Bug Fixes

* **action:** add docker image back to yml ([09fdc59](https://github.com/wagoid/commitlint-github-action/commit/09fdc594834fda031fa27ce7f95d89da8ef68dc8))
* **action:** move info sequence for failonerrors ([d4e1e80](https://github.com/wagoid/commitlint-github-action/commit/d4e1e800cd5f24869c63b725ca461da53cc8b419))
* **action:** move info sequence for failonerrors ([00cf650](https://github.com/wagoid/commitlint-github-action/commit/00cf65022ffbecf121f0ac4d7158772d57e35735))
* **action:** removed unnecessary setOutput call ([0a35ed4](https://github.com/wagoid/commitlint-github-action/commit/0a35ed499e45918fc5e3735b85e015a20bb82177))
* **action:** use dockerfile ([0561ba8](https://github.com/wagoid/commitlint-github-action/commit/0561ba89620ef690e74a82f00c378aa655a86490))



# [5.4.0](https://github.com/wagoid/commitlint-github-action/compare/v5.3.1...v5.4.0) (2023-04-10)


### Bug Fixes

* **action:** add field to action ([8589bb7](https://github.com/wagoid/commitlint-github-action/commit/8589bb7e04b6baba23e93083597321c592b18593))
* **action:** fix bug with value, add tests ([2640e4c](https://github.com/wagoid/commitlint-github-action/commit/2640e4c8bf1ef522aea0d9fa997c4f07ee95ba97))
* **action:** refactor a value, add to docs ([7991e57](https://github.com/wagoid/commitlint-github-action/commit/7991e57b35c9a86cdda880119d9c4ca3b975b4fd))
* **docs:** remove dupe ([6a9739b](https://github.com/wagoid/commitlint-github-action/commit/6a9739b9a2f47cb6e51a850b6e82fa9c42a13f61))
* **tests:** remove log ([097b726](https://github.com/wagoid/commitlint-github-action/commit/097b726807006a63d6f34782aad667815f4217dc))


### Features

* **action:** adds flag to optionally fail on errors ([83467da](https://github.com/wagoid/commitlint-github-action/commit/83467da07bcf182bf7dead9d98090d358bb760d8))



## [5.3.1](https://github.com/wagoid/commitlint-github-action/compare/v5.3.0...v5.3.1) (2023-02-15)



# [5.3.0](https://github.com/wagoid/commitlint-github-action/compare/v5.2.2...v5.3.0) (2022-11-24)


### Features

* adds commitDepth as new input param ([b0982e3](https://github.com/wagoid/commitlint-github-action/commit/b0982e3b0a9fd9398bcfdf10c12df058bb8ffaf2))



## [5.2.2](https://github.com/wagoid/commitlint-github-action/compare/v5.2.1...v5.2.2) (2022-10-24)



## [5.2.1](https://github.com/wagoid/commitlint-github-action/compare/v5.2.0...v5.2.1) (2022-10-24)



# [5.2.0](https://github.com/wagoid/commitlint-github-action/compare/v5.1.2...v5.2.0) (2022-10-08)


### Bug Fixes

* add conventional-changelog-conventionalcommits dependency to fix [#552](https://github.com/wagoid/commitlint-github-action/issues/552) ([b584ba3](https://github.com/wagoid/commitlint-github-action/commit/b584ba3e8df77995e7e1858cac45eea8e203e0aa))


### Features

* **deps:** update [@commitlint](https://github.com/commitlint) packages from 17.0 to 17.1 ([d23c330](https://github.com/wagoid/commitlint-github-action/commit/d23c330a95e9e3bead8cbab20e1fbe072bdaeec9))
* **deps:** update commitlint-config-jira and commitlint-config-jira-rules to 1.6.4 ([8b8230b](https://github.com/wagoid/commitlint-github-action/commit/8b8230b1f5be718edfe694137f7af2843c8617fa))
* **deps:** update commitlint-plugin-function-rules to 1.7.1 ([c2981f1](https://github.com/wagoid/commitlint-github-action/commit/c2981f157c76acf9bc11bc5d3d278140b642aa8f))



## [5.1.2](https://github.com/wagoid/commitlint-github-action/compare/v5.1.1...v5.1.2) (2022-10-06)



## [5.1.1](https://github.com/wagoid/commitlint-github-action/compare/v5.1.0...v5.1.1) (2022-10-06)



# [5.1.0](https://github.com/wagoid/commitlint-github-action/compare/v5.0.2...v5.1.0) (2022-10-06)


### Features

* add @commitlint/ensure so that users of the action can use it too ([21c37a5](https://github.com/wagoid/commitlint-github-action/commit/21c37a524217629f2486c3f38a88b1628bf78d87))



## [5.0.2](https://github.com/wagoid/commitlint-github-action/compare/v5.0.1...v5.0.2) (2022-06-28)



## [5.0.1](https://github.com/wagoid/commitlint-github-action/compare/v5.0.0...v5.0.1) (2022-06-18)



# [5.0.0](https://github.com/wagoid/commitlint-github-action/compare/v4.1.15...v5.0.0) (2022-06-16)


### Features

* upgrade [@commitlint](https://github.com/commitlint) packages ([91c000c](https://github.com/wagoid/commitlint-github-action/commit/91c000c1e080c9c04bf3c2c139acf4a8cd2f98c9))


### BREAKING CHANGES

* chore: rename circleci windows job
* requires lerna v5



## [4.1.15](https://github.com/wagoid/commitlint-github-action/compare/v4.1.14...v4.1.15) (2022-06-16)



## [4.1.14](https://github.com/wagoid/commitlint-github-action/compare/v4.1.13...v4.1.14) (2022-06-16)



## [4.1.13](https://github.com/wagoid/commitlint-github-action/compare/v4.1.12...v4.1.13) (2022-06-16)



## [4.1.12](https://github.com/wagoid/commitlint-github-action/compare/v4.1.11...v4.1.12) (2022-05-07)


### Bug Fixes

* set workspace directory as safe in the entrypoint ([ce9a8cb](https://github.com/wagoid/commitlint-github-action/commit/ce9a8cb8ca913ad31123ebcfb3ce88061fe7108e)), closes [/github.com/actions/checkout/issues/760#issuecomment-1098135955](https://github.com//github.com/actions/checkout/issues/760/issues/issuecomment-1098135955)



## [4.1.11](https://github.com/wagoid/commitlint-github-action/compare/v4.1.10...v4.1.11) (2022-04-06)



## [4.1.10](https://github.com/wagoid/commitlint-github-action/compare/v4.1.9...v4.1.10) (2022-04-01)



## [4.1.9](https://github.com/wagoid/commitlint-github-action/compare/v4.1.8...v4.1.9) (2021-10-11)


### Bug Fixes

* use helpUrl from config when present ([6f0b49b](https://github.com/wagoid/commitlint-github-action/commit/6f0b49bb7b70977c2f0ea471a0282d21d5a8aab5)), closes [#234](https://github.com/wagoid/commitlint-github-action/issues/234)



## [4.1.8](https://github.com/wagoid/commitlint-github-action/compare/v4.1.7...v4.1.8) (2021-10-11)



## [4.1.7](https://github.com/wagoid/commitlint-github-action/compare/v4.1.6...v4.1.7) (2021-10-11)



## [4.1.6](https://github.com/wagoid/commitlint-github-action/compare/v4.1.5...v4.1.6) (2021-10-11)



## [4.1.5](https://github.com/wagoid/commitlint-github-action/compare/v4.1.4...v4.1.5) (2021-10-01)



## [4.1.4](https://github.com/wagoid/commitlint-github-action/compare/v4.1.3...v4.1.4) (2021-09-11)



## [4.1.3](https://github.com/wagoid/commitlint-github-action/compare/v4.1.2...v4.1.3) (2021-09-11)


### Bug Fixes

* action failing to check footer of a single commit ([961b6d4](https://github.com/wagoid/commitlint-github-action/commit/961b6d4cd7565e86ea5e28bcb015042ae2022f4f)), closes [#187](https://github.com/wagoid/commitlint-github-action/issues/187)
* vulnerabilities from npm audit ([bf83d2b](https://github.com/wagoid/commitlint-github-action/commit/bf83d2b35c4177779d047f464b48d9907f2c5201))



## [4.1.2](https://github.com/wagoid/commitlint-github-action/compare/v4.1.1...v4.1.2) (2021-09-11)



## [4.1.1](https://github.com/wagoid/commitlint-github-action/compare/v4.1.0...v4.1.1) (2021-07-17)



# [4.1.0](https://github.com/wagoid/commitlint-github-action/compare/v4.0.3...v4.1.0) (2021-07-17)


### Features

* officially support commitlint-plugin-function-rules ([d6d6fc0](https://github.com/wagoid/commitlint-github-action/commit/d6d6fc0ae0ec45f7b495ae44a78ec5499877ae0d)), closes [#196](https://github.com/wagoid/commitlint-github-action/issues/196)



## [4.0.3](https://github.com/wagoid/commitlint-github-action/compare/v4.0.2...v4.0.3) (2021-07-17)


### Bug Fixes

* build the action with rollup ([2e57812](https://github.com/wagoid/commitlint-github-action/commit/2e578124a54b446aaf8dfa6d7c71d92e2d6a3de7)), closes [#194](https://github.com/wagoid/commitlint-github-action/issues/194)



## [4.0.2](https://github.com/wagoid/commitlint-github-action/compare/v4.0.1...v4.0.2) (2021-07-15)


### Bug Fixes

* default to .cjs extension in config files ([5b6cd1b](https://github.com/wagoid/commitlint-github-action/commit/5b6cd1b23af3fcd4e6df552d48cc01dff41262dd))



## [4.0.1](https://github.com/wagoid/commitlint-github-action/compare/v4.0.0...v4.0.1) (2021-07-15)



# [4.0.0](https://github.com/wagoid/commitlint-github-action/compare/v3.1.4...v4.0.0) (2021-07-15)


### Features

* update dependencies that needed to switch to ESM syntax ([5463926](https://github.com/wagoid/commitlint-github-action/commit/5463926c07584c419d865a3fc9efdb382be54995))
* upgrade to node.js 16 to support ES modules by default ([30d514f](https://github.com/wagoid/commitlint-github-action/commit/30d514f252505053d2e65896a0865ff0302b7233))


### BREAKING CHANGES

* Node.js version used on the action updated from 12 to
16



## [3.1.4](https://github.com/wagoid/commitlint-github-action/compare/v3.1.3...v3.1.4) (2021-05-19)



## [3.1.3](https://github.com/wagoid/commitlint-github-action/compare/v3.1.2...v3.1.3) (2021-05-10)



## [3.1.2](https://github.com/wagoid/commitlint-github-action/compare/v3.1.1...v3.1.2) (2021-05-08)



## [3.1.1](https://github.com/wagoid/commitlint-github-action/compare/v3.1.0...v3.1.1) (2021-05-04)



# [3.1.0](https://github.com/wagoid/commitlint-github-action/compare/v3.0.8...v3.1.0) (2021-04-06)


### Features

* add support for pull_request_target event ([de51303](https://github.com/wagoid/commitlint-github-action/commit/de513030467551ee03fb8827bd790967fd5818ab))



## [3.0.8](https://github.com/wagoid/commitlint-github-action/compare/v3.0.7...v3.0.8) (2021-04-05)



## [3.0.7](https://github.com/wagoid/commitlint-github-action/compare/v3.0.6...v3.0.7) (2021-04-01)



## [3.0.6](https://github.com/wagoid/commitlint-github-action/compare/v3.0.5...v3.0.6) (2021-03-02)


### Bug Fixes

* perform an atomic push when releasing ([9d00d1e](https://github.com/wagoid/commitlint-github-action/commit/9d00d1e75718143215dbf95c9c12956c56225e90))



## [3.0.5](https://github.com/wagoid/commitlint-github-action/compare/v3.0.3...v3.0.5) (2021-03-02)



## [3.0.3](https://github.com/wagoid/commitlint-github-action/compare/v3.0.2...v3.0.3) (2021-03-02)



## [3.0.2](https://github.com/wagoid/commitlint-github-action/compare/v3.0.1...v3.0.2) (2021-03-02)



## [3.0.1](https://github.com/wagoid/commitlint-github-action/compare/v3.0.0...v3.0.1) (2021-02-25)



# [3.0.0](https://github.com/wagoid/commitlint-github-action/compare/v2.2.5...v3.0.0) (2021-02-24)


### Bug Fixes

* **deps:** udpate commitlint monorepo to v12 ([8b0b095](https://github.com/wagoid/commitlint-github-action/commit/8b0b095f5e2c4a8bc5ebc94da6e1a9c0ebc6b862)), closes [#97](https://github.com/wagoid/commitlint-github-action/issues/97)


### BREAKING CHANGES

* **deps:** Remove support for lerna v2 and change the order of the `extends` resolution
from right-to-left to left-to-right.



## [2.2.5](https://github.com/wagoid/commitlint-github-action/compare/v2.2.4...v2.2.5) (2021-02-18)



## [2.2.4](https://github.com/wagoid/commitlint-github-action/compare/v2.2.3...v2.2.4) (2021-02-17)


### Bug Fixes

* call getOctokit function instead of removed Github constructor ([84dd768](https://github.com/wagoid/commitlint-github-action/commit/84dd7685c6e51c38415801f8ca57df0578a83059))



## [2.2.3](https://github.com/wagoid/commitlint-github-action/compare/v2.2.2...v2.2.3) (2021-02-15)



## [2.2.2](https://github.com/wagoid/commitlint-github-action/compare/v2.2.1...v2.2.2) (2021-02-10)



## [2.2.1](https://github.com/wagoid/commitlint-github-action/compare/v2.2.0...v2.2.1) (2021-02-10)



# [2.2.0](https://github.com/wagoid/commitlint-github-action/compare/v2.1.7...v2.2.0) (2021-02-07)


### Features

* add outputs generation again ([a34ac47](https://github.com/wagoid/commitlint-github-action/commit/a34ac47c340ba0062e19bae66271eef6390ab03e)), closes [/github.com/actions/toolkit/issues/702#issuecomment-774269650](https://github.com//github.com/actions/toolkit/issues/702/issues/issuecomment-774269650)



## [2.1.7](https://github.com/wagoid/commitlint-github-action/compare/v2.1.6...v2.1.7) (2021-01-28)


### Bug Fixes

* remove output generation ([b674cd3](https://github.com/wagoid/commitlint-github-action/commit/b674cd3ec44b3d627899d44e7cd5c649566d291a))
* stop trying to issue commands on failures ([1128358](https://github.com/wagoid/commitlint-github-action/commit/1128358de33626153faadc9d01d0fad8bde5cfb8)), closes [#70](https://github.com/wagoid/commitlint-github-action/issues/70)



## [2.1.6](https://github.com/wagoid/commitlint-github-action/compare/v2.1.5...v2.1.6) (2020-12-16)



## [2.1.5](https://github.com/wagoid/commitlint-github-action/compare/v2.1.4...v2.1.5) (2020-12-16)



## [2.1.4](https://github.com/wagoid/commitlint-github-action/compare/v2.1.3...v2.1.4) (2020-12-03)



## [2.1.3](https://github.com/wagoid/commitlint-github-action/compare/v2.1.2...v2.1.3) (2020-11-29)



## [2.1.2](https://github.com/wagoid/commitlint-github-action/compare/v2.1.1...v2.1.2) (2020-11-21)



## [2.1.1](https://github.com/wagoid/commitlint-github-action/compare/v2.1.0...v2.1.1) (2020-11-11)


### Bug Fixes

* do not run workflow commands in commit messages ([d67c2ec](https://github.com/wagoid/commitlint-github-action/commit/d67c2ec96c0039c3cdbde4e677be13127062ed85))



# [2.1.0](https://github.com/wagoid/commitlint-github-action/compare/v2.0.5...v2.1.0) (2020-09-14)


### Features

* upgrade dependencies to their latest version ([f162ac0](https://github.com/wagoid/commitlint-github-action/commit/f162ac07f904e8b5578fa77172b997145fd61b7a))



## [2.0.5](https://github.com/wagoid/commitlint-github-action/compare/v2.0.4...v2.0.5) (2020-09-14)



## [2.0.4](https://github.com/wagoid/commitlint-github-action/compare/v2.0.3...v2.0.4) (2020-09-14)



## [2.0.3](https://github.com/wagoid/commitlint-github-action/compare/v2.0.2...v2.0.3) (2020-09-14)


### Features

* use config-conventional as default config ([7e67891](https://github.com/wagoid/commitlint-github-action/commit/7e678913ff14e04ef128e3d06523eabd0df4d639))



## [2.0.2](https://github.com/wagoid/commitlint-github-action/compare/v2.0.1...v2.0.2) (2020-08-22)



## [2.0.1](https://github.com/wagoid/commitlint-github-action/compare/v2.0.0...v2.0.1) (2020-08-20)


### Bug Fixes

* action shows error ouput when not all commits have warnings ([0911cae](https://github.com/wagoid/commitlint-github-action/commit/0911cae00990e44bafab30af5357ed057b5cf964)), closes [#43](https://github.com/wagoid/commitlint-github-action/issues/43)



# [2.0.0](https://github.com/wagoid/commitlint-github-action/compare/v1.8.0...v2.0.0) (2020-08-02)


### Features

* upgrade commitlint dependencies to v9 ([a413a3f](https://github.com/wagoid/commitlint-github-action/commit/a413a3f439c38181670fdd6d1be4b528c942af4b))
* use action input instead of env var to get the github token ([18e9bff](https://github.com/wagoid/commitlint-github-action/commit/18e9bff0e6956f1bfe76e18cc582c6cb5d3b9800))


### BREAKING CHANGES

* GITHUB_TOKEN env var is now ignored. In case a custom token is needed,
it'll be necessary to pass it via the `token` input from now on.
* this includes breaking changes from commitlint v9,
like the fact that `improvement` type is now rejected in `@commitlint/config-conventional`.



# [1.8.0](https://github.com/wagoid/commitlint-github-action/compare/v1.7.0...v1.8.0) (2020-08-02)


### Features

* add `results` output ([550792f](https://github.com/wagoid/commitlint-github-action/commit/550792f0ca7bb2cb7e9b15afee32ffead2b237e5)), closes [#39](https://github.com/wagoid/commitlint-github-action/issues/39)



# [1.7.0](https://github.com/wagoid/commitlint-github-action/compare/v1.6.0...v1.7.0) (2020-07-03)


### Performance Improvements

* improve action pull speed by using an alpine image ([d0b8181](https://github.com/wagoid/commitlint-github-action/commit/d0b8181fa4aff97a9369f2df5c1672d4afbc1e0a)), closes [#37](https://github.com/wagoid/commitlint-github-action/issues/37)



# [1.6.0](https://github.com/wagoid/commitlint-github-action/compare/v1.5.0...v1.6.0) (2020-03-11)


### Features

* upgrade to latest commitlint version ([6125fde](https://github.com/wagoid/commitlint-github-action/commit/6125fdec43ef947cadae4e84df097d400089ebbb))



# [1.5.0](https://github.com/wagoid/commitlint-github-action/compare/v1.4.0...v1.5.0) (2020-02-22)


### Features

* add support for additional dependencies ([895d9f3](https://github.com/wagoid/commitlint-github-action/commit/895d9f3f73f541076012c5572ffa9249c42aed65)), closes [#27](https://github.com/wagoid/commitlint-github-action/issues/27)



# [1.4.0](https://github.com/wagoid/commitlint-github-action/compare/v1.3.1...v1.4.0) (2020-02-14)


### Bug Fixes

* don't fail on warnings ([6e0fcb1](https://github.com/wagoid/commitlint-github-action/commit/6e0fcb1270630772518ceb183d388776739701da))
* update jira rules ([1be2ce0](https://github.com/wagoid/commitlint-github-action/commit/1be2ce0d7a4433a2774280459231bd9b2c550e06))


### Features

* add helpURL parameter ([f4821d1](https://github.com/wagoid/commitlint-github-action/commit/f4821d1c767b560567ce48a8d8d9fbc09af3c49a))



## [1.3.1](https://github.com/wagoid/commitlint-github-action/compare/v1.3.0...v1.3.1) (2019-11-30)


### Bug Fixes

* do not try to get parent of push event's "before" field ([c1bba52](https://github.com/wagoid/commitlint-github-action/commit/c1bba52d77fd4b35d15b07a6bea62c0d471be128)), closes [#18](https://github.com/wagoid/commitlint-github-action/issues/18)



# [1.3.0](https://github.com/wagoid/commitlint-github-action/compare/v1.2.3...v1.3.0) (2019-11-25)


### Features

* support opts for lint ([c1cb555](https://github.com/wagoid/commitlint-github-action/commit/c1cb555db50ed712533a81f33e925467d06a2977))



## [1.2.3](https://github.com/wagoid/commitlint-github-action/compare/v1.2.2...v1.2.3) (2019-11-24)


### Bug Fixes

* also check range of commits for push events ([aa3e7ae](https://github.com/wagoid/commitlint-github-action/commit/aa3e7ae63ba43b1a9ac061e52296a9c9624a2945))
* errors not showing when PR has only one commit ([8dd0fbf](https://github.com/wagoid/commitlint-github-action/commit/8dd0fbf821d2787f01a1eb83f410d5179e6e45a5))
* Jira rules can now be used out of the box ([6cede4b](https://github.com/wagoid/commitlint-github-action/commit/6cede4b760624a01ecc0abcdf323ce46ec551256))



## [1.2.2](https://github.com/wagoid/commitlint-github-action/compare/v1.2.1...v1.2.2) (2019-10-21)


### Bug Fixes

* set @commitlint/config-conventional to exact version 8.2.0 ([4fb9495](https://github.com/wagoid/commitlint-github-action/commit/4fb94958d723dce739c60b3e6d13ff4aebd7b8bb))
* update @commitlint/config-conventional to latest version ([bc31cec](https://github.com/wagoid/commitlint-github-action/commit/bc31cecbe8f41a27fbefe78744e0954d38d4d4d3))



## [1.2.1](https://github.com/wagoid/commitlint-github-action/compare/v1.2.0...v1.2.1) (2019-10-18)


### Bug Fixes

* also show stack when an error happens ([2c42093](https://github.com/wagoid/commitlint-github-action/commit/2c42093c709a9ccfef8e76a53d64595331627893))
* do not call `require` in the config file to allow other file types ([3559d7d](https://github.com/wagoid/commitlint-github-action/commit/3559d7d304b40cda20e697472e6d501f584d96f1))
* lerna scopes not working due to missing lerna dependency ([99b068a](https://github.com/wagoid/commitlint-github-action/commit/99b068a8442549908268790b6fdb6ceda74aee1f))
* make action name unique ([fd906ae](https://github.com/wagoid/commitlint-github-action/commit/fd906aec0b42b81b00ab19c1432598fb10551838))
* revert action to use debian image ([33f8aa3](https://github.com/wagoid/commitlint-github-action/commit/33f8aa30dd74d746436537fa50b0073a575aa53e))
* use Commit Linter as a unique action name ([dedf966](https://github.com/wagoid/commitlint-github-action/commit/dedf966fb08cdce72293ff259f57e0096a4c9f64))


### Features

* add ability to run commitlint on events that are not pull requests ([23cd801](https://github.com/wagoid/commitlint-github-action/commit/23cd801837313785b2231d6d73e294bd6edf0feb))
* add commitlint action ([478fbaf](https://github.com/wagoid/commitlint-github-action/commit/478fbaff69771fd49568dabcefde8dd86543c1fe))
* add firstParent input to ignore errors from your default branch ([598e473](https://github.com/wagoid/commitlint-github-action/commit/598e473cb441db3b8a81761f2d77f6182ce73993))
* use image from docker hub ([9379b32](https://github.com/wagoid/commitlint-github-action/commit/9379b32eb6e98429a7b2d25d47864e730d10bdc7))
