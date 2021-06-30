# Changelog

## Unreleased

## v2.1.0 (2021-05-10)

> **Note**: Before updating, you'll need to upgrade to Simple Commerce v2.3. Review the [upgrade guide](https://sc-docs.doublethree.digital/v2.3/update-guide).

### What's new?

* Support for Simple Commerce v2.3 #87
* Digital downloads are now zipped up, instead of downloading the raw file.
* You can attach multiple assets to a product for downloading. #62

## v2.0.4 (2021-04-21)

* [fix] Fixed bug with digital product detection sometimes being off #88

## v2.0.3

* [new] Limit the number of downloads per product #71

## v2.0.2

* [new] [Download History](https://github.com/doublethreedigital/sc-digital-products#download-history)
* [new] Supports Statamic 3.1

## v2.0.1

* v2 should only support v2.2

## v2.0.0

* Fully compatible with Simple Commerce v2.2
* Dependency updates

## v1.0.6

* Bump dependencies

## v1.0.5

* [new] Supports Simple Commerce v2.1
* [fix] The Verification endpoint will now get orders from the [configured order collection](https://sc-docs.doublethree.digital/v2.1/configuring#collections-amp-taxonomies), instead of being hard coded.
* [fix] Fixed bug where enabling the Statamic API wouldn't enable the Verification endpoint
* `LicenseKeyRepository` is now bound by `Statamic::repository`
* Added tests and did some refactoring

## v1.0.4

* Fix dependency issues.

## v1.0.3

* Just realised we don't technically support v2 of Simple Commerce yet 🤦

## v1.0.2

* Officially supports Statamic 3 (not beta)

## v1.0.1

* [new] A REST endpoint for license key verification

## v1.0.0

* Initial release of Digital Products addon for Statamic.