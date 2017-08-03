# gulp-docx-to-html

Converts a word document (.docx) to html with gulp-ready and pipe-ready input/output.  Unnecessary clutter consistent with .docx files is stripped.  The file extension is also changed to .html before being output.

## Getting Started

To install, simply use the npm installer.



### Prerequisites

Requires utilization of npm and gulp.

```
npm init
npm install
npm install --save gulp
```


## Deployment


```
    npm install gulp-docx-to-html
````

```
    var docxHtmlConverter = require('gulp-docx-converter);
    gulp.src('someFileDirectory/')
        .pipe(docxHtmlConverter())
        .pipe(gulp.dest('outputDirectory/'));
```



