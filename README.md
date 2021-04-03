# WASMpsx
A fork of TJWei's PlayStation emulator to use for your own purposes.
![Screenshot](/screenshots/turismo.png)

# Adding to website
To add this to your website, download these four scripts:

### - wasmpsx.min.js
### - wasmpsx_worker.js
### - wasmpsx_worker.wasm
### - wasmpsx_ww.wasm

Then, add them to your website and create a ```<script>``` tag like this:

 ```
 <script src="path/to/wasmpsx.min.js"></script>
 ```

After those steps, you are ready to use WASMpsx!


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
<wasmpsx-player></wasmpsx-player>
```
