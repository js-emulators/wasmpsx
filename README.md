# WASMpsx
A fork of TJWei's PlayStation emulator to use for your own purposes.
![Screenshot](/screenshots/turismo.png)

# Adding to website
To add this to your website, click [here](http://download-wasmpsx.glitch.me/) so you can download the WASMpsx source code as a ZIP file.

Then, add them to your website and create a ```<script>``` tag like this:

 ```
 <script src="path/to/wasmpsx.min.js"></script>
 ```
 
 Also, please make sure that your site correctly serves .wasm files. To do this:
 ## Apache
 ```
 AddType application/wasm .wasm
```
## Nginx
```
types { application/wasm wasm; }
```

After those steps, you are ready to use WASMpsx!


# Usage
To use WASMpsx, use this example script:

```
document.getElementById('my-wasmpsx-element').loadUrl('/path/to/granturismo.bin');
```

#### Note: does not come with example ROM files.

And to load files, not URLs, use this script:

```
document.getElementById('my-wasmpsx-element').readFile(file here, useful for file input);
```

To add a display, add a ```wasmpsx-player``` element.

Example element:
```
<wasmpsx-player id="my-wasmpsx-element"></wasmpsx-player>
```
