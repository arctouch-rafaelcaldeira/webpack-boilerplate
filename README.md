# Webpack Boilerplate

This is a really simple Webpack boilerplate that uses Babel loader with the preset-env Babel plugin preset.

## Requirements

* Node >= 8.10
* npm => 5.6

## Initializing

Simply install the project dependencies from the project root directory:

```bash
npm install
```

## Files/Folders Overview

* **/dist**: the public distribution directory, with Webpack generated files and the index.html file.
* **/src***: files to be bundled by Webpack.  
* **package.json**: a kind of project manifest. Reference: https://nodejs.dev/the-package-json-guide  
* **package-lock.json**: a manifestation of the manifest. Reference: https://docs.npmjs.com/files/package-lock.json.html
* **webpack.config.js**: webpack config file. Reference: https://webpack.js.org/configuration/  