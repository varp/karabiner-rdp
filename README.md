# MAC OSX shortcuts to PC in Remote Desktop sessions  

Translate MAC OS X shortcuts to PC equivalent during remote sessions. The
following applications input:
```
"bundle_identifiers": 
[
    "^com\\.microsoft\\.rdc$",
    "^com\\.microsoft\\.rdc\\.mac$",
    "^com\\.microsoft\\.rdc\\.macos$",
    "^com\\.microsoft\\.rdc\\.osx\\.beta$",
    "^com\\.thinomenon\\.RemoteDesktopConnection$",
    "^com\\.teamviewer\\.TeamViewer$",
    "^com\\.vmware\\.horizon$"
]
```
will be monitored for keyboard shortcuts and will be translated to tss PC equivalent.


# Install

For local testing and development you can import JSON using `file://` URL. 

Using Terminal `open karabiner://karabiner/assets/complex_modifications/import?url=<JSON_URL>`
or just browse in Safari to `karabiner://karabiner/assets/complex_modifications/import?url=<JSON_URL>`.

Just replace `<FULL_FILE_PATH>` with path of the project on your machine to get properly encoded URL:
```
php -r 'echo "karabiner://karabiner/assets/complex_modifications/import?url=". urlencode("file://<FULL_FILE_PATH>/mac_osx_on_rdp.json").PHP_EOL; 
```

Karabiner will do the rest! =)
