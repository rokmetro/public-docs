# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## Unreleased

## [1.2.16] - 2021-05-13
### Added
- Manually enter barcode option for cancel function [#39](https://github.com/rokmetro/safer-check-in-app/issues/39)
### Fixed
- Issue with authentication timeouts in dev environment [#41](https://github.com/rokmetro/safer-check-in-app/issues/41)
- Prevent backup of login credentials [#44](https://github.com/rokmetro/safer-check-in-app/issues/44)

## [1.2.15] - 2021-05-07
### Added
- Scan once before manually enter barcode is an option [#31](https://github.com/rokmetro/safer-check-in-app/issues/31)
- Default caps on manually enter barcode [#45](https://github.com/rokmetro/safer-check-in-app/issues/45)
- Sort locations alphabetically [#46](https://github.com/rokmetro/safer-check-in-app/issues/46)
- Allow walk-ins (manually enter new user information) by location [#15](https://github.com/rokmetro/safer-check-in-app/issues/15)
- Additional improvements to clarity of success/failure messages [#35](https://github.com/rokmetro/safer-check-in-app/issues/35)
- Loading indicators and prevent double clicking buttons [#30](https://github.com/rokmetro/safer-check-in-app/issues/30)
 
## [1.2.14] - 2021-04-30
### Added
- Support for walk-ins [#27](https://github.com/rokmetro/safer-check-in-app/issues/27)
    - Search by email and phone
    - Automatically assign default externalID if none is known
- Add support for minimum age restriction [#24](https://github.com/rokmetro/safer-check-in-app/issues/24)

## [1.2.12] - 2021-04-21
### Added
- Alerts when network connection is lost [#7](https://github.com/rokmetro/safer-check-in-app/issues/7)
- Add permission to manually enter barcode numbers/specimen IDs [#13](https://github.com/rokmetro/safer-check-in-app/issues/13)
- Allow manual entry of barcode numbers/specimen IDs when checking orders [#13](https://github.com/rokmetro/safer-check-in-app/issues/13)
- Add automated validation of barcode numbers and associated error messaging [#8](https://github.com/rokmetro/safer-check-in-app/issues/8)
- Make search by external ID case-insensitive [#16](https://github.com/rokmetro/safer-check-in-app/issues/16)
- Improve order creation success/error messages to catch attention and display additonal information [#17](https://github.com/rokmetro/safer-check-in-app/issues/17)
- Fix bug occasionally preventing check and cancel order buttons from finding orders [#20](https://github.com/rokmetro/safer-check-in-app/issues/20)