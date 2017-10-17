
> Static asset revisioning by appending content hash to filenames
> `recharge.css` → `recharge.css?v=66704ea636`

Based on [gulp-dev](https://www.npmjs.com/package/gulp-rev)

## Install

```
$ npm install --save-dev gulp-rev-params
```


## Usage

```js
var gulp = require('gulp');
var rev = require('gulp-rev-params');

gulp.task('default', function () {
	return gulp.src('src/*.css')
		.pipe(rev())
		.pipe(gulp.dest('dist'));
});
```


## Works with gulp-rev-collector-params

- [gulp-rev-collector-params](https://www.npmjs.com/package/gulp-rev-collector-params) 

## License

MIT 