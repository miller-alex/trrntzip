# Unreleased

* fix build on Windows with MSVC
* add more tests

# 1.3 [2024-03-06]

* fix a regression in 1.2 which wrongly treated some zip files as torrentzipped
* fix a core dump
* more consistent casing behaviour across platforms
* add some tests

# 1.2 [2024-02-22]

* fix a build error on windows
* improve log file handling
* add -e and -l options to set (or disable) error log file and logging directory
* revert zip64 format changes from last release
* update included source for minizip to version from zlib-1.3.1
* various fixes and code cleanup

# 1.1 [2024-01-16]

* zip64 format: zip64 EOCD was missing in some cases
* add -q flag to reduce log output
* update included source for minizip to version from zlib-1.2.13
* fix -g description
* canonicalize sort order
* fix memory leak
* improve temporary file handling
* do not follow symlinks, only handle regular files
* various other fixes

Thanks to our new contributor:
* Alexander Miller

# 1.0.0 [2022-06-18]

* portability fixes
* update included source for minizip to version from zlib-1.2.10
