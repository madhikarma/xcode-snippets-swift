# xcode-snippets-swift
Swift code snippets for Xcode

# Setup
## Script
Run `sh setup.sh` to copy all the snippets into the Xcode snippets folder.

## Manual
- Select all files in the `snippets` folder and copy them to: `~/Library/Developer/Xcode/UserData/CodeSnippets`.
- Launch / Restart Xcode.
 
# Usage
- Use shortcut indicated by each .codesnippet’s filename to autocomplete the code snippet. 

e.g. 

- `alrt` - For `UIAlertController` creation.
- `cvds` - For `UICollectionViewDataSource` methods.
- `initc` - For `initWithCoder:` initialiser method.
- `initf` - For `initWithFrame:` initialiser method.
- `gcd` - For <a href=“https://developer.apple.com/library/ios/documentation/Performance/Reference/GCD_libdispatch_Ref/“>Grand Central Dispatch</a> code example.
- `mark` - For `MARK: -` Swift comment / directive.
- `stp` - For `setup` and `setupConstraints` methods.
- `stpo` - For overriden `setup` and `setupConstraints` methods (e.g. when subclassing <a href=“https://github.com/ustwo/baseview-swift”>BaseView-swift</a> framework)
- `tvd` - For `UITableViewDelegate` methods.
- `tvds` - For `UITableViewDataSource` methods.
