# Museum Jobs Gateway

[Museum Gateway](http://museumgateway.com/)


## Notes

- Flipbook is possible through [yumpu](https://www.yumpu.com/en/account/create)


## Start
gulp

## Push
You can push, but don't merge into master. Master is the site files that are build during the deploy process


## Depoly
gulp deploy


## Current REPO
museumgateway/museumgateway.github.io

### Old REPO
museumjobsgateway/museumjobsgateway.github.io

It's confusing, but there was a last minute name change made to the project


## ISSUES
Sometimes gulp wont run. It seems like the is an issue with the vesion of node that was used at the time this project was created. Just delete the package-lock fire and re-install the packages

`npm i babel-core babel-preset-es2015 browser-sync del gulp gulp-autoprefixer gulp-changed gulp-concat gulp-evil-icons gulp-gh-pages gulp-imagemin gulp-notify gulp-plumber gulp-pug gulp-rename gulp-sourcemaps gulp-stylus gulp-todo gulp-uglify imagemin-pngquant pump`