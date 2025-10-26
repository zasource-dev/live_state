# Changelog

## [0.9.0]

### Added
- New `handle_message/3` callback for more flexible message handling with additional context (#32, #33)
- Implementation for `lvs_refresh` functionality
- Comprehensive documentation for `LiveState.Encoder` explaining encoding and serialization behavior

### Fixed
- Bug where `Ecto.Association.NotLoaded` structs were incorrectly passed through `LiveState.Encoder` instead of being properly handled
- Elixir 1.19 type system compatibility warnings (#31)
- Documentation corrections for `gen.element`
- Unused variable warnings

### Changed
- Updated tutorial documentation with improved examples and socket handling (#26)
- Upgraded ExDoc dependency
- Updated to use Elixir 1.19 in local development and CI builds

