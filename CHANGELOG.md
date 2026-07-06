# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [3.0.1](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v3.0.0...v3.0.1) (2026-02-09)


### 🐛 Fixes

* terraform tests ([#39](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/39)) ([02cbef5](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/02cbef5c86c30150d5c489a721f3a01ac6460e61))

## [3.0.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.7.1...v3.0.0) (2026-02-09)


### ⚠ BREAKING CHANGES

* Remove deprecated vars trigger_prefixes and workspace_tags ([#38](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/38))

### 🚀 Features

* Remove deprecated vars trigger_prefixes and workspace_tags ([#38](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/38)) ([9db5417](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/9db5417a5c4ed3146baa00b80d8229d7264449f7))

## [2.7.1](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.7.0...v2.7.1) (2025-11-28)


### 🐛 Fixes

* clarify VCS-mode trigger behaviour and make trigger logic fully null-safe ([#37](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/37)) ([92a90e5](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/92a90e5ed9768f447349c6d9463d6f0155320915))

## [2.7.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.6.0...v2.7.0) (2025-11-20)


### 🚀 Features

* Improve trigger pattern flexibility and simplify logic ([#36](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/36)) ([b78e72f](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/b78e72ff083ead626afbf7130834fc5ebd60a821))

## [2.6.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.5.0...v2.6.0) (2025-11-18)


### 🚀 Features

* add variables related to tags and ephemeral workspaces ([#34](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/34)) ([12cb04f](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/12cb04f863323c693906c46f85fc1f7571b04ec9))

### 🐛 Fixes

* rename tags to workspace_map_tags ([#35](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/35)) ([f8065dd](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/f8065ddabd24f0dcf89bae54b0d149a50c48a500))

## [2.5.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.4.0...v2.5.0) (2025-07-17)


### 🚀 Features

* Add `github-vcs` and `gitlab-vcs` submodules ([#31](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/31)) ([eb11827](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/eb11827d2e23dd6c6d090c4419c341cede784eeb))

### 🐛 Fixes

* Make `var.terraform_organization` optional ([#32](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/32)) ([6603d0c](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/6603d0c5c9106fa3d4d521d48340efd8faca98ea))
* Correct file trigger logic and update default trigger patterns ([#29](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/29)) ([616a529](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/616a52966099ca469ee88e7164303b806ffd94f2))

## [2.4.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.3.1...v2.4.0) (2025-03-14)


### 🐛 Fixes

* invalid for_each argument error in TF 1.10.0+ when notification configuration url is marked sensitive ([#26](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/26)) ([399f979](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/399f97981b9c0b92bad32ab1cdd11d461d18d269))

## [2.3.1](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.3.0...v2.3.1) (2025-02-24)


### 🐛 Fixes

* bug: trigger patterns could be null ([#25](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/25)) ([b6ab978](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/b6ab978f01330b277a23e2fa21880071cd4381de))

## [2.3.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.2.0...v2.3.0) (2025-02-24)


### 🚀 Features

* enhancement: move trigger_prefix default values to trigger_patterns ([#24](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/24)) ([701a0b2](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/701a0b244456e59b3f881bc2cb13944948ab0006))

## [2.2.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.1.1...v2.2.0) (2025-01-28)


### 🚀 Features

* Add speculative_enabled option ([#23](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/23)) ([60e532b](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/60e532b06ceedac7536ad4c6f76e1a7d60656079))

## [2.1.1](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.1.0...v2.1.1) (2024-12-13)


### 🐛 Fixes

* Fix deprecation ([#22](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/22)) ([aa4c887](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/aa4c887a8750eb380476f34407ec1efe65dfa467))

## [2.1.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v2.0.0...v2.1.0) (2024-12-11)


### 🚀 Features

* Support GitHub app for VCS connections ([#21](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/21)) ([288ee69](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/288ee690b2c4566eb1681d3e19ed87df7dcdef75))

## [2.0.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v1.0.0...v2.0.0) (2024-08-23)


### 🚀 Features

* breaking: Sync changes from terrraform-aws-mcaf-workspace to this repo ([#20](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/20)) ([530e631](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/530e63196daddafc0fd0f2312ae083452e790877))

## [1.0.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.5.0...v1.0.0) (2024-01-30)


### 🚀 Features

* breaking: improve team access settings ([#18](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/18)) ([4298874](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/4298874b89d6b87a6de602f6a80f8fd67e082d80))

## [0.5.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.4.1...v0.5.0) (2024-01-30)


### 🚀 Features

* add central workflow, make repository_identifier optional, fix bug in workspace_tags ([#19](https://github.com/schubergphilis/terraform-tfe-mcaf-workspace/pull/19)) ([5d56503](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/commit/5d565031a6319fb688d403c389987d2844ade205))

## [0.4.1](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.4.0...v0.4.1) (2024-01-30)

## [0.4.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.3.3...v0.4.0) (2024-01-11)

## [0.3.3](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.3.2...v0.3.3) (2023-11-10)

## [0.3.2](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.3.1...v0.3.2) (2023-01-26)

## [0.3.1](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.3.0...v0.3.1) (2022-10-14)

## [0.3.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.2.0...v0.3.0) (2022-04-27)

## [0.2.0](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.1.4...v0.2.0) (2021-09-17)

## [0.1.4](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.1.3...v0.1.4) (2021-06-22)

## [0.1.3](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.1.2...v0.1.3) (2021-05-03)

## [0.1.2](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.1.1...v0.1.2) (2020-12-30)

## [0.1.1](https://github.com/schubergphilis-ep/terraform-tfe-mcaf-workspace/compare/v0.1.0...v0.1.1) (2020-07-20)

## 0.1.0 (2020-02-20)

