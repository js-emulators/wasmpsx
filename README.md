# WASMpsx
A fork of TJWei's PlayStation emulator to use for your own purposes.
![Screenshot](/screenshots/turismo.png)

# Usage
To use WASMpsx, use this example script:

```
WASMpsx.loadUrl('URL of PlayStation ISO (only .bin and .iso are accepted)');
```

And to load files, not URLs, use this script:

```
WASMpsx.readFile(file here, useful for file input);
```

To add a display, add a ```wasmpsx-player``` element.

Example element:
```
<wasmpsx-player width="640" height="480"></wasmpsx-player>
```
