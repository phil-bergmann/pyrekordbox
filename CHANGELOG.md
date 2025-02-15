# What's New

<a name="unreleased"></a>
## [Unreleased]

### New Features
- add SQLCipher support for macOS (see [#27](https://github.com/dylanljones/pyrekordbox/issues/27))


<a name="0.0.6"></a>
## [0.0.6] - 2022-27-05
### Improvements/Bug Fixes
- fix encoding errors on MacOS
- improve ANLZ getters


<a name="0.0.5"></a>
## [0.0.5] - 2022-06-05
### Improvements/Bug Fixes
- improve XML playlist handling and fix refactoring bugs
- raise ValueError if duplicate track is added
- improve XML key errors
- add implementation of crc16xmodem to support Python 3.10 ([#21](https://github.com/dylanljones/pyrekordbox/issues/21))


<a name="0.0.4"></a>
## [0.0.4] - 2022-06-05
### New Features
- add auto-increment of XML TrackID when adding new tracks

### Improvements/Bug Fixes
- fix wrong MySetting default values
- simplify names of playlist (folder) creation methods
- add method to remove tracks in XML database and fix bug in track count update
- fix position argument of XPath in XML file (starts at 1)
- file paths in the XML file are now encoded and decoded as URI's
- fix XML tests with new API
- Improve Rekordbox XML handling and API


<a name="0.0.3"></a>
## [0.0.3] - 2022-24-04
### New Features
- add get-methods for `master.db` database tables

### Improvements/Bug Fixes
- fix table name in `get_artist`
- fix typo in settingFile table name

### Documentation
- switch back to rtd theme since furo code blocks don't render properly
- use furo sphinx theme
- add quick-start
- add installation section
- add tutorial sections
- rename file-format headers
- add development section


<a name="0.0.2"></a>
## [0.0.2] - 2022-20-04
### New Features
- use SQLAlchemy for the  Rekordbox6 `master.db` database

### Improvements/Bug Fixes
- fix import error and README.md
- set logging level to warning
- fix loading the Rekordbox setting file twice in config initialization
- add context for Rekordbox 6 database
- inherit AnlzFile from Mapping to implement dict interface
- unify binary file API

### Documentation
- add missing djmd tables to `master.db` database documentation
- add missing djmd tables to `master.db` database documentation


<a name="0.0.1"></a>
## [0.0.1] - 2022-10-04
### Improvements/Bug Fixes
- fix Python version


<a name="0.0.0"></a>
## 0.0.0 - 2022-10-04


[Unreleased]: https://github.com/dylanljones/pyrekordbox/compare/0.0.6...HEAD
[0.0.6]: https://github.com/dylanljones/pyrekordbox/compare/0.0.5...0.0.6
[0.0.5]: https://github.com/dylanljones/pyrekordbox/compare/0.0.4...0.0.5
[0.0.4]: https://github.com/dylanljones/pyrekordbox/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/dylanljones/pyrekordbox/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/dylanljones/pyrekordbox/compare/0.0.1...0.0.2
[0.0.1]: https://github.com/dylanljones/pyrekordbox/compare/0.0.0...0.0.1
