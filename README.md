# MinLog

An easy to use light-weight logging Swift Package.

## Installation instructions:

To install the MinLog package through Swift Package Manager(SPM):
1. Open Xcode
2. Go to File -> Add Packages
3. On top right search bar, search for URL: https://github.com/TribalScale/MinLog.git
4. Add the package

Features of MinLog library:
This library debug prints the file name, function name, line number and a message. 
The logging has 5 levels: 
* Verbose: 👄
* Error: ❌
* Info: 📙
* Warning: 🔔
* Debug: 🧑‍💻

The library can be used in this way:
``` 
MinLog.v("Hello World")
```

The output will be:
```
👄👄👄 VERBOSE: FileName.swift - FunctionName(_:) at line 33[13]: Hello World 👄👄👄
```
