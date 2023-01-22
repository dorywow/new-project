# Simple Webpack Project
Example of basic Webpack config for a website.

Use node verison 14+
```
$ nvm install 14
$ nvm use 14
```

Install all packages:
```
$ npm install
```

Run webpack
```
$ npm run build
```

Done! Open index.html in browser.

----

### Notice about develop mode
Sass Watcher at Vs Code.
1. Go to the app section and looking for Live Sass Compiler and install it.
2. At the bottom, click on Watch Sass.
3. Uncomment `<link rel="stylesheet" href="src/sass/styles.css">` and comment `<link rel="stylesheet" href="dist/bundle.css">` **in index.html**.
4. Now you can compile inside Vs Code and you don´t have to run any command.
