# iconer

App icon generator for Apple platforms.

### Installation

```
brew tap tib/tap
brew install iconer
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