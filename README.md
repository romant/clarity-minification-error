### reproduce bug
```
npm run build
```

you'll see

```
npm run build 

> hello@0.1.0 build /Users/roman/playpen/hello
> vue-cli-service build


 ERROR  Error: CSS minification error: postcss-svgo: Error in parsing SVG: Invalid character in tag name
        Line: 0
      Column: 5
Char: +. File: css/chunk-vendors.7e10bad3.css
Error: CSS minification error: postcss-svgo: Error in parsing SVG: Invalid character in tag name
Line: 0
Column: 5
Char: +. File: css/chunk-vendors.7e10bad3.css
    at /Users/roman/playpen/hello/node_modules/@intervolga/optimize-cssnano-plugin/index.js:106:21
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! hello@0.1.0 build: `vue-cli-service build`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the hello@0.1.0 build script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

```