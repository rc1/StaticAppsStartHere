# Static HTML and assets generator

`gulp` to build

`gulp watch` to build on file changes

`gulp serve` to serve

`gulp clean` to remove the build folder

### JavaScript

Files in `./js` uglyfied and babeled, with source maps, and placed in `./build`

### Less/CSS

Files in `./less` converted to css and placed in `./build`  
Files in `./less/include` will be ingored.

### Jade

Files in `./jade` converted to html and placed in `./build`

### Copy

Files and folders in `./copy` will be copied into `./build`