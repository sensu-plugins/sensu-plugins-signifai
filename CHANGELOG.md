# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format located [here](https://github.com/sensu-plugins/community/blob/master/HOW_WE_CHANGELOG.md)

## Unreleased

## [2.0.0] - 2019-02-17
### Breaking Changes
- Updated dependencies and reconciled necessary changes (@zcarlson-signifai)
    - Bundler 2.0
    - Rubocop 0.50.0
    - sensu-plugins >= 1.2 and < 4.0
- Minimum Ruby version is now 2.3.0, in-line with sensu-plugins-skel (@zcarlson-signifai)

### Fixed
- Travis config following new minimum Ruby version requirement (@zcarlson-signifai)

### Changed
- misc changes to changelog and pr template (@majormoses)

## [1.1.3] 2017-09-21
### Added
- A bunch more information about the check and its results sent to signifai (@zcarlson-signifai)

## [1.1.1] 2017-07-11
### Fixed
- fix travis config (@majormoses)

## [1.1.0] 2017-07-11
### Added
- standard pr template (@majormoses)
- standard `.gitignore` (@majormoses)
- standard `.travis.yml` and deploy key (@majormoses)
- gemspec added `support@signifai.io` per #2 (@majormoses)

### Changed
- update gemspec to reflect sensu mailing list (@majormoses)
- use standard Rakefile (@majormoses)

### Removed
- Gemfile.lock (@majormoses)

## [1.0.0]
### Adopted
- became an official sensu community gem


[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-signifai/compare/1.1.3...HEAD
[2.0.0]: https://github.com/sensu-plugins/sensu-plugins-signifai/compare/1.1.3...2.0.0
[1.1.3]: https://github.com/sensu-plugins/sensu-plugins-signifai/compare/1.1.1...1.1.3
[1.1.1]: https://github.com/sensu-plugins/sensu-plugins-signifai/compare/1.0.0...1.1.0
[1.1.0]: https://github.com/sensu-plugins/sensu-plugins-signifai/compare/1.0.0...1.1.0
