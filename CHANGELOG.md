# Changelog

All notable changes to this project will be documented in this file.

## [1.7.3](https://github.com/kieranbrown/github-actions/compare/v1.7.2...v1.7.3) (2025-06-22)


### Continuous Integration

* replace ubuntu-latest with ubuntu-24.04 ([e2646ec](https://github.com/kieranbrown/github-actions/commit/e2646ecd2999f76979a50f77fafdd8c3d4f1b477))
* **workflow-keepalive:** added workflow ([49f114c](https://github.com/kieranbrown/github-actions/commit/49f114ca0f53afc0648400d02f2151100af1fc2d))

## [1.7.2](https://github.com/kieranbrown/github-actions/compare/v1.7.1...v1.7.2) (2025-06-22)


### Miscellaneous Chores

* **deps:** update pre-commit hooks ([#52](https://github.com/kieranbrown/github-actions/issues/52)) ([e63e574](https://github.com/kieranbrown/github-actions/commit/e63e5745791eb34e7ca2b99b30e890662ad20f1f))

## [1.7.1](https://github.com/kieranbrown/github-actions/compare/v1.7.0...v1.7.1) (2025-06-22)


### Bug Fixes

* **dependabot-auto-merge:** use squash merges ([cfeac26](https://github.com/kieranbrown/github-actions/commit/cfeac26731e4e51ad21673cf1349ce42641aa6e9))


### Miscellaneous Chores

* **deps:** bump the gh-actions group across 1 directory with 6 updates ([#51](https://github.com/kieranbrown/github-actions/issues/51)) ([5705641](https://github.com/kieranbrown/github-actions/commit/5705641d938f0bc7254d01e89714157bf2dad475))


### Continuous Integration

* **dependabot-auto-merge:** added workflow ([18d4e49](https://github.com/kieranbrown/github-actions/commit/18d4e49e2dba4b452683030cd3130490325e2532))
* fix dependabot not updating actions ([6fced45](https://github.com/kieranbrown/github-actions/commit/6fced459ed5c8ad6713ff920ac42915de2d48d8f))

## [1.7.0](https://github.com/kieranbrown/github-actions/compare/v1.6.0...v1.7.0) (2025-01-26)


### Features

* **digger:** general improvements and action upgrades ([#37](https://github.com/kieranbrown/github-actions/issues/37)) ([07bdab5](https://github.com/kieranbrown/github-actions/commit/07bdab58713ea2428c15933d0a2b20faa8bb90d5))


### Miscellaneous Chores

* **deps:** bump the gh-actions group across 1 directory with 5 updates ([#41](https://github.com/kieranbrown/github-actions/issues/41)) ([8064432](https://github.com/kieranbrown/github-actions/commit/80644322f0c0e466d801b77ffcf8f634ff2dd991))


### Continuous Integration

* migrate from semantic-release to release-please ([#39](https://github.com/kieranbrown/github-actions/issues/39)) ([7dc87fe](https://github.com/kieranbrown/github-actions/commit/7dc87fed2e0b8ae81e5e24f3abcb3a9189efb2f7))

## [1.6.0](https://github.com/kieranbrown/github-actions/compare/v1.5.4...v1.6.0) (2025-01-26)


### Features

* **pre-commit-autoupdate:** added workflow ([#38](https://github.com/kieranbrown/github-actions/issues/38)) ([f99d0d4](https://github.com/kieranbrown/github-actions/commit/f99d0d4a3e9bd16115979e22625f854db12564f0))

## [1.5.4](https://github.com/kieranbrown/github-actions/compare/v1.5.3...v1.5.4) (2024-09-02)


### Miscellaneous Chores

* **deps:** bump the gh-actions group across 1 directory with 4 updates ([#25](https://github.com/kieranbrown/github-actions/issues/25)) ([d50f1a8](https://github.com/kieranbrown/github-actions/commit/d50f1a82e26583728231f24aa3f45eb31deec5ba))

## [1.5.3](https://github.com/kieranbrown/github-actions/compare/v1.5.2...v1.5.3) (2024-08-19)


### Miscellaneous Chores

* **deps:** bump the gh-actions group across 1 directory with 5 updates ([#23](https://github.com/kieranbrown/github-actions/issues/23)) ([64d75b8](https://github.com/kieranbrown/github-actions/commit/64d75b83597944c0a8a32c1fdb374560668e9a89))

## [1.5.2](https://github.com/kieranbrown/github-actions/compare/v1.5.1...v1.5.2) (2024-04-30)


### Miscellaneous Chores

* **deps:** bump the gh-actions group across 1 directory with 4 updates ([#10](https://github.com/kieranbrown/github-actions/issues/10)) ([4a078d3](https://github.com/kieranbrown/github-actions/commit/4a078d3803e2b9b98dffde7720f77e8ddf02ba49))

## [1.5.1](https://github.com/kieranbrown/github-actions/compare/v1.5.0...v1.5.1) (2024-04-30)


### Bug Fixes

* **digger-job:** sts requests failing due to missing region ([ab16988](https://github.com/kieranbrown/github-actions/commit/ab16988a187d240bdb868482b494c3baec385e08))

## [1.5.0](https://github.com/kieranbrown/github-actions/compare/v1.4.1...v1.5.0) (2024-04-30)


### Features

* **digger-job:** enable dependency caching ([4494e92](https://github.com/kieranbrown/github-actions/commit/4494e922beaa83984f62d6ebaf521f73bf123ad8))

## [1.4.1](https://github.com/kieranbrown/github-actions/compare/v1.4.0...v1.4.1) (2024-04-18)


### Code Refactors

* replace underscore with hyphen in workflow file names ([ad0783a](https://github.com/kieranbrown/github-actions/commit/ad0783ab5a69d1ead8383f5b737a9c3727b42184))

## [1.4.0](https://github.com/kieranbrown/github-actions/compare/v1.3.0...v1.4.0) (2024-04-17)


### Features

* run terraform and terragrunt non-interactive ([7116a5b](https://github.com/kieranbrown/github-actions/commit/7116a5bb397c1047f84111d201b77402369c9aae))

## [1.3.0](https://github.com/kieranbrown/github-actions/compare/v1.2.0...v1.3.0) (2024-04-14)


### Features

* **digger_job:** added aws assume role support ([#7](https://github.com/kieranbrown/github-actions/issues/7)) ([6cf10ab](https://github.com/kieranbrown/github-actions/commit/6cf10ab3aa9029aecb5e68da5b41034ff928e2e3))

## [1.2.0](https://github.com/kieranbrown/github-actions/compare/v1.1.5...v1.2.0) (2024-04-14)


### Features

* **digger_job:** install and configure tgenv ([#1](https://github.com/kieranbrown/github-actions/issues/1)) ([b6ecefa](https://github.com/kieranbrown/github-actions/commit/b6ecefa57f73c1aeed73457b48e4d58d25324636))

## [1.1.5](https://github.com/kieranbrown/github-actions/compare/v1.1.4...v1.1.5) (2024-04-14)


### Bug Fixes

* **digger_job:** fix error when there are no vars or secrets to export ([7072586](https://github.com/kieranbrown/github-actions/commit/707258683e0fd11e0f9b05aa72ffe6683d421196))

## [1.1.4](https://github.com/kieranbrown/github-actions/compare/v1.1.3...v1.1.4) (2024-04-14)


### Bug Fixes

* **digger_job:** fix error when there are no vars or secrets to export ([bb10d64](https://github.com/kieranbrown/github-actions/commit/bb10d64cc06871f82f1e85100d2d6a7b640f1dfb))

## [1.1.3](https://github.com/kieranbrown/github-actions/compare/v1.1.2...v1.1.3) (2024-04-14)


### Miscellaneous Chores

* **deps:** bump the gh-actions group with 4 updates ([#6](https://github.com/kieranbrown/github-actions/issues/6)) ([92e941e](https://github.com/kieranbrown/github-actions/commit/92e941e9a9739335c19fc64a27b0cc5ae0123d85))


### CI/CD

* fix invalid dependabot syntax ([09b9c5b](https://github.com/kieranbrown/github-actions/commit/09b9c5b5e37d34ec5fac1af484bfb4d881a7f5c2))
* group dependabot pull requests ([d2518c8](https://github.com/kieranbrown/github-actions/commit/d2518c800e3da962bc28f0cca901d43dfbecdd55))

## [1.1.2](https://github.com/kieranbrown/github-actions/compare/v1.1.1...v1.1.2) (2024-04-10)


### Bug Fixes

* **digger_workflow:** do not cleanup when doing targetted applies ([286e13c](https://github.com/kieranbrown/github-actions/commit/286e13cac3259f03127c47efaa9ea4f14dc585e8))

## [1.1.1](https://github.com/kieranbrown/github-actions/compare/v1.1.0...v1.1.1) (2024-04-04)


### Bug Fixes

* **digger_job:** not restoring correct artifact on issue comments ([c96b6da](https://github.com/kieranbrown/github-actions/commit/c96b6dad7f2611153d040aaad08c30a975db9f02))

## [1.1.0](https://github.com/kieranbrown/github-actions/compare/v1.0.3...v1.1.0) (2024-04-03)


### Features

* **digger_job:** persist lambda build artifacts ([18b4f1f](https://github.com/kieranbrown/github-actions/commit/18b4f1f086f6c32100ba79cec15c1f55d0572439))

## [1.0.3](https://github.com/kieranbrown/github-actions/compare/v1.0.2...v1.0.3) (2024-04-03)


### CI/CD

* **digger_job:** bump action version to 0.4.13 ([98b2446](https://github.com/kieranbrown/github-actions/commit/98b24464ba309712fad437a9bacb431d97295fbc))

## [1.0.2](https://github.com/kieranbrown/github-actions/compare/v1.0.1...v1.0.2) (2024-03-03)


### Bug Fixes

* **digger_job:** fix failure when slack webhook url is missing ([d95b884](https://github.com/kieranbrown/github-actions/commit/d95b884472567b788a1621c8291ca10c5e02b5b5))

## [1.0.1](https://github.com/kieranbrown/github-actions/compare/v1.0.0...v1.0.1) (2024-03-03)


### Bug Fixes

* **digger_workflow:** fix failure when slack webhook url is missing ([a5307a9](https://github.com/kieranbrown/github-actions/commit/a5307a9ecbac1cff42df70a56e3190dba91b02fe))


### Code Refactors

* **digger_workflow:** moved user comment guarding from main workflow into guard workflow ([c5d049e](https://github.com/kieranbrown/github-actions/commit/c5d049ee9475db52b279dec32c649581177069b5))

## 1.0.0 (2024-03-03)


### Features

* initial commit ([6386a21](https://github.com/kieranbrown/github-actions/commit/6386a21ec55c5a27f173e73e1b1e7f00a3877345))
