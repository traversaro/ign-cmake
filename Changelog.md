## Ignition CMake 2.x

### Ignition CMake 2.x.x

1. Set viewport for doxygen pages.
    * [BitBucket pull request 167](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/167)

1. Use upstream `CURL::libcurl` imported target in FindIgnCURL.cmake if available.
    * [BitBucket pull request 175](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/175)

1. Avoid hardcoding /machine:x64 flag on 64-bit on MSVC.
    * [BitBucket pull request 171](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/171)
    * [BitBucket pull request 168](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/168)

1. FindIgnOGRE2: fix include paths for new directory structure.
    * [BitBucket pull request 170](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/170)
    * [BitBucket pull request 157](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/157)

1. Support for custom vcpkg ogre2 windows port (backport of PR 155).
    * [BitBucket pull request 161](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/161)
    * [BitBucket pull request 155](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/155)

1. IgnConfigureBuild: only `add_subdirectory(test)` if `BUILD_TESTING` is ON
    * [BitBucket pull request 169](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/169)

1. Add FindIgnBullet cmake module.
    * [BitBucket pull request 162](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/162)

### Ignition CMake 2.1.1 (2019-08-07)

1. Turn on doxygen warnings, add CI script to check for doxygen warnings.
    * [BitBucket pull request 158](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/158)

### Ignition CMake 2.1.0 (2019-05-17)

1. Fixes for vcpkg ogre 1.11 version
    * [BitBucket pull request 152](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/152)

1. Add benchmark aggregation functionality
    * [BitBucket pull request 148](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/148)
    * [BitBucket pull request 149](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/149)

1. Use `PRIVATE_FOR` to skip cmake dependencies in addition to pkg-config
    * [BitBucket pull request 147](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/147)

1. `upload_doc.sh`: actually use dry-run, and allow the user to pass in a 'y' or 'n'
    * [BitBucket pull request 146](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/146)

1. Set favicon
    * [BitBucket pull request 145](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/145)

1. Fix tagfile generation by preventing the inclusion of tutorials
    * [BitBucket pull request 142](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/142)

1. Update datainstall dir
    * [BitBucket pull request 141](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/141)

1. Allow tests to build without automatic linking against project lib
    * [BitBucket pull request 140](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/140)

### Ignition CMake 2.0.0 (2019-01-31)

1. Require cmake 3.10.2, support `CXX_STANDARD` 17
    * [BitBucket pull request 68](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/68)

    * [Full list of changes](https://github.com/ignitionrobotics/ign-cmake/compare/ignition-cmake2_2.0.0...ign-cmake1)

## Ignition CMake 1.x

1. Set viewport for doxygen pages.
    * [BitBucket pull request 167](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/167)

1. Use upstream `CURL::libcurl` imported target in FindIgnCURL.cmake if available.
    * [BitBucket pull request 175](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/175)

1. Avoid hardcoding /machine:x64 flag on 64-bit on MSVC.
    * [BitBucket pull request 171](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/171)
    * [BitBucket pull request 168](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/168)

1. IgnConfigureBuild: only `add_subdirectory(test)` if `BUILD_TESTING` is ON
    * [BitBucket pull request 165](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/165)

1. Fix race condition in test for issue 48
    * [BitBucket pull request 136](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/136)
    * [Issue 48](https://github.com/ignitionrobotics/ign-cmake/issues/48)

1. Account for inter-component dependencies when importing targets
    * [BitBucket pull request 131](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/131)
    * [Issue 48](https://github.com/ignitionrobotics/ign-cmake/issues/48)

### Ignition CMake 1.1.0

* Initial version bumped to 1.1.0 since there was a 1.1.0 prerelease

### Ignition CMake 1.0.0

    * [Full list of changes](https://github.com/ignitionrobotics/ign-cmake/compare/ignition-cmake1_1.0.0...ign-cmake0)

## Ignition CMake 0.x

1. Set viewport for doxygen pages.
    * [BitBucket pull request 167](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/167)

1. Use upstream `CURL::libcurl` imported target in FindIgnCURL.cmake if available.
    * [BitBucket pull request 175](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/175)

1. Avoid hardcoding /machine:x64 flag on 64-bit on MSVC.
    * [BitBucket pull request 168](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/168)

1. IgnConfigureBuild: only `add_subdirectory(test)` if `BUILD_TESTING` is ON
    * [BitBucket pull request 163](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/163)

1. IgnConfigureProject.cmake: fix small typo PKCONFIG -> PKGCONFIG
    * [BitBucket pull request 118](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/118)

### Ignition CMake 0.6.1

1. Fix duplicated imported target error
    * [BitBucket pull request 110](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/110)
    * [Issue 47](https://github.com/ignitionrobotics/ign-cmake/issues/47)

### Ignition CMake 0.6.0

1. Properly mark internal CMake cache variables as advanced
    * [BitBucket pull request 68](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/68)

1. Make line coverage by default, add separate coverage-branch target
    * [BitBucket pull request 66](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/66)

1. Refactor variable names in example test junit templates
    * [BitBucket pull request 57](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/57)

1. Suport for `CMAKE_BUILD_TYPE` None
    * [BitBucket pull request 54](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/54)

### Ignition CMake 0.5.0

1. FindJSONCPP: fix target when pkg-config is successful
    * [BitBucket pull request 50](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/50)

1. Add branch coverage
    * [BitBucket pull request 46](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/46)

1. Add FindOptiX.cmake
    * [BitBucket pull request 34](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/34)

### Ignition CMake 0.4.1

    * [Full list of changes](https://github.com/ignitionrobotics/ign-cmake/compare/ignition-cmake_0.4.1...ignition-cmake_0.4.0)

### Ignition CMake 0.4.0

