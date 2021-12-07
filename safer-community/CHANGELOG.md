# Safer Community Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## Unreleased
## [2.12.51] - 2021-12-07
[Milestone](https://github.com/rokmetro/safer-app/milestone/8)

### Fixed
 - Stuck on consent panel after token expires [#223](https://github.com/rokmetro/safer-app/issues/223)

## [2.12.50] - 2021-11-09
[Milestone](https://github.com/rokmetro/safer-app/milestone/7)

### Fixed
 - Stacking notification alert dialogs [#217](https://github.com/rokmetro/safer-app/issues/217)
 - New strings conflict with old [#218](https://github.com/rokmetro/safer-app/issues/218)

## [2.12.49] - 2021-11-02
[Milestone](https://github.com/rokmetro/safer-app/milestone/6)

### Fixed
 - Device time manipulation [#193](https://github.com/rokmetro/safer-app/issues/193) 
 - Users setting invalid password with reset [#205](https://github.com/rokmetro/safer-app/issues/205)
 - Subaccounts inheriting exemption [#202](https://github.com/rokmetro/safer-app/issues/202)
 - Make status card animation more visible [#213](https://github.com/rokmetro/safer-app/issues/213)
 - Available upgrade option not dismissable [#209](https://github.com/rokmetro/safer-app/issues/209)
 - Unprompted logouts [#191](https://github.com/rokmetro/safer-app/issues/191)

### Removed
 - Remove exposure notification [#204](https://github.com/rokmetro/safer-app/issues/204)
 - Remove Microblink [#203](https://github.com/rokmetro/safer-app/issues/203)
 
## [2.12.48] - 2021-09-28
[Milestone](https://github.com/rokmetro/safer-app/milestone/5)
### Added
 - Alphabetically sort org list [#195](https://github.com/rokmetro/safer-app/issues/195)

### Fixed
 - Device time manipulation [#193](https://github.com/rokmetro/safer-app/issues/193)
 - Account deletion process [#187](https://github.com/rokmetro/safer-app/issues/187)
 - Registration text box missing in other languages [#189](https://github.com/rokmetro/safer-app/issues/189)
 - Connection error displaying when inactive [#192](https://github.com/rokmetro/safer-app/issues/192)
 - Accidental account deletion [#190](https://github.com/rokmetro/safer-app/issues/190)
 - Application size increase [#199](https://github.com/rokmetro/safer-app/issues/199)

## [2.12.47] - 2021-08-31
[Milestone](https://github.com/rokmetro/safer-app/milestone/4)
### Added
 - Make status card swiping more clear [#170](https://github.com/rokmetro/safer-app/issues/170)
 - Better connection error messaging [#175](https://github.com/rokmetro/safer-app/issues/175)
 - Make completing personal info form requirable [#171](https://github.com/rokmetro/safer-app/issues/171)
 - Improve login flow [#168](https://github.com/rokmetro/safer-app/issues/168)

### Fixed
 - User profile information not saving [#169](https://github.com/rokmetro/safer-app/issues/169)
 - Push notifications toggle and save QR code in settings will not request necessary permissions on iOS [#182](https://github.com/rokmetro/safer-app/issues/182)

## [2.12.46] - 2021-06-22
### Added
 - Re-display consent form if user has not agreed to latest version [#166](https://github.com/rokmetro/safer-app/issues/166)

### Fixed
 - Loop during authentication refresh [#162](https://github.com/rokmetro/safer-app/issues/162)
 - Returning users do not need to repeat onboarding process [#80](https://github.com/rokmetro/safer-app/issues/80)
 - Broken help email button on iOS

## [2.12.45] - 2021-05-26
### Added
 - Support for creating minor accounts (does not impact all clients) [#153](https://github.com/rokmetro/safer-app/issues/153)
 - Support for printing results (does not impact all clients) [#149](https://github.com/rokmetro/safer-app/issues/149)

### Fixed
 - Inconsistent user name updates

## [2.12.38] - 2021-05-01
### Added
 - FAQ and support email (does not impact all clients) [#130](https://github.com/rokmetro/safer-app/issues/130)
 - Support for minimum age restriction [#131](https://github.com/rokmetro/safer-app/issues/131)
 
### Fixed
 - Issue with multiple accounts on the same device [#127](https://github.com/rokmetro/safer-app/issues/127)
 - Accessibility improvements

## [2.12.31] - 2021-04-11
### Added
 - Automatically display sign up form when creating account by email for the first time [#120](https://github.com/rokmetro/safer-app/issues/120)

### Fixed
 - Missing info on personal info form on first login [#115](https://github.com/rokmetro/safer-app/issues/115)
 - Partial account deletion issue [#110](https://github.com/rokmetro/safer-app/issues/110)
 - UI issues after token expires [#118](https://github.com/rokmetro/safer-app/issues/118)
 - Analytics event duplication issue [#112](https://github.com/rokmetro/safer-app/issues/112)
 - Improve phone number input
 - Improve messaging when disconnected from network

## [2.12.27] - 2021-03-25
### Added
 - Status card QR code/groups support for roster members (Does not impact existing clients) [#106](https://github.com/rokmetro/safer-app/issues/106)

 # Fixed
 - Improve phone number entry on personal info form
 - Improve phone login experience

## [2.12.26] - 2021-03-19
### Added
 - Support for sub-accounts (Does not impact existing clients) [#101](https://github.com/rokmetro/safer-app/pull/101)
 - Load roster data into account as default values [#91](https://github.com/rokmetro/safer-app/issues/91)

### Fixed
 - Rule intervals bug for daylight saving time [#97](https://github.com/rokmetro/safer-app/issues/97)
 - Improve onboarding organization selection

## [2.12.23] - 2021-03-11
### Added
 - Groups functionality (Does not impact existing clients)
 - Test reservation functionality (Does not impact existing clients)
 - Support for additional data in results (eg. collection time, result time, specimen ID)
 - Support for create and cancel order events
 - Disclaimer to results
 - Enable location notes section

### Fixed
 - Bug preventing autopopulation of dropdown form fields from SSO
 - Bug preventing new users from automatically generating private key QR code

## [2.12.2] - 2021-02-10
### Added
 - Autopopulate dynamic fields on personal information form from Single Sign-On
 - Enhance OIDC reauthentication process when no refresh token is available

### Changed
 - Replace Personal Info Panel in settings with form summary

### Fixed
 - Incorrect output calculation of birthdate
 - Unable to restore secret QR code from files
 - Lower resolution displays not showing the email field to log in
 - Issue with date cutoff for "today" vs "tomorrow" for Next Steps