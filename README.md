# Mac OSX shortcuts to PC in Remote Desktop sessions  

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

Go to https://ke-complex-modifications.pqrs.org/#mac_osx_on_rdp in browser and click Import.

# Development and testing

For local testing and development you can import JSON using `file://` URL. 

Using Terminal `open karabiner://karabiner/assets/complex_modifications/import?url=<JSON_URL>`
or just browse in a browser to `karabiner://karabiner/assets/complex_modifications/import?url=<JSON_URL>`.

Karabiner will do the rest! =)
