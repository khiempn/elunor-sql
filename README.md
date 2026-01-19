# SSMS Extension - Elunor SQL [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/khiempn/elunor-sql/blob/main/LICENSE) ![latest v1.0.1](https://img.shields.io/badge/latest-1.0.1-green)

This is a custom extension for **SQL Server Management Studio (SSMS)** that provides enhanced functionality to improve your SQL development workflow.

## ✨ Features

- SQL Complete
- SQL Snippets Manager
- Grid Result Aggregate
- Grid Result Aggregate
- SQL History
  
## 📦 Installation - Using Setup File

1. Download file `elunorsql_setup.exe`
2. Click Next to Install
   
## 📦 Installation - Using Vsix File

1. Rename `ElunorSQL.vsix` to `ElunorSQL.zip`.
2. Extract the contents of the `.zip` file.
3. Copy the extracted folder to:

   ```
   C:\Program Files (x86)\Microsoft SQL Server Management Studio 1x\Common7\IDE\Extensions\Elunor SQL\
   ```

4. Make sure the folder contains the `extension.vsixmanifest` file and other binaries.
5. Unlock the files using PowerShell
   ```
      PS C:\> dir C:\Program Files (x86)\Microsoft SQL Server Management Studio 1x\Common7\IDE\Extensions\Elunor SQL\ | Unblock-File
   ```
6. Restart SSMS.

> ⚠️ Manual installs may not work properly if the extension is not fully registered.

## 🧪 Compatibility
- SSMS 17.x (tested)
- SSMS 18.x (tested)
- SSMS 19.x (tested)
- SSMS 20.x (tested)
## ☕ Buy Me a Coffee

If you find this extension helpful, you can support my work here:

👉 [https://buymeacoffee.com/elunorsql](https://buymeacoffee.com/elunorsql)

Your support helps me build more great tools for the community!

## 📃 License

MIT License

---

Created with ❤️ by [Elunor Team].
