# PVue Syntax
Syntax highlighting support for PVue files.

## Features
- Syntax highlighting for `.pvue` files
- Language configuration for PVue

## Release Notes
See [CHANGELOG.md](CHANGELOG.md)

PHPue is still early development!

## Install for Development
```
# Clone repository
git clone <your-repo-url>
cd pvue-syntax

# Package locally
npm install -g @vscode/vsce
vsce package

# Install the VSIX
code --install-extension pvue-syntax-*.vsix
```

IF you love PHPue Framework, then please help develop better syntax highlighting!

**Every little bit helps!!**

LINUX:
```bash
cp -r PHPue-SyntaxHighlighter ~/.vscode/extensions/pvue-syntax-0.0.1
```

WINDOWS:
# Command Prompt
```cmd
xcopy PHPue-SyntaxHighlighter %USERPROFILE%\.vscode\extensions\pvue-syntax-0.0.1 /E /I
```

# Or PowerShell
```powershell
Copy-Item -Path "PHPue-SyntaxHighlighter" -Destination "$env:USERPROFILE\.vscode\extensions\pvue-syntax-0.0.1" -Recurse
```
