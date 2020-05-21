# esatan README

This is the README for VS Code extension esatan. Code Highlighting.

## Features

We wil see.

## Installing
Install node.js and VSCE ("Visual Studio Code Extensions")

```console
npm install -g vsce
```
then install the extension using
```console
cd vsix
code --install-extension esatan-0.0.1.vsix
```

For compiling .d file, install Code Runner extension and set:
```javascript
"code-runner.executorMap": {
    "esatan": "C:\\path\\to\\esatan.bat e $dir $fileNameWithoutExt $fileName . no"
    }
```  
in the user settings.json file.

## Developing
To develope the extension, run the package.json file from VS Code. 
The changes must be updates in the .vsix file by doing
```
vsce package
```
and then move the .vsix file to the \vsix directory.

User must installa again the extension.

## Extension Settings

??

## Known Issues

Many

**Enjoy!**
