# Swift Package Name
![Swift Version](https://img.shields.io/badge/Swift-5.10-DE5D43)
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Usage
```swift
import Example
// example code
```

## Installation
To use the `Example` library in a SwiftPM project, 
add it to the dependencies for your package and your target:

```swift
let package = Package(
    // name, platforms, products, etc.
    dependencies: [
        // other dependencies
        .package(url: "https://github.com/spacenation/swift-example", from: "1.0.0"),
    ],
    targets: [
        .target(
            // name, etc.
            dependencies: [
                // other dependencies
                .product(name: "Example", package: "swift-example")
            ]
        )
        // other targets
    ]
)
```

## Contributions
Feel free to contribute via fork/pull request to the main branch. If you want to request a feature or report a bug, please start a new issue.

## Become a Sponsor
If you find this project useful, please consider becoming our [GitHub Sponsor](https://github.com/sponsors/spacenation).
