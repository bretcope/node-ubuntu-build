# Node.js Ubuntu Build

A simple install script for Ubuntu which accepts a version as an argument, then downloads and builds node.js from source followed by installing node-gyp (for compiling native modules).

> If you already have node installed, it is recommended to remove it before using this script.

This script can be cloned via git, or downloaded using `npm install ubuntu-build`.

## Example

To install node v0.11.9:

```
sudo ./install 0.11.9
```

Any version can be uninstalled using `sudo dpkg -r node`. To finish cleanup of any globally installed modules, use `sudo rm -rf /usr/local/lib/node_modules`.

## License

NO WARRANTY IS IMPLIED; use at your own risk. The script a modified version of the one [found here](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager#wiki-build-from-source), and no additional copyright is claimed. Feel free to use and modify as desired.
