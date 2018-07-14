# OpenAQKit
---
Open AQ Kit was an SDK written to simplify the process of interacting with [OpenAQ](openaq.org). This SDK lets you easily fetch air quality data for more than 60+ countries.

## Requirements
---
* Swift 4
* iOS 10.0+
* macOS 10.13+

## Installation
---
### Swift Package Manager
The Swift Package Manager is a tool for automating the distribution of Swift code and is integrated into the swift compiler.

Once you have your Swift package set up, adding OpenAQKit as a dependency is as easy as adding it to the dependencies value of your Package.swift.

```swift
dependencies: [
    .package(url: "https://github.com/hyerra/OpenAQKit.git", from: "1.0.1")
]
```
## Usage
---
Requests to Open AQ can be requested by using the `OpenAQClient` class like so:
```swift
let client = OpenAQClient.shared
```

Requests can be made by using any of the public functions within the client to fetch supported cities, supported countries, air quality data, and more.

## Communication
---
* If you'd like to ask a general question, use Stack Overflow.
* If you found a bug, open an issue.
* If you have a feature request, open an issue.
* If you want to contribute, submit a pull request.

## Author
---
Written by [Harish Yerra](https://twitter.com/harishyerra4)
## License
OpenAQKit is released under the MIT license. See LICENSE for details.
