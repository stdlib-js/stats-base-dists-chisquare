# CHANGELOG

> Package changelog.

<section class="release" id="v0.3.1">

## 0.3.1 (2026-02-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.3.0">

## 0.3.0 (2026-01-30)

<section class="features">

### Features

-   [`409bec4`](https://github.com/stdlib-js/stdlib/commit/409bec42b05a23d1527fd82696e1a05660daa8a3) - add C implementation for `stats/base/dists/chisquare/cdf`
-   [`267ba17`](https://github.com/stdlib-js/stdlib/commit/267ba17121461b7cb1e8ddbc963b107319d38ebe) - add C implementation for `stats/base/dists/chisquare/kurtosis` [(#4592)](https://github.com/stdlib-js/stdlib/pull/4592)
-   [`ccaed30`](https://github.com/stdlib-js/stdlib/commit/ccaed309a4bfdc50b0c8f2c78f1ee4e365d51337) - add C implementation for `stats/base/dists/chisquare/variance` [(#3999)](https://github.com/stdlib-js/stdlib/pull/3999)
-   [`292c21e`](https://github.com/stdlib-js/stdlib/commit/292c21e986d7d432d7caee7ce89392e69cd72e5e) - add C implementation for `stats/base/dists/chisquare/mode` [(#4002)](https://github.com/stdlib-js/stdlib/pull/4002)
-   [`3f740e8`](https://github.com/stdlib-js/stdlib/commit/3f740e88f3d1e0a42e50e351603a0d4eb0e9cf2e) - add C implementation for `stats/base/dists/chisquare/stdev` [(#3996)](https://github.com/stdlib-js/stdlib/pull/3996)
-   [`2b91a43`](https://github.com/stdlib-js/stdlib/commit/2b91a43344d32f63fd50185d17fadf13e9c977a7) - add C implementation for `stats/base/dists/chisquare/mean` [(#3989)](https://github.com/stdlib-js/stdlib/pull/3989)
-   [`6def8d6`](https://github.com/stdlib-js/stdlib/commit/6def8d6af0309beb3e207ae21b4266f142edfa48) - add C implementation for `stats/base/dists/chisquare/mgf` [(#4593)](https://github.com/stdlib-js/stdlib/pull/4593)
-   [`118284b`](https://github.com/stdlib-js/stdlib/commit/118284b97293f409c1769047675bed85ddf4dd20) - add C implementation for `stats/base/dists/chisquare/skewness` [(#4005)](https://github.com/stdlib-js/stdlib/pull/4005)
-   [`7a87244`](https://github.com/stdlib-js/stdlib/commit/7a872442e344e03a69d987f0f7b89d1344d5547c) - add C implementation for `stats/base/dists/chisquare/entropy` [(#4007)](https://github.com/stdlib-js/stdlib/pull/4007)

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`efe801c`](https://github.com/stdlib-js/stdlib/commit/efe801c057e0fb3ad2327f6df6e3627d76964602) - remove unused `sqrt` and `eps` dependencies from `chisquare/variance` manifest

</section>

<!-- /.bug-fixes -->

<section class="issues">

### Closed Issues

A total of 9 issues were closed in this release:

[#1619](https://github.com/stdlib-js/stdlib/issues/1619), [#3501](https://github.com/stdlib-js/stdlib/issues/3501), [#3502](https://github.com/stdlib-js/stdlib/issues/3502), [#3504](https://github.com/stdlib-js/stdlib/issues/3504), [#3506](https://github.com/stdlib-js/stdlib/issues/3506), [#3507](https://github.com/stdlib-js/stdlib/issues/3507), [#3510](https://github.com/stdlib-js/stdlib/issues/3510), [#3511](https://github.com/stdlib-js/stdlib/issues/3511), [#3512](https://github.com/stdlib-js/stdlib/issues/3512)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`a27671f`](https://github.com/stdlib-js/stdlib/commit/a27671f8fc907e4f054086e3e422234ed56964cd) - **docs:** update string interpolation in various `stats/base/dists` examples [(#9533)](https://github.com/stdlib-js/stdlib/pull/9533) _(by Harsh Yadav)_
-   [`97218a1`](https://github.com/stdlib-js/stdlib/commit/97218a12e1d5ec1479a5b39ac4d32318c372e922) - **docs:** fix TSDoc example code return annotations _(by Philipp Burckhardt)_
-   [`e2efe32`](https://github.com/stdlib-js/stdlib/commit/e2efe32914d0d9dae5da34e6f7e7bf7655430710) - **chore:** rename exported variable in d.ts file to match name used in example code _(by Philipp Burckhardt)_
-   [`776887e`](https://github.com/stdlib-js/stdlib/commit/776887e9577ae2402fd69c97328cb864811bd120) - **docs:** update annotation values _(by Philipp Burckhardt)_
-   [`7add020`](https://github.com/stdlib-js/stdlib/commit/7add0201c13e56a0381926ccfd4073c84eaf2ed4) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`fc438e0`](https://github.com/stdlib-js/stdlib/commit/fc438e0edbad0689d6923d6f3edb959b96597662) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`07f7c05`](https://github.com/stdlib-js/stdlib/commit/07f7c0522c73e6ad9505e1d45035ae439344200d) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`9c21fd2`](https://github.com/stdlib-js/stdlib/commit/9c21fd20ef8b8a6a88abb96d80ea6d8e4c5434eb) - **test:** use .strictEqual() instead of .equal() _(by Philipp Burckhardt)_
-   [`8ea46b6`](https://github.com/stdlib-js/stdlib/commit/8ea46b662dc6e27231d250d101e33a3cf770cd77) - **test:** update descriptions to match language used in JS tests _(by Philipp Burckhardt)_
-   [`7e24b8b`](https://github.com/stdlib-js/stdlib/commit/7e24b8ba0fff87a56584bb1a2fa106eb88267596) - **test:** slightly increase tolerances for passing tests _(by Philipp Burckhardt)_
-   [`c698e73`](https://github.com/stdlib-js/stdlib/commit/c698e73a6365ec5d828861bb26a6e3bb74fb1af8) - **chore:** add missing eps dependency to benchmark and examples configs _(by Philipp Burckhardt)_
-   [`409bec4`](https://github.com/stdlib-js/stdlib/commit/409bec42b05a23d1527fd82696e1a05660daa8a3) - **feat:** add C implementation for `stats/base/dists/chisquare/cdf` _(by Philipp Burckhardt)_
-   [`efe801c`](https://github.com/stdlib-js/stdlib/commit/efe801c057e0fb3ad2327f6df6e3627d76964602) - **fix:** remove unused `sqrt` and `eps` dependencies from `chisquare/variance` manifest _(by Philipp Burckhardt)_
-   [`bab1647`](https://github.com/stdlib-js/stdlib/commit/bab1647c1309043335a7ec9badb8f3e629bf9136) - **style:** add missing space _(by Athan Reines)_
-   [`2e9da74`](https://github.com/stdlib-js/stdlib/commit/2e9da74a9f19a2090b8405b54553baa7fb715c27) - **docs:** replace manual `for` loop in examples [(#7056)](https://github.com/stdlib-js/stdlib/pull/7056) _(by Harsh Yadav)_
-   [`ce62b14`](https://github.com/stdlib-js/stdlib/commit/ce62b1490d4948a707f496b66ad03bb296a2468a) - **docs:** replace manual `for` loop in examples [(#7055)](https://github.com/stdlib-js/stdlib/pull/7055) _(by Harsh Yadav)_
-   [`367fdcd`](https://github.com/stdlib-js/stdlib/commit/367fdcd966fd9b6c883997b6f0deebbe84a63cbd) - **bench:** update random value generation [(#7026)](https://github.com/stdlib-js/stdlib/pull/7026) _(by Harsh Yadav)_
-   [`4a896f3`](https://github.com/stdlib-js/stdlib/commit/4a896f34e9a1bd41102d45f4de71992ce85fab5f) - **bench:** update random value generation [(#7027)](https://github.com/stdlib-js/stdlib/pull/7027) _(by Harsh Yadav)_
-   [`a1e230f`](https://github.com/stdlib-js/stdlib/commit/a1e230f29297caa89880e9c194c615a0400fb7bc) - **chore:** clean up cppcheck-suppress comments _(by Karan Anand)_
-   [`f7988d3`](https://github.com/stdlib-js/stdlib/commit/f7988d3c02e0eff3bd9bd7523b5dc975bb98dc0e) - **bench:** fix `isnan` checks in `stats/base/dists` [(#5296)](https://github.com/stdlib-js/stdlib/pull/5296) _(by Karan Anand)_
-   [`911e179`](https://github.com/stdlib-js/stdlib/commit/911e1793885aced96a177f2ea54300503b2c2a26) - **docs:** clean-up of C docstrings _(by Philipp Burckhardt)_
-   [`e61b1de`](https://github.com/stdlib-js/stdlib/commit/e61b1dee3334bacf30d213de5b5f1c7868c0753b) - **docs:** clean-up of C docstrings _(by Philipp Burckhardt)_
-   [`267ba17`](https://github.com/stdlib-js/stdlib/commit/267ba17121461b7cb1e8ddbc963b107319d38ebe) - **feat:** add C implementation for `stats/base/dists/chisquare/kurtosis` [(#4592)](https://github.com/stdlib-js/stdlib/pull/4592) _(by Karan Anand, Philipp Burckhardt, stdlib-bot)_
-   [`02b9077`](https://github.com/stdlib-js/stdlib/commit/02b907765ad6a6ebcc884f16f2128475ab866814) - **bench:** refactor random number generation in `stats/base/dists/chisquare` [(#4860)](https://github.com/stdlib-js/stdlib/pull/4860) _(by Karan Anand)_
-   [`177f0a0`](https://github.com/stdlib-js/stdlib/commit/177f0a00909c097be05d47107a3e6ab05b865409) - **chore:** consistently use differential entropy for continuous distributions _(by Philipp Burckhardt)_
-   [`f75a0ce`](https://github.com/stdlib-js/stdlib/commit/f75a0cef6a3112b166dba04c13bada9763cec350) - **chore:** use excess kurtosis consistently _(by Philipp Burckhardt)_
-   [`c4bdf1c`](https://github.com/stdlib-js/stdlib/commit/c4bdf1c73fcd8c5534b13873a4a9d632ba1444c8) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`ff97e29`](https://github.com/stdlib-js/stdlib/commit/ff97e29be19b90e74565d410af768774bf96bf2e) - **chore:** update wording from non-negative to nonnegative _(by Philipp Burckhardt)_
-   [`c4ef550`](https://github.com/stdlib-js/stdlib/commit/c4ef5500174a0d77a90b1a72be560938ac56d58d) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`ccaed30`](https://github.com/stdlib-js/stdlib/commit/ccaed309a4bfdc50b0c8f2c78f1ee4e365d51337) - **feat:** add C implementation for `stats/base/dists/chisquare/variance` [(#3999)](https://github.com/stdlib-js/stdlib/pull/3999) _(by Vivek Maurya, Philipp Burckhardt, stdlib-bot)_
-   [`292c21e`](https://github.com/stdlib-js/stdlib/commit/292c21e986d7d432d7caee7ce89392e69cd72e5e) - **feat:** add C implementation for `stats/base/dists/chisquare/mode` [(#4002)](https://github.com/stdlib-js/stdlib/pull/4002) _(by Vivek Maurya, Philipp Burckhardt, stdlib-bot)_
-   [`3f740e8`](https://github.com/stdlib-js/stdlib/commit/3f740e88f3d1e0a42e50e351603a0d4eb0e9cf2e) - **feat:** add C implementation for `stats/base/dists/chisquare/stdev` [(#3996)](https://github.com/stdlib-js/stdlib/pull/3996) _(by Vivek Maurya, Philipp Burckhardt, stdlib-bot)_
-   [`2b91a43`](https://github.com/stdlib-js/stdlib/commit/2b91a43344d32f63fd50185d17fadf13e9c977a7) - **feat:** add C implementation for `stats/base/dists/chisquare/mean` [(#3989)](https://github.com/stdlib-js/stdlib/pull/3989) _(by Vivek Maurya, Philipp Burckhardt, stdlib-bot)_
-   [`1d5aa47`](https://github.com/stdlib-js/stdlib/commit/1d5aa47204c258b674d3db4aec92fbd2475e5ea7) - **chore:** directly draw from the desired distribution instead of adding constants _(by Philipp Burckhardt)_
-   [`6def8d6`](https://github.com/stdlib-js/stdlib/commit/6def8d6af0309beb3e207ae21b4266f142edfa48) - **feat:** add C implementation for `stats/base/dists/chisquare/mgf` [(#4593)](https://github.com/stdlib-js/stdlib/pull/4593) _(by Karan Anand, Philipp Burckhardt, stdlib-bot)_
-   [`118284b`](https://github.com/stdlib-js/stdlib/commit/118284b97293f409c1769047675bed85ddf4dd20) - **feat:** add C implementation for `stats/base/dists/chisquare/skewness` [(#4005)](https://github.com/stdlib-js/stdlib/pull/4005) _(by Vivek Maurya, Philipp Burckhardt)_
-   [`7a87244`](https://github.com/stdlib-js/stdlib/commit/7a872442e344e03a69d987f0f7b89d1344d5547c) - **feat:** add C implementation for `stats/base/dists/chisquare/entropy` [(#4007)](https://github.com/stdlib-js/stdlib/pull/4007) _(by Vivek Maurya, Philipp Burckhardt)_
-   [`28bdda3`](https://github.com/stdlib-js/stdlib/commit/28bdda3affa89470bbdf531cb3bbc233c85d3d17) - **docs:** improve examples of `stats/base/dists/chisquare` namespace [(#2678)](https://github.com/stdlib-js/stdlib/pull/2678) _(by Kohantika Nath, Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 6 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Harsh Yadav
-   Karan Anand
-   Kohantika Nath
-   Philipp Burckhardt
-   Vivek Maurya

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.2">

## 0.2.2 (2024-07-28)

<section class="commits">

### Commits

<details>

-   [`41d41e9`](https://github.com/stdlib-js/stdlib/commit/41d41e959b4eaad3c631e6898e3144a4015a5458) - **test:** include trailing newlines in Julia-generated JSON fixtures _(by Philipp Burckhardt)_
-   [`9ed7d0e`](https://github.com/stdlib-js/stdlib/commit/9ed7d0e7d57edb5ad0dfb65c944bed87d475cbf3) - **chore:** add missing trailing newlines _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.1">

## 0.2.1 (2024-02-24)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2024-02-14)

<section class="commits">

### Commits

<details>

-   [`9502ed2`](https://github.com/stdlib-js/stdlib/commit/9502ed27e2853e312c556a48bdd7775095e66709) - **build:** replace tslint directive with eslint equivalent _(by Philipp Burckhardt)_
-   [`d73bbf4`](https://github.com/stdlib-js/stdlib/commit/d73bbf43d222f935085f8ecf7526e5f57835f74e) - **build:** replace lint directives _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2023-09-24)

<section class="features">

### Features

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - **feat:** update minimum TypeScript version _(by Philipp Burckhardt)_
-   [`d5fa8e8`](https://github.com/stdlib-js/stdlib/commit/d5fa8e8a6267a837a25a7027e9fe3e847bc2d1c5) - **test:** use strictEqual checks _(by Philipp Burckhardt)_
-   [`ce7e336`](https://github.com/stdlib-js/stdlib/commit/ce7e3367c0f9477773fe76dd0eca64dc6ad33c02) - **docs:** update equations _(by Philipp Burckhardt)_
-   [`37f032d`](https://github.com/stdlib-js/stdlib/commit/37f032d4a571f667ea99f6f52f60b5d736c627f3) - **docs:** render equations via math code blocks _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.0.7">

## 0.0.7 (2022-07-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.6">

## 0.0.6 (2022-02-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.5">

## 0.0.5 (2021-08-22)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.4">

## 0.0.4 (2021-07-07)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.3">

## 0.0.3 (2021-06-28)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.2">

## 0.0.2 (2021-06-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.1">

## 0.0.1 (2021-06-15)

No changes reported for this release.

</section>

<!-- /.release -->

