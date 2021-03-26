# WASMpsx
A fork of TJWei's PlayStation emulator to use for your own purposes.
![Screenshot](/screenshots/turismo.png)

# Usage
To use WASMpsx, use this example script:

```
WASMpsx.loadUrl('URL of PlayStation ISO (only .bin and .iso are accepted)');
```

To add a display, add a ```<canvas>``` element with the ID of "wasmpsx-canvas."

Example element:
```
<canvas id="wasmpsx-canvas" width="640" height="480"></canvas>
```

And to read files (not URLs), use this script:

```
WASMpsx.readFile(file here);
```
