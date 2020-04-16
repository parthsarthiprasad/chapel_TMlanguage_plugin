# chapel_TMlanguage_plugin
This repository holds the custom plugin to create a chapel_tmLanguage plugin.

The original repository 
[chapel-tmbundle](https://github.com/chapel-lang/chapel-tmbundle) holds the original repository for tmbundle.
The issues I faces was using chapel.tmLanguage directly as a vscode plugin related to yo-code generator issue with
tmlanguage and it only accepts chapel.tmLanguage.json see [this](https://github.com/microsoft/vscode-generator-code/issues/100#issuecomment-455814925)

## Hence this repository holds the code steps taken
- generate code with new defintion and language specification using YO code generator
- Convert plist type XML format to json object using [plist-to-json-convertor](https://github.com/parthsarthiprasad/plist-to-json?organization=parthsarthiprasad&organization=parthsarthiprasad)
- Follow ./chapel/vsc-extension-quickstart.md to use custom language plugin.
