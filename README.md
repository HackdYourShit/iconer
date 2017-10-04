# iconer

App icon generator for Apple platforms.

See this [blog post](https://theswiftdev.com/2016/06/07/app-icon-generator-for-ios-watchos-and-os-x/) for more info.

### Installation

```
brew install corekit/brew/iconer
```

### Usage

```
iconer ~/AppIcon.png ~/Icon.png
```

### Xcode Phase

To use as a build script for iOS platform add a New Run Script Phase before the Copy Bundle Resources phase.

```
iconer "${SRCROOT}/${PROJECT_NAME}/AppIcon.png" -t "${SRCROOT}/${PROJECT_NAME}" -x -p "ios"

```



### License

WTFPL
