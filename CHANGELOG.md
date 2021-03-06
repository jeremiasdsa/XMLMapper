# Change Log

## [1.4.4](https://github.com/gcharita/XMLMapper/releases/tag/1.4.4) (2018-04-01)

- Fixed [#5](https://github.com/gcharita/XMLMapper/issues/5). Mapping Array of single object.
- Fixed [#8](https://github.com/gcharita/XMLMapper/issues/8). Threading problem in `XMLObjectParser` causing crash.

## [1.4.3](https://github.com/gcharita/XMLMapper/releases/tag/1.4.3) (2018-02-17)

- Fixed [#2](https://github.com/gcharita/XMLMapper/issues/2). Wrong XML String from nodes with attributes only.

## [1.4.2](https://github.com/gcharita/XMLMapper/releases/tag/1.4.2) (2018-02-04)

- Fixed changes that broke Swift 3.1 and Xcode 8.3 support
- Added `innerText` property in `XMLMap` to map directly the text of current XML node [#1](https://github.com/gcharita/XMLMapper/issues/1)
- General code improvements

## [1.4.1](https://github.com/gcharita/XMLMapper/releases/tag/1.4.1) (2018-01-25)

- Added Carthage support

## [1.4.0](https://github.com/gcharita/XMLMapper/releases/tag/1.4.0) (2018-01-04)

- Added Swift 4 support
- Added Swift Package Manager support
- Added CHANGELOG.md
- Fixed compilation warnings

## [1.3.0](https://github.com/gcharita/XMLMapper/releases/tag/1.3.0) (2017-11-05)

- Removed XMLDictionary dependency and replaced with Swift code
- Added `ReadingOptions` in `XMLSerialization`
- Added documentation in `XMLSerialization`
- Minor code improvements

## [1.2.0](https://github.com/gcharita/XMLMapper/releases/tag/1.2.0) (2017-10-12)

- Added Requests subspec for making xml requests with Alamofire
- Added classes for making SOAP request (supports SOAP v1.1 and v1.2)
- Minor code improvements

## [1.0.0](https://github.com/gcharita/XMLMapper/releases/tag/1.0.0) (2017-10-04)

- Added `nodeName` property in `XMLMappable` protocol
- Fixed compiler warnings
- Small improvements

## [0.1.0](https://github.com/gcharita/XMLMapper/releases/tag/0.1.0) (2017-09-27)

- Initial release
- Basic XML mapping