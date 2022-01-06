# Safer Check-In Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## Unreleased

## [1.1.19] - 2022-01-06
### Added
- Package seal not working [#49](https://github.com/rokmetro/safer-check-in-app/issues/49)

## [1.1.18] - 2021-06-16
### Added
- Add manual specimen ID entry indicator to orders [#48](https://github.com/rokmetro/safer-check-in-app/issues/48)

## [1.1.17] - 2021-05-26
### Added
- Support for subaccounts [#6](https://github.com/rokmetro/safer-check-in-app/issues/6)

## [1.1.16] - 2021-05-13
### Fixed
- Issue with authentication timeouts in dev environment [#41](https://github.com/rokmetro/safer-check-in-app/issues/41)
- Prevent backup of login credentials [#44](https://github.com/rokmetro/safer-check-in-app/issues/44)

## [1.1.15] - 2021-05-07
### Added
 - Scan once before manually enter barcode is an option [#31](https://github.com/rokmetro/safer-check-in-app/issues/31)
 - Default caps on manually enter barcode [#45](https://github.com/rokmetro/safer-check-in-app/issues/45)
 - Sort locations alphabetically [#46](https://github.com/rokmetro/safer-check-in-app/issues/46)
 - Allow walk-ins (manually enter new user information) by location [#15](https://github.com/rokmetro/safer-check-in-app/issues/15)
 - Additional improvements to clarity of success/failure messages [#35](https://github.com/rokmetro/safer-check-in-app/issues/35)
 - Loading indicators and prevent double clicking buttons [#30](https://github.com/rokmetro/safer-check-in-app/issues/30)
 
 ## [1.1.14] - 2021-04-30
 ### Added
 - Support for walk-ins [#27](https://github.com/rokmetro/safer-check-in-app/issues/27)
	- Search by email and phone
	- Automatically assign default externalID if none is known
 - Add support for minimum age restriction [#24](https://github.com/rokmetro/safer-check-in-app/issues/24)

## [1.1.12] - 2021-04-21
### Added
 - Alerts when network connection is lost [#7](https://github.com/rokmetro/safer-check-in-app/issues/7)
 - Add permission to manually enter barcode numbers/specimen IDs [#13](https://github.com/rokmetro/safer-check-in-app/issues/13)
 - Add automated validation of barcode numbers and associated error messaging [#8](https://github.com/rokmetro/safer-check-in-app/issues/8)
 - Make search by external ID case-insensitive [#16](https://github.com/rokmetro/safer-check-in-app/issues/16)
 - Improve order creation success/error messages to catch attention and display additonal information [#17](https://github.com/rokmetro/safer-check-in-app/issues/17)