# Swift DocC Template

Use Xcode 15 & Swift DocC to build and share documentation for standalone projects.   

## Overview

Use this starter template to create rich documentation and interactive tutorials for *non* Swift projects.

## Topics

* [Meet DocC documentation in Xcode](https://developer.apple.com/videos/play/wwdc2021/10166 "site: developer.apple.com")
* [Create rich documentation with Swift-DocC](https://developer.apple.com/wwdc23/10244 "site: developer.apple.com")
* [Produce rich API reference documentation and interactive tutorials site](https://www.swift.org/documentation/docc "site: swift.org")

---

### Command Line

```console
# Resolve package dependencies
swift package resolve -h
swift package resolve

# Preview documentation from a source bundle
xcrun docc preview -h
xcrun docc preview Documentation.docc --port 4256
```

---

*Customization example with `@Metadata` directives.*
![Example of some of the @Metadata directives.](Documentation.docc/Resources/Documentation@2x.png)
