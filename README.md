# Swift Package Name
![Swift Version](https://img.shields.io/badge/Swift-5.10-DE5D43)
![License](https://img.shields.io/badge/License-MIT-blue)

## How to Use
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
