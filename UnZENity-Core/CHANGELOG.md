# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [1.2.3] - 2024-10-13

### Fixed
- TextureBuilder won't crash when GC'd.


## [1.2.2] - 2024-10-13

### Fixed
- Initializing multiple NpcInstances of same Index work correctly.


## [1.2.1] - 2024-10-07

### Added
- NpcInstance (subclass of DaedalusInstance) contains UserData field to store exchangeable data between ZenKit's objects and UnZENity ones.


## [1.2.0] - 2024-09-22

### Fixed
- Daedalus externals where strings are sent to ZenKit are encoded correctly.

### Added
- Interfaces for all Vob types inside ZenKitCS added (I*VirtualObject). https://github.com/GothicKit/ZenKitCS/pull/12


## [1.1.2] - 2024-09-20

## Updated
- All scenes now have a Bootstrapping GameObject+Component attached (WorldSceneManager.cs). It will get called whenever the scene is loaded.


## [1.1.1] - 2024-09-15

### Fixed
- Daedalus support for _null_ return values when a class is expected (e.g. Hlp_GetNpc(); https://github.com/GothicKit/ZenKitCS/issues/10)
- Daedalus support for DaedalusInstance as parameters for _overloaded_ external calls like Hlp_GetInstanceID() (https://github.com/GothicKit/ZenKitCS/issues/8)


## [1.1.0] - 2024-08-31

### Updated
- Occlusion data for Gothic1 worlds.
- Moved occlusion data into subfolder.

### Added
- Occlusion data for Gothic2 Night of the Raven worlds.


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
