Windows command-line utility to calculate the checksum of a file.

## Features

- Supported algorithms : CRC32, CRC64, MD4, MD5, PANAMA, RIPEMD, SHA-1, SHA-256, SHA-384, SHA-512, SHA3-256, SHA3-256, SHA3-384, SHA3-512, TIGER, ...
- Copy the hash result to the clipboard
- Display the hash result in a dialog box
- Add to the shell context menu (optional)

## Package Parameters

- `/UseInf:` - Change the inno setup configuration file to use/save when installing

### Examples

`choco install hash`

`choco install hash --params "'/UseInf:C:\hash.inf'"`