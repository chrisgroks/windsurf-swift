# Swift for Windsurf


## 🏷️ Attribution & Community Fork Notice

This extension is a community fork of the official Swift VS Code extension maintained by the Swift team. 

**Original Repository**: https://github.com/swiftlang/vscode-swift  
**Original Publisher**: swiftlang organization  
**License**: Apache 2.0 with Runtime Library Exception  

### Credits
All credit for the original work goes to:
- The Swift team at Apple Inc.
- The swiftlang organization and maintainers
- All contributors listed in [CONTRIBUTORS.txt](./CONTRIBUTORS.txt)

### Purpose of This Fork
This fork exists solely to provide the Swift VS Code extension on the Open VSX marketplace for users  that cannot access the Microsoft Visual Studio Marketplace due to licensing restrictions.

**No modifications have been made to the core functionality**. This is a direct republication with proper attribution to ensure broader accessibility of this excellent Swift development tool.

For the latest official updates and development, please refer to the original repository.

This extension adds language support for Swift to Windsurf, providing a seamless experience for developing Swift applications on all supported platforms. It supports:

* Code completion
* Jump to definition, peek definition, find all references, symbol search
* Error annotations and apply suggestions from errors
* Automatic generation of launch configurations for debugging with [LLDB DAP](https://marketplace.visualstudio.com/items?itemName=llvm-vs-code-extensions.lldb-dap)
* Automatic task creation
* Package dependency view
* Test Explorer view

# Documentation

The official documentation for this extension is available at [vscode-swift](https://docs.swift.org/vscode/documentation/userdocs)

This extension uses [SourceKit LSP](https://github.com/apple/sourcekit-lsp) for the [language server](https://microsoft.github.io/language-server-protocol/overviews/lsp/overview/), which powers code completion. It also has a dependency on the [LLDB DAP](https://marketplace.visualstudio.com/items?itemName=llvm-vs-code-extensions.lldb-dap) extension to enable debugging.

To propose new features, you can post on the [swift.org forums](https://forums.swift.org) in the [VS Code Swift Extension category](https://forums.swift.org/c/related-projects/vscode-swift-extension/). If you run into something that doesn't work the way you'd expect, you can [file an issue in the GitHub repository](https://github.com/swiftlang/vscode-swift/issues/new).

## Contributing

The Swift for Visual Studio Code extension is based on an extension originally created by the [Swift Server Working Group](https://www.swift.org/sswg/). It is now maintained as part of the [swiftlang organization](https://github.com/swiftlang/), and the original extension is deprecated. Contributions, including code, tests, and documentation, are welcome. For more details, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

To provide clarity on the expectations for our members, Swift has adopted the code of conduct outlined in the [Contributor Covenant](https://www.contributor-covenant.org). This widely recognized document effectively encapsulates our values. For more information, please refer to the [Code of Conduct](https://swift.org/code-of-conduct/).
