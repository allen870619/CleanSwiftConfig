### Add script to Build Phrases > New Run Script
```
# Type a script or drag a script file from your workspace to insert its path.
# swift format
swiftformat .

# swiftlint
if which swiftlint >/dev/null; then
    swiftlint
else
    echo "warning: SwiftLint not installed, download from https://github.com/realm/SwiftLint"
fi
``````
