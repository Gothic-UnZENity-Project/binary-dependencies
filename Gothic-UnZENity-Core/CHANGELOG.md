# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [1.0.5] - 2024-08-10

### Fixed
- Non-void Daedalus function calls without a proper return value always provide default return values.


## [1.0.4] - 2024-08-04

### Added
- VOBs of type _oCNPC_ can be casted to _ZenKit.Vobs.Npc_ directly.


## [1.0.3] - 2024-07-02

### Added
- Items (VOBs) now contain fields for _Amount_ and _Flags_ from save files.


## [1.0.2] - 2024-06-29

### Fixed
- Fixes multiple issues with file loading on Windows which caused Vfs mounting to fail in various places.


## [1.0.1] - 2024-06-23

### Fixed
- Zen worlds loading inside a SaveGame returns null instead of a segfault.


# [1.0.0] - 2024-06-01

### Added
- Initial commit.
