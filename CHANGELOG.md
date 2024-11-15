# Changelog

## [2.0.0](https://github.com/kodiakseraphim/p8-static-search-portal/compare/v1.5.0...2.0.0) (2024-11-15)


### ⚠ BREAKING CHANGES

* Use in-memory based storage for authorization tokens, by default. ([#235](https://github.com/kodiakseraphim/p8-static-search-portal/issues/235))

### Features

* add support for 'links' on Results ([943f89d](https://github.com/kodiakseraphim/p8-static-search-portal/commit/943f89d1ae958a36af94b3d9939502ad62c87083))
* adds 'table' field type and scaffold for JSONTree component ([a539724](https://github.com/kodiakseraphim/p8-static-search-portal/commit/a5397242abd89b28b4388476dfb3cbf533490c13))
* adds "globus.embed" field type support ([#243](https://github.com/kodiakseraphim/p8-static-search-portal/issues/243)) ([baa2d7e](https://github.com/kodiakseraphim/p8-static-search-portal/commit/baa2d7ee8b5271b1d58d6455e5096e077c19aecd))
* adds ability for theming via static.json file ([827c256](https://github.com/kodiakseraphim/p8-static-search-portal/commit/827c2562008b4fccf64fb4e06c166d19c9bdbfb5))
* adds basic pagination and improved loading state ([#37](https://github.com/kodiakseraphim/p8-static-search-portal/issues/37)) ([ef577e1](https://github.com/kodiakseraphim/p8-static-search-portal/commit/ef577e1f67a6447b29e771324c1c0c4da9ad8607))
* adds core generator utilities, packages, and configuration ([9265bdb](https://github.com/kodiakseraphim/p8-static-search-portal/commit/9265bdb38a462e194724e48c7c9252fd820f2af3))
* Adds JSON Renderer for Globus Embeds ([#262](https://github.com/kodiakseraphim/p8-static-search-portal/issues/262)) ([dfd7aa0](https://github.com/kodiakseraphim/p8-static-search-portal/commit/dfd7aa08065ce64d2dd1d6a057a4d7dbaa5b420c))
* adds release-please GitHub Action ([c64f033](https://github.com/kodiakseraphim/p8-static-search-portal/commit/c64f03336806b666364033862ea3003e845a5559))
* adds support for "content" directory and landing page customization ([#189](https://github.com/kodiakseraphim/p8-static-search-portal/issues/189)) ([63b3319](https://github.com/kodiakseraphim/p8-static-search-portal/commit/63b3319c808cb06e52cbcbea624b6407796f7b45))
* Adds support for `features.requireAuthentication` – this will update built-in routes to prompt for authentication before any information is displayed. This feature is useful for mostly/completely private Globus Search indicies. ([abdd9cf](https://github.com/kodiakseraphim/p8-static-search-portal/commit/abdd9cff0c03724326dd98fcc070de36126c8f57))
* adds support for globus.search.facet to generate filter UI based on configured facets and responses from the index ([#28](https://github.com/kodiakseraphim/p8-static-search-portal/issues/28)) ([c0cce3b](https://github.com/kodiakseraphim/p8-static-search-portal/commit/c0cce3b455f2d1e44233cb47fd4c02da24fa060c))
* adds support for jsonata based references in static.json ([#47](https://github.com/kodiakseraphim/p8-static-search-portal/issues/47)) ([6232a8b](https://github.com/kodiakseraphim/p8-static-search-portal/commit/6232a8bdfc2c51baed343781a219322b31ebdbd9))
* adds support for rendering embedded Globus assets as a Plotly graph or chart ([#248](https://github.com/kodiakseraphim/p8-static-search-portal/issues/248)) ([272e4a6](https://github.com/kodiakseraphim/p8-static-search-portal/commit/272e4a675c3e9008e90107cd68a41c15b61dfb79))
* Adds support for rendering fields a links. ([#212](https://github.com/kodiakseraphim/p8-static-search-portal/issues/212)) ([889d966](https://github.com/kodiakseraphim/p8-static-search-portal/commit/889d966bcbef78fa38a86c28eabf3bdf2ef843f9))
* Allows configuration of custom navigation using "attributes.content.navigation" ([#205](https://github.com/kodiakseraphim/p8-static-search-portal/issues/205)) ([e9356b8](https://github.com/kodiakseraphim/p8-static-search-portal/commit/e9356b8733ccef5ab18f75136aceb2da32453bb6))
* Basic support Image and RGBA fields. ([4d6c290](https://github.com/kodiakseraphim/p8-static-search-portal/commit/4d6c2904613c106fbff61685dd8543c3522576cf))
* generic result rendering ([d2fbf9e](https://github.com/kodiakseraphim/p8-static-search-portal/commit/d2fbf9e6982c89906d8c236399404f15375aa9f8))
* improved image and rgba rendering ([b41c8cf](https://github.com/kodiakseraphim/p8-static-search-portal/commit/b41c8cfc504d92cec6d37586c7831405241402f3))
* Improves "globus.embed" behaviors ([#253](https://github.com/kodiakseraphim/p8-static-search-portal/issues/253)) ([57a5a25](https://github.com/kodiakseraphim/p8-static-search-portal/commit/57a5a25bfd3dfca798d122acd660d776a82ecd9e))
* Improves JSON rendering via react-json-view ([#260](https://github.com/kodiakseraphim/p8-static-search-portal/issues/260)) ([59b6fc1](https://github.com/kodiakseraphim/p8-static-search-portal/commit/59b6fc10e8d10566a19e709adc198371695acf57))
* Introduces authorization feature. ([4d6c290](https://github.com/kodiakseraphim/p8-static-search-portal/commit/4d6c2904613c106fbff61685dd8543c3522576cf))
* ResultListing now supports a `image` property. ([4d6c290](https://github.com/kodiakseraphim/p8-static-search-portal/commit/4d6c2904613c106fbff61685dd8543c3522576cf))
* supports dynamic component configuration ([d69c034](https://github.com/kodiakseraphim/p8-static-search-portal/commit/d69c034d66bdfa0b94f6d1e8636408157d9841b4))
* switch back to onChange search behaviors, improved error handling ([8ba1ec2](https://github.com/kodiakseraphim/p8-static-search-portal/commit/8ba1ec2ce7ae6bad33269262cd70179382e7ca1e))
* **Transfer:** Adds `stat` integration for files added to the Transfer list. ([#219](https://github.com/kodiakseraphim/p8-static-search-portal/issues/219)) ([e3d27f5](https://github.com/kodiakseraphim/p8-static-search-portal/commit/e3d27f585e305be340986f80186f9e14ff780449))
* use 'primary' and 'secondary' colors for styling ([#192](https://github.com/kodiakseraphim/p8-static-search-portal/issues/192)) ([0877f8e](https://github.com/kodiakseraphim/p8-static-search-portal/commit/0877f8e169cbdc03e7fd8f9b62438ffcc19f2b01))
* Use in-memory based storage for authorization tokens, by default. ([#235](https://github.com/kodiakseraphim/p8-static-search-portal/issues/235)) ([427d9e7](https://github.com/kodiakseraphim/p8-static-search-portal/commit/427d9e768bedde4f5dc3d367aa2f475355b36dde))


### Fixes

* add suspense boundary to results page ([855989b](https://github.com/kodiakseraphim/p8-static-search-portal/commit/855989b5473a2121e61b2ef237fea2b810c1634f))
* address TS errors ([c450e3d](https://github.com/kodiakseraphim/p8-static-search-portal/commit/c450e3dc93f09d8434375a68a0f8c623c4db060b))
* Addresses count issues with pagination. ([4d6c290](https://github.com/kodiakseraphim/p8-static-search-portal/commit/4d6c2904613c106fbff61685dd8543c3522576cf))
* clean-up result page rendering ([df3947a](https://github.com/kodiakseraphim/p8-static-search-portal/commit/df3947aaa8abc972652e1da3f52c920aafcadff7))
* ensure "Authorization" header is included when fetching a single result. ([#85](https://github.com/kodiakseraphim/p8-static-search-portal/issues/85)) ([7930257](https://github.com/kodiakseraphim/p8-static-search-portal/commit/7930257c3f3d18f37749b76cfe1e36d361f19cee))
* Ensure application path is accounted for in OAuth redirects ([8fac9a1](https://github.com/kodiakseraphim/p8-static-search-portal/commit/8fac9a178c49b01aef5ff83e0dc384a9d6fccfac))
* ensure proper export/next.config.js ([ebf79bd](https://github.com/kodiakseraphim/p8-static-search-portal/commit/ebf79bd18a4bfb3bbfc913682f79c308a088e2f8))
* ensure proper references to static.json file ([35bf90e](https://github.com/kodiakseraphim/p8-static-search-portal/commit/35bf90e3793d80e75ed0c176f8c54310c63653d3))
* improved image rendering by providing source and more obvious 'View Image' button ([#53](https://github.com/kodiakseraphim/p8-static-search-portal/issues/53)) ([40154cb](https://github.com/kodiakseraphim/p8-static-search-portal/commit/40154cbf6f9ad4f11745f97b690eb45c0e1e2f0f))
* Improves default styling of Markdown components. ([e9356b8](https://github.com/kodiakseraphim/p8-static-search-portal/commit/e9356b8733ccef5ab18f75136aceb2da32453bb6))
* Improves general layout styling. ([e9356b8](https://github.com/kodiakseraphim/p8-static-search-portal/commit/e9356b8733ccef5ab18f75136aceb2da32453bb6))
* Improves result rendering to account for 404s on hard refresh. ([#233](https://github.com/kodiakseraphim/p8-static-search-portal/issues/233)) ([2dc2bbc](https://github.com/kodiakseraphim/p8-static-search-portal/commit/2dc2bbcd1b77666c964c7d4ed97620a0d998e74e))
* include basePath in publicRuntimeConfig ([0e4585f](https://github.com/kodiakseraphim/p8-static-search-portal/commit/0e4585f82123b150f857b853f553309b6ea12aaa))
* Includes https://*.globusonline.org in default CSP ([#258](https://github.com/kodiakseraphim/p8-static-search-portal/issues/258)) ([ebd5fe3](https://github.com/kodiakseraphim/p8-static-search-portal/commit/ebd5fe39d6e474b08ab1a3b8312a000a98518eef))
* **OAuth:** Ensures users are redirected back to the path they initiated a "Sign In" request from. ([#236](https://github.com/kodiakseraphim/p8-static-search-portal/issues/236)) ([abdd9cf](https://github.com/kodiakseraphim/p8-static-search-portal/commit/abdd9cff0c03724326dd98fcc070de36126c8f57))
* proper reference to jsonata feature configuration ([21eb5cb](https://github.com/kodiakseraphim/p8-static-search-portal/commit/21eb5cb83837b2ff2efc48bc4b2e3866c0fa8300))
* Updates "globus.embed" fields to prompt for authorization when no session is found ([#255](https://github.com/kodiakseraphim/p8-static-search-portal/issues/255)) ([bd25b05](https://github.com/kodiakseraphim/p8-static-search-portal/commit/bd25b05de46cccd5f4ed7d3cf7d6d3fa235d8bf6))
* use default export instead of destructure ([7a4de58](https://github.com/kodiakseraphim/p8-static-search-portal/commit/7a4de58e1baffeb4ce3912d93052ad9d66883164))

## [1.5.0](https://github.com/globus/static-search-portal/compare/1.4.0...1.5.0) (2024-11-14)


### Features

* Adds JSON Renderer for Globus Embeds ([#262](https://github.com/globus/static-search-portal/issues/262)) ([dfd7aa0](https://github.com/globus/static-search-portal/commit/dfd7aa08065ce64d2dd1d6a057a4d7dbaa5b420c))

## [1.4.0](https://github.com/globus/static-search-portal/compare/1.3.1...1.4.0) (2024-11-14)


### Features

* Improves JSON rendering via react-json-view ([#260](https://github.com/globus/static-search-portal/issues/260)) ([59b6fc1](https://github.com/globus/static-search-portal/commit/59b6fc10e8d10566a19e709adc198371695acf57))

## [1.3.1](https://github.com/globus/static-search-portal/compare/1.3.0...1.3.1) (2024-11-14)


### Fixes

* Includes https://*.globusonline.org in default CSP ([#258](https://github.com/globus/static-search-portal/issues/258)) ([ebd5fe3](https://github.com/globus/static-search-portal/commit/ebd5fe39d6e474b08ab1a3b8312a000a98518eef))

## [1.3.0](https://github.com/globus/static-search-portal/compare/1.2.0...1.3.0) (2024-11-12)


### Features

* Improves "globus.embed" behaviors ([#253](https://github.com/globus/static-search-portal/issues/253)) ([57a5a25](https://github.com/globus/static-search-portal/commit/57a5a25bfd3dfca798d122acd660d776a82ecd9e))


### Fixes

* Updates "globus.embed" fields to prompt for authorization when no session is found ([#255](https://github.com/globus/static-search-portal/issues/255)) ([bd25b05](https://github.com/globus/static-search-portal/commit/bd25b05de46cccd5f4ed7d3cf7d6d3fa235d8bf6))

## [1.2.0](https://github.com/globus/static-search-portal/compare/1.1.0...1.2.0) (2024-11-08)


### Features

* adds "globus.embed" field type support ([#243](https://github.com/globus/static-search-portal/issues/243)) ([baa2d7e](https://github.com/globus/static-search-portal/commit/baa2d7ee8b5271b1d58d6455e5096e077c19aecd))
* adds support for rendering embedded Globus assets as a Plotly graph or chart ([#248](https://github.com/globus/static-search-portal/issues/248)) ([272e4a6](https://github.com/globus/static-search-portal/commit/272e4a675c3e9008e90107cd68a41c15b61dfb79))


### Fixes

* Ensure application path is accounted for in OAuth redirects ([8fac9a1](https://github.com/globus/static-search-portal/commit/8fac9a178c49b01aef5ff83e0dc384a9d6fccfac))

## [1.1.0](https://github.com/globus/static-search-portal/compare/1.0.0...1.1.0) (2024-11-01)


### Features

* Adds support for `features.requireAuthentication` – this will update built-in routes to prompt for authentication before any information is displayed. This feature is useful for mostly/completely private Globus Search indicies. ([abdd9cf](https://github.com/globus/static-search-portal/commit/abdd9cff0c03724326dd98fcc070de36126c8f57))


### Fixes

* **OAuth:** Ensures users are redirected back to the path they initiated a "Sign In" request from. ([#236](https://github.com/globus/static-search-portal/issues/236)) ([abdd9cf](https://github.com/globus/static-search-portal/commit/abdd9cff0c03724326dd98fcc070de36126c8f57))

## [1.0.0](https://github.com/globus/static-search-portal/compare/0.12.0...1.0.0) (2024-11-01)


### ⚠ BREAKING CHANGES

* Use in-memory based storage for authorization tokens, by default. ([#235](https://github.com/globus/static-search-portal/issues/235))

### Features

* Use in-memory based storage for authorization tokens, by default. ([#235](https://github.com/globus/static-search-portal/issues/235)) ([427d9e7](https://github.com/globus/static-search-portal/commit/427d9e768bedde4f5dc3d367aa2f475355b36dde))


### Fixes

* Improves result rendering to account for 404s on hard refresh. ([#233](https://github.com/globus/static-search-portal/issues/233)) ([2dc2bbc](https://github.com/globus/static-search-portal/commit/2dc2bbcd1b77666c964c7d4ed97620a0d998e74e))

## [0.12.0](https://github.com/globus/static-search-portal/compare/0.11.0...0.12.0) (2024-10-22)


### Features

* **Transfer:** Adds `stat` integration for files added to the Transfer list. ([#219](https://github.com/globus/static-search-portal/issues/219)) ([e3d27f5](https://github.com/globus/static-search-portal/commit/e3d27f585e305be340986f80186f9e14ff780449))

## [0.11.0](https://github.com/globus/static-search-portal/compare/0.10.1...0.11.0) (2024-10-11)


### Features

* Adds support for rendering fields a links. ([#212](https://github.com/globus/static-search-portal/issues/212)) ([889d966](https://github.com/globus/static-search-portal/commit/889d966bcbef78fa38a86c28eabf3bdf2ef843f9))

## [0.10.1](https://github.com/globus/static-search-portal/compare/0.10.0...0.10.1) (2024-10-10)


### Fixes

* include basePath in publicRuntimeConfig ([0e4585f](https://github.com/globus/static-search-portal/commit/0e4585f82123b150f857b853f553309b6ea12aaa))

## [0.10.0](https://github.com/globus/static-search-portal/compare/0.9.0...0.10.0) (2024-10-10)


### Features

* Allows configuration of custom navigation using "attributes.content.navigation" ([#205](https://github.com/globus/static-search-portal/issues/205)) ([e9356b8](https://github.com/globus/static-search-portal/commit/e9356b8733ccef5ab18f75136aceb2da32453bb6))


### Fixes

* Improves default styling of Markdown components. ([e9356b8](https://github.com/globus/static-search-portal/commit/e9356b8733ccef5ab18f75136aceb2da32453bb6))
* Improves general layout styling. ([e9356b8](https://github.com/globus/static-search-portal/commit/e9356b8733ccef5ab18f75136aceb2da32453bb6))

## [0.9.0](https://github.com/globus/static-search-portal/compare/0.8.3...0.9.0) (2024-10-08)


### Features

* adds support for "content" directory and landing page customization ([#189](https://github.com/globus/static-search-portal/issues/189)) ([63b3319](https://github.com/globus/static-search-portal/commit/63b3319c808cb06e52cbcbea624b6407796f7b45))
* use 'primary' and 'secondary' colors for styling ([#192](https://github.com/globus/static-search-portal/issues/192)) ([0877f8e](https://github.com/globus/static-search-portal/commit/0877f8e169cbdc03e7fd8f9b62438ffcc19f2b01))

## 0.8.3 (2024-05-22)

## What's Changed
* chore: adds Apache-2.0 LICENSE by @jbottigliero in https://github.com/globus/static-search-portal/pull/59
* deps: bump the react group with 3 updates by @dependabot in https://github.com/globus/static-search-portal/pull/61
* deps: bump eslint-plugin-react-hooks from 4.6.1 to 4.6.2 by @dependabot in https://github.com/globus/static-search-portal/pull/62
* deps: bump @globus/sdk from 3.0.0-alpha.17 to 3.0.0 by @dependabot in https://github.com/globus/static-search-portal/pull/63
* deps: bump @types/node from 20.12.7 to 20.12.8 by @dependabot in https://github.com/globus/static-search-portal/pull/65
* deps: bump @globus/sdk from 3.0.0 to 3.1.0 by @dependabot in https://github.com/globus/static-search-portal/pull/64
* deps: bump jsonata from 2.0.4 to 2.0.5 by @dependabot in https://github.com/globus/static-search-portal/pull/75
* deps: bump @types/node from 20.12.8 to 20.12.11 by @dependabot in https://github.com/globus/static-search-portal/pull/73
* deps: bump framer-motion from 11.1.7 to 11.1.9 by @dependabot in https://github.com/globus/static-search-portal/pull/72
* deps: bump @globus/sdk from 3.1.0 to 3.2.0 by @dependabot in https://github.com/globus/static-search-portal/pull/74
* deps: bump framer-motion from 11.1.9 to 11.2.4 by @dependabot in https://github.com/globus/static-search-portal/pull/82
* deps: bump @types/node from 20.12.11 to 20.12.12 by @dependabot in https://github.com/globus/static-search-portal/pull/78
* deps: bump @globus/sdk from 3.2.0 to 3.3.0 by @dependabot in https://github.com/globus/static-search-portal/pull/79
* deps: bump @types/react from 18.3.1 to 18.3.2 in the react group by @dependabot in https://github.com/globus/static-search-portal/pull/76
* deps: bump typedoc-plugin-markdown from 3.17.1 to 4.0.2 by @dependabot in https://github.com/globus/static-search-portal/pull/80
* deps: bump framer-motion from 11.2.4 to 11.2.5 by @dependabot in https://github.com/globus/static-search-portal/pull/84
* deps: bump @globus/sdk from 3.3.0 to 3.3.1 by @dependabot in https://github.com/globus/static-search-portal/pull/83
* fix: ensure "Authorization" header is included when fetching a single result. by @jbottigliero in https://github.com/globus/static-search-portal/pull/85


**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.8.2...0.8.3

## 0.8.2 (2024-04-26)

## What's Changed
* deps: bump the react group with 4 updates by @dependabot in https://github.com/globus/static-search-portal/pull/56
* deps: bump the next group with 2 updates by @dependabot in https://github.com/globus/static-search-portal/pull/55
* deps: bump eslint-plugin-react-hooks from 4.6.0 to 4.6.1 by @dependabot in https://github.com/globus/static-search-portal/pull/57


**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.8.1...0.8.2

## 0.8.1 (2024-04-24)

## What's Changed
* fix: improved image rendering by providing source and more obvious 'View Image' button by @jbottigliero in https://github.com/globus/static-search-portal/pull/53


**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.8.0...0.8.1

## 0.8.0 (2024-04-23)

## What's Changed
* ops: run 'tsc' on CI by @jbottigliero in https://github.com/globus/static-search-portal/pull/51


**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.7.0...0.8.0

## 0.7.0 (2024-04-23)

**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.6.1...0.7.0

## 0.6.1 (2024-04-22)

**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.6.0...0.6.1

## 0.6.0 (2024-04-22)

## What's Changed
* deps: bump @fontsource/ibm-plex-mono from 5.0.12 to 5.0.13 by @dependabot in https://github.com/globus/static-search-portal/pull/46
* deps: bump @fontsource/ibm-plex-sans from 5.0.19 to 5.0.20 by @dependabot in https://github.com/globus/static-search-portal/pull/45
* feat: adds support for jsonata based references in static.json by @jbottigliero in https://github.com/globus/static-search-portal/pull/47


**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.5.1...0.6.0

## 0.5.1 (2024-04-19)

**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.5.0...0.5.1

## 0.5.0 (2024-04-19)

## What's Changed
* deps: bump the next group with 2 updates by @dependabot in https://github.com/globus/static-search-portal/pull/39
* deps: bump framer-motion from 11.1.1 to 11.1.7 by @dependabot in https://github.com/globus/static-search-portal/pull/43


**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.4.0...0.5.0

## 0.4.0 (2024-04-17)

## What's Changed
* feat: adds basic pagination and improved loading state by @jbottigliero in https://github.com/globus/static-search-portal/pull/37
* deps: bump @globus/sdk from 3.0.0-alpha.8 to 3.0.0-alpha.17 by @dependabot in https://github.com/globus/static-search-portal/pull/34


**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.3.0...0.4.0

## 0.3.0 (2024-04-17)

## What's Changed
* deps: bump typescript from 5.3.3 to 5.4.5 by @dependabot in https://github.com/globus/static-search-portal/pull/35
* deps: bump typedoc from 0.25.12 to 0.25.13 by @dependabot in https://github.com/globus/static-search-portal/pull/36


**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.2.2...0.3.0

## 0.2.2 (2024-04-16)

**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.2.1...0.2.2

## 0.2.1 (2024-04-16)

**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.2.0...0.2.1

## 0.2.0 (2024-04-16)

## What's Changed
* feat: adds support for globus.search.facet to generate filter UI based on configured facets and responses from the index by @jbottigliero in https://github.com/globus/static-search-portal/pull/28
* deps: bump the next group with 2 updates by @dependabot in https://github.com/globus/static-search-portal/pull/24
* deps: bump @types/react from 18.2.78 to 18.2.79 in the react group by @dependabot in https://github.com/globus/static-search-portal/pull/23
* deps: bump @emotion/styled from 11.11.0 to 11.11.5 by @dependabot in https://github.com/globus/static-search-portal/pull/27
* deps: bump eslint from 8.56.0 to 8.57.0 by @dependabot in https://github.com/globus/static-search-portal/pull/25
* deps: bump framer-motion from 10.18.0 to 11.1.1 by @dependabot in https://github.com/globus/static-search-portal/pull/30


**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.1.1...0.2.0

## 0.1.1 (2024-04-15)

## What's Changed
* deps: bump eslint-plugin-react from 7.33.2 to 7.34.1 by @dependabot in https://github.com/globus/static-search-portal/pull/1
* deps: bump @fontsource/ibm-plex-mono from 5.0.8 to 5.0.12 by @dependabot in https://github.com/globus/static-search-portal/pull/5
* deps: bump @types/node from 20.11.4 to 20.12.7 by @dependabot in https://github.com/globus/static-search-portal/pull/19
* deps: bump @types/react from 18.2.48 to 18.2.78 by @dependabot in https://github.com/globus/static-search-portal/pull/22
* deps: bump @types/react-dom from 18.2.18 to 18.2.25 by @dependabot in https://github.com/globus/static-search-portal/pull/20
* deps: bump @emotion/react from 11.11.3 to 11.11.4 by @dependabot in https://github.com/globus/static-search-portal/pull/2
* deps: bump @fontsource/ibm-plex-sans from 5.0.18 to 5.0.19 by @dependabot in https://github.com/globus/static-search-portal/pull/4

## New Contributors
* @dependabot made their first contribution in https://github.com/globus/static-search-portal/pull/1

**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.1.0...0.1.1

## 0.1.0 (2024-03-29)

**Full Changelog**: https://github.com/globus/static-search-portal/compare/0.0.0...0.1.0
