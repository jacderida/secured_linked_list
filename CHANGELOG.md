# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.5.2](https://github.com/maidsafe/secured_linked_list/compare/v0.5.1...v0.5.2) (2022-06-14)

### [0.5.1](https://github.com/maidsafe/secured_linked_list/compare/v0.5.0...v0.5.1) (2022-05-15)

## [0.5.0](https://github.com/maidsafe/secured_linked_list/compare/v0.4.0...v0.5.0) (2021-11-14)


### ⚠ BREAKING CHANGES

* **api:** the 'merge' public API was renamed to 'join'

### Bug Fixes

* **api:** get_proof_chain was returning a subchain with forks in some cases ([a5b282e](https://github.com/maidsafe/secured_linked_list/commit/a5b282ef1bcc4c4b5d12e421b5014011916e28c1))

## [0.4.0](https://github.com/maidsafe/secured_linked_list/compare/v0.3.1...v0.4.0) (2021-11-11)


### ⚠ BREAKING CHANGES

* blsttc->3.4.0

* blsttc->3.4.0 ([24f4556](https://github.com/maidsafe/secured_linked_list/commit/24f4556b5f3a9e448756ccfdb211c71c79932b92))

### [0.3.1](https://github.com/maidsafe/secured_linked_list/compare/v0.3.0...v0.3.1) (2021-07-29)


### Features

* add self_verify API which checks every key in the chain is proven (signed) by its parent key ([9f14e7b](https://github.com/maidsafe/secured_linked_list/commit/9f14e7bccf8bbd24c3190dc019671a3fa0c6bf38))

## [0.3.0](https://github.com/maidsafe/secured_linked_list/compare/v0.2.0...v0.3.0) (2021-06-30)


### ⚠ BREAKING CHANGES

* **blsttc:** this enables blsttc to run on older cpu architectures

### Features

* **blsttc:** update blsttc ([f8d167c](https://github.com/maidsafe/secured_linked_list/commit/f8d167c7bd7568ec627beb6110173311f93fb028))

## [0.2.0](https://github.com/maidsafe/secured_linked_list/compare/v0.1.3...v0.2.0) (2021-06-29)


### ⚠ BREAKING CHANGES

* updates to use blsstc

### Features

* introducing blsstc ([731cbe4](https://github.com/maidsafe/secured_linked_list/commit/731cbe4a7ffea73fc07bbea0b8786732c7c50ccb))

### [0.1.3](https://github.com/maidsafe/secured_linked_list/compare/v0.1.2...v0.1.3) (2021-06-28)


### Bug Fixes

* use blsttc instead of threshold_crypto ([38e2307](https://github.com/maidsafe/secured_linked_list/commit/38e23074359c1eb7514d91d86eaa7ad8a6dd819f))

### [0.1.2](https://github.com/maidsafe/secured_linked_list/compare/v0.1.1...v0.1.2) (2021-06-15)

### [0.1.1](https://github.com/maidsafe/secured_linked_list/compare/v0.1.0...v0.1.1) (2021-05-26)

## [0.1.0](https://github.com/maidsafe/secured_linked_list/compare/v0.1.0...v0.1.0) (2021-05-25)

* Initial commit.
