# CoreData_BasicSetup

### Find CoreData Root

```swift
let dirPaths: [String] = NSSearchPathForDirectoriesInDomains(.documentDirectory, .userDomainMask, true)
print("CoreData Root: \(String(describing: dirPaths.first))")
```

### On Launch Argument

com.apple.CoreData.SQLDebug 1
com.apple.CoreData.ConcurrencyDebug 1
