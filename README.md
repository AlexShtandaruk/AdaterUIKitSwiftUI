# AdapterUIKitSwiftUI

A simple adapter to use native navigation between SwiftUI and UIKit

![AdapterViewController](https://github.com/AlexShtandaruk/AdaterUIKitSwiftUI/assets/125973696/4b1e32fa-d50b-4ea7-a38f-f7f0fa4c2ca7)


### Installation:

It requires iOS 14

In Xcode go to `File -> Swift Packages -> Add Package Dependency` and paste in the repo's url: `https://github.com/AlexShtandaruk/AdaterUIKitSwiftUI`

or just copy the code from the Source folder :)

### Usage

```swift
 NavigationView {
    VStack {
      NavigationLink("Push View Controller", destination: ViewControllerAdapter(SomeViewController()))
    }
    .navigationTitle("SwiftUI View")
 }
```
