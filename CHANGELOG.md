# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) 
(modification: no type change headlines) and this project adheres to 
[Semantic Versioning](http://semver.org/spec/v2.0.0.html).


## [1.3.4] - 2018-03-06
- Fix a bug producing hash collisions on ``FakeTransaction`` for different senders, PR [#81](https://github.com/ethereumjs/ethereumjs-tx/pull/81)
- Switched from deprecated ``es2015`` to ``env`` babel preset, PR [#86](https://github.com/ethereumjs/ethereumjs-tx/pull/86)
- Dropped Node 4 support

[1.3.4]: https://github.com/ethereumjs/ethereumjs-tx/compare/v1.3.3...v1.3.4

## [1.3.3] - 2017-07-12
- Allow zeros in ``v``,``r``,``s`` signature values
- Dropped ``browserify`` transform from ``package.json``
- (combined v1.3.3 and v1.3.2 release notes)

[1.3.3]: https://github.com/ethereumjs/ethereumjs-tx/compare/v1.3.1...v1.3.3

## [1.3.1] - 2017-05-13
- Added ``ES5`` build

[1.3.1]: https://github.com/ethereumjs/ethereumjs-tx/compare/v1.3.0...v1.3.1

## [1.3.0] - 2017-04-24

- ``EIP155``: allow ``v`` value to be greater than one byte (replay attack protection)
- Added ``browserify`` ``ES2015`` transform to ``package.json``
- Improved documentation
- (combined v1.3.0, v1.2.5 and v1.2.4 release notes)

[1.3.0]: https://github.com/ethereumjs/ethereumjs-tx/compare/v1.2.3...v1.3.0

## [1.2.3] - 2017-01-30
- ``EIP155`` hash implementation
- README example and doc fixes

[1.2.3]: https://github.com/ethereumjs/ethereumjs-tx/compare/v1.2.2...v1.2.3

## [1.2.2] - 2016-12-15
- Moved ``chainId`` param to ``txParams``, parse ``sig`` for ``chainId`` (``EIP155`` refactor)
- Test improvements
- (combined v1.2.2 and v1.2.1 release notes)

[1.2.2]: https://github.com/ethereumjs/ethereumjs-tx/compare/v1.2.0...v1.2.2

## [1.2.0] - 2016-12-14
- Added ``EIP155`` changes
- Renamed ``chain_id`` to ``chainId``
- Node 4/5 compatibility
- ``ES6`` standards

[1.2.0]: https://github.com/ethereumjs/ethereumjs-tx/compare/v1.1.4...v1.2.0

## Older releases:

- [1.1.4](https://github.com/ethereumjs/ethereumjs-tx/compare/v1.1.3...v1.1.4) - 2016-11-17
- [1.1.3](https://github.com/ethereumjs/ethereumjs-tx/compare/v1.1.2...v1.1.3) - 2016-11-10
- [1.1.2](https://github.com/ethereumjs/ethereumjs-tx/compare/v1.1.1...v1.1.2) - 2016-07-17
- [1.1.1](https://github.com/ethereumjs/ethereumjs-tx/compare/v1.1.0...v1.1.1) - 2016-03-05
- [1.1.0](https://github.com/ethereumjs/ethereumjs-tx/compare/v1.0.1...v1.1.0) - 2016-03-03
- [1.0.1](https://github.com/ethereumjs/ethereumjs-tx/compare/v1.0.0...v1.0.1) - 2016-03-03
- [1.0.0](https://github.com/ethereumjs/ethereumjs-tx/compare/v0.7.3...v1.0.0) - 2016-02-11
