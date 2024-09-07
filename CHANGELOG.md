Changelog
=========

## 1.1.2 - 2024.09.07
### Added
* Added support for the `TEMPLATES_VENDOR_DIR` environment variable, either defined in the environment itself, or in a `.env` file if [Dotenv](https://github.com/vlucas/phpdotenv)) is used

## 1.1.1 - 2024.04.16
### Added
* Add `phpstan` and `ecs` code linting
* Add `code-analysis.yaml` GitHub action

### Changed
* PHPstan code cleanup
* ECS code cleanup

## 1.1.0 - 2023-02-19
### Added
* Added support for Composer 2.x
* Added `.gitattributes`
* Added `CODEOWNERS`

### Changed
* Write out a `.gitignore` file to the `templates/vendor/` directory

## 1.0.0 - 2020-02-13
### Changed
* Initial release.
