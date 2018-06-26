# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed [here](https://github.com/sensu-plugins/community/blob/master/HOW_WE_CHANGELOG.md).
Which is based on [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]

### Added
- metrics-snmp-if.rb: added `--timeout|-t` option which controls the request timeout (@rocdove)

## [2.0.0] - 2017-11-04

### Changed
- updated changelog guideline location (@majormoses)

### Fixed
- typos in changelog and pr template (@majormoses)

### Added
- check-snmp-disk.rb: added `--port|-P` option (@freepenguins)
- metrics-snmp.rb: added `--port|-P` option (@freepenguins)
- metrics-snmp-bulk.rb: added `--port|-P` option (@freepenguins)
- metrics-snmp-if.rb: added `--port|-P` option (@freepenguins)

### Breaking Change
- check-snmp.rb: changed port option from `-p` to `-P` to avoid confusion with prefix (@freepenguins)

## [1.1.0] - 2017-10-04
### Added
- check-snmp.rb: added `--port` option (@freepenguins)

## [1.0.0] - 2017-07-04
### Added
- Ruby 2.3.0 testing (@Evesy)
- Ruby 2.4.1 testing (@Evesy)

### Breaking Changes
- Dropped Ruby 1.9.3 support (@Evesy)

### Fixed
- PR template spelling

## [0.2.0] - 2016-08-10
### Added
- Updated sensu-plugin dependency from `= 1.2.0` to `~> 1.2`
- check-snmp.rb: Option to convert SNMP Timetick data to Integer for easier comparisons
- check-snmp.rb Debug option for troubleshooting pesky SNMP data

## [0.1.0] - 2015-11-13
### Added
- Added a script check-snmp-disk, that checks disk utilization using SNMP

## [0.0.4] - 2015-07-22
### Fixed
- Fixed graphite output when using a prefix in metrics-snmp-bulk.rb

### Added
- Made suffix an optional flag in metrics-snmp-bulk.rb so you can choose exactly how to format your metrics output

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - 2015-06-03
### Fixed
- added binstubs

### Changed
- removed cruft from /lib

## 0.0.1 - 2015-04-30
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-snmp/compare/2.0.0...HEAD
[2.0.0]: https://github.com/sensu-plugins/sensu-plugins-snmp/compare/1.1.0...2.0.0
[1.1.0]: https://github.com/sensu-plugins/sensu-plugins-snmp/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-snmp/compare/0.2.0...1.0.0
[0.2.0]: https://github.com/sensu-plugins/sensu-plugins-snmp/compare/0.1.0...0.2.0
[0.1.0]: https://github.com/sensu-plugins/sensu-plugins-snmp/compare/0.0.4...0.1.0
[0.0.4]: https://github.com/sensu-plugins/sensu-plugins-snmp/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-snmp/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-snmp/compare/0.0.1...0.0.2
