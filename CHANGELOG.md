# Changelog

## v1.0.1
### Fixed
- fixed LoadError when requiring the gem by adding `version.rb` to the gem files

## v1.0.0
### Changed
- records of subassociations with the `:delete` or `:delete_all` option are now deleted during recursive deletion; associations that follow these in the association tree are still ignored

### Added
- added support for `has_many :through` associations
