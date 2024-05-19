## 1.8.0 (Unreleased)

UPGRADE NOTES:

NEW FEATURES:

ENHANCEMENTS:
* Added `tofu test -json` types to website Machine-Readable UI documentation ([1408](https://github.com/opentofu/opentofu/issues/1408))
* Made `tofu plan` with `generate-config-out` flag replace JSON strings with `jsonencode` functions calls. ([#1595](https://github.com/opentofu/opentofu/pull/1595))

BUG FIXES:
* Fixed crash in gcs backend when using certain commands ([#1618](https://github.com/opentofu/opentofu/pull/1618))
* Fix inmem backend crash due to missing struct field ([#1619](https://github.com/opentofu/opentofu/pull/1619))
* Added a check in the `tofu test` to validate that the names of test run blocks do not contain spaces. ([#1489](https://github.com/opentofu/opentofu/pull/1489))
* Fix race condition on locking in gcs backend ([#1342](https://github.com/opentofu/opentofu/pull/1342))

## Previous Releases

For information on prior major and minor releases, see their changelogs:

- [v1.7](https://github.com/opentofu/opentofu/blob/v1.7/CHANGELOG.md)
- [v1.6](https://github.com/opentofu/opentofu/blob/v1.6/CHANGELOG.md)
