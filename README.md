**Gulp Simple Project**
Modern development workflow with Gulp



Make sure to run:
```
npm install 
```
Since the project you downloaded doesn't have Node dependencies installed.

List of dependencies:

**gulp-sass and node sass:** transform Sass into CSS

**gulp-autoprefixer:** adds vendor prefixes to CSS rules 

**gulp-cssnano:** minifies CSS

**gulp-concat:** merges several CSS or several JS files

**gulp-uglify:** minifies JS

**gulp-rename:** adds .min to the name of a minified file

**gulp-imagemin:** minifies images

**gulp-changed:** detects whether files were changed and excludes unchanged files: every time you run gulp all your files would not be rewritten regardless of whether the source files were changed

**gulp-clean:** clears the build directory and deletes everything in it

**browser-sync:** provides you with a simple web server and auto-reloads the page in all browsers on all devices



If there was issues - Make sure to update all dependencies via:
```
npm update
```



Folder Overview:
```
gulp-project/
└── assets/
└── src/
│    └── css/
│        └── global.scss 
│        └── main.scss 
│        └── ...
│    └── img/
│    └── js/
│        └── addition.js
│        └── script.js
│        └── ...
└── index.html
```
