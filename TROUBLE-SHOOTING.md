### Various challenges you may encounter when, trying to get your VSCode env setup

1. git fails to work - `xcrun: error`

probably a mac os upgrade (e.g. Mojave to Catalina ) issue you will see on using git commands:

```bash
git status
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), 
missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
```
dependancies on xcode!

```sh
xcode-select --install
```
You will be prompted to install command line developer tools!

[Solution ](https://tips.tutorialhorizon.com/2015/10/01/xcrun-error-invalid-active-developer-path-library-developer-commandline-tools-missing-xcrun/)

2. The `gRPC fails to rebuild` issue

#### IBM Blockchain Platform Extension updated to v1.0.20
_Release date: February 20th 2020_

Announcements
---
* We’re still waiting for the gRPC v1.25.0 binaries to be published so you may be affected by [this issue](https://github.com/IBM-Blockchain/blockchain-vscode-extension/issues/1621), where gRPC fails to rebuild when using VS Code 1.40.x.
   > Please see [this comment](https://github.com/IBM-Blockchain/blockchain-vscode-extension/issues/1621#issuecomment-552926559) for a workaround.
