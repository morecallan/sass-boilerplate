## Sassy Boilerplate
Boilerplate for compiling Sass into CSS. Features Grunt compiling and new file structure.

#### To Run Project [Node Must Be Installed]:
Global installs: `npm install http-server -g` & `npm install grunt-cli -g`

```
$ git clone https://github.com/morecallan/sass-boilerplate.git
$ cd sass-boilerplate
$ cd lib
$ bower install
$ npm install
$ cd ..
$ hs -c-1 (this will run http-server without caching issues)
This should show in your browser at localhost:8080
```

For developers [to lint the JS files, or update the styles]:
```
Open a new tab from the root project file.
$ cd lib
$ grunt
```
