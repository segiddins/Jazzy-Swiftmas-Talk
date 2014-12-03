![inline](image/jazzy.jpg)

## Samuel Giddins
## @_segiddins_

---

## Thanks to _Realm_

---

### Document Swift Projects

---

## Built on _JP_’s __sourcekitten__

Leverages `sourcekit` for parsing

```
Usage: sourcekitten 
    [-h] 
    [--skip-xcodebuild COMPILER_ARGUMENTS]
    [--structure /absolute/path/to/file.swift]
    [--syntax /absolute/path/to/file.swift]
    [--syntax-text SWIFT_SOURCE_TEXT]
    [Xcode build arguments...]

Version: 0.1.9
```

^ All done via XPC
Reason why Swift-only now
Uses AST

---

## Swift Documentation

Like HeaderDoc, but uses ReST

See _[http://nshipster.com/swift-documentation/](http://nshipster.com/swift-documentation/)_ for reference

---

Example code from Alamofire v1.1.1

```swift
/**
    Creates a URL request by encoding parameters and applying them onto an existing request.
    
    :param: URLRequest The request to have parameters applied
    :param: parameters The parameters to apply

    :returns: A tuple containing the constructed request and the error that occurred during parameter encoding, if any.
*/
public func encode(URLRequest: URLRequestConvertible, parameters: [String: AnyObject]?) -> (NSURLRequest, NSError?) {

    // ...

}

```

---

The beautiful result

![inline](image/docs.jpg)

---

README Index Pages

![inline](image/readme.jpg)

---

Docsets for Dash

![inline](image/docset.jpg)

---

## What’s Next?

- More robust _tooling_
- Documentation generation on _CocoaDocs_
- Stronger _CocoaPods_ integration
- _:cake:_
- *¯\\\_(ツ)\_/¯*

^ We want to know what features you all want, and we welcome your contributions!

---

## [fit] Samuel E. Giddins
### _Things_ at _Realm_
### @_segiddins_
