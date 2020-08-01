# ChessKit

[![codebeat badge](https://codebeat.co/badges/d0f02d72-ca79-4cd6-a4a1-d4ad3a77ea04)](https://codebeat.co/projects/github-com-perechnev-chesskit-develop)
[![docs badge](https://raw.githubusercontent.com/perechnev/ChessKit/develop/docs/badge.svg)](https://perechnev.github.io/ChessKit/) [![Gitter](https://badges.gitter.im/Ladoga-Engine/ChessKit.svg)](https://gitter.im/Ladoga-Engine/ChessKit?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) ![Tests](https://github.com/perechnev/ChessKit/workflows/Tests/badge.svg) ![](https://img.shields.io/github/license/perechnev/ChessKit) [![ChessKit pod](https://img.shields.io/cocoapods/v/ChessKit)](https://cocoapods.org/pods/ChessKit)

Lightweight and fast chess framework written in Swift.

ChessKit is used as a base framework for [Ladoga](https://lichess.org/@/ladoga_engine) chess engine.

## Installation

The ChessKit framework is avalable for installation via Swift Package Manager and CocoaPods.

### Swift Package Manager

Add a dependency via Xcode, linking to `https://github.com/perechnev/ChessKit`, or directly in your `Package.swift` file:

```Swift
import PackageDescription

let package = Package(
    name: "MyPackage",
    platforms: [
        .macOS(.v10_12),
    ],
    dependencies: [
        .package(url: "https://github.com/perechnev/ChessKit.git", from: "1.2.10"),
    ],
    targets: [
        .target(name: "MyPackage", dependencies: ["ChessKit"]),
    ]
)
```

### CocoaPods

To install ChessKit via CocoaPods, just add a dependencie to your `Podfile`:

```Ruby
target 'MyApp' do
  pod 'ChessKit'
end
```

## How To Contribute

Please follow the [git-flow](http://danielkummer.github.io/git-flow-cheatsheet/index.html) notation and make sure that all tests are passing before contributing. Your questions and pull requests are welcome.

## Versioning

We are using [semantic versioning](https://semver.org).

## Support

If you need some help, you can join our [gitter room](https://gitter.im/Ladoga-Engine/ChessKit).

## License

ChessKit is released under the MIT license. See LICENSE for details.
