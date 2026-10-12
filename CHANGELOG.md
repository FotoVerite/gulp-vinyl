# Changelog

## 1.0.0 (2026-10-12)


### ⚠ BREAKING CHANGES

* Clone streams with teex
* No longer await all streams to flow before emitting data
* Remove cloneable-readable ([#155](https://github.com/FotoVerite/gulp-vinyl/issues/155))
* Remove `inspect` method & rely on `util.inspect.custom` symbol
* Normalize repository, dropping node <10.13 support ([#151](https://github.com/FotoVerite/gulp-vinyl/issues/151))

### Features

* Clone streams with teex ([d4868f4](https://github.com/FotoVerite/gulp-vinyl/commit/d4868f4ec1e8b43f1be5b066b55907b29d43c383))
* No longer await all streams to flow before emitting data ([d4868f4](https://github.com/FotoVerite/gulp-vinyl/commit/d4868f4ec1e8b43f1be5b066b55907b29d43c383))
* Remove cloneable-readable ([#155](https://github.com/FotoVerite/gulp-vinyl/issues/155)) ([d4868f4](https://github.com/FotoVerite/gulp-vinyl/commit/d4868f4ec1e8b43f1be5b066b55907b29d43c383))


### Bug Fixes

* Add option to end stream produced by .pipe, defaulted to true (fixes [#2](https://github.com/FotoVerite/gulp-vinyl/issues/2)) ([b8099c4](https://github.com/FotoVerite/gulp-vinyl/commit/b8099c47f773385c6fb2029d4203a43da06265e2))
* Align file clone options with documentation ([73c1cdd](https://github.com/FotoVerite/gulp-vinyl/commit/73c1cdd26356e0759129f726076758fc118dfbee))
* Allow history to be set in the constructor (closes [#35](https://github.com/FotoVerite/gulp-vinyl/issues/35)) ([dc07a97](https://github.com/FotoVerite/gulp-vinyl/commit/dc07a973967e97a7b455fbd074e854611190471a))
* Avoid unused require ([33c6ebf](https://github.com/FotoVerite/gulp-vinyl/commit/33c6ebf0f28f6f2b2a7053a816c0b5e38b761d8e))
* Clone history properly, instead of as a custom property ([68d4448](https://github.com/FotoVerite/gulp-vinyl/commit/68d444844dad52cdba65448d0dedc369b529b300))
* Clone with constructor ([#91](https://github.com/FotoVerite/gulp-vinyl/issues/91)) ([94c4e02](https://github.com/FotoVerite/gulp-vinyl/commit/94c4e026714623114111bdc40e3f1037ef19b6dd))
* Correct error message in stem accessor ([3e04607](https://github.com/FotoVerite/gulp-vinyl/commit/3e0460777b9c3e729d5b9f021d47fb15b32c7f6e))
* Drop clone-stats dependency by cloning with `Object.create` ([#162](https://github.com/FotoVerite/gulp-vinyl/issues/162)) ([f56ac3d](https://github.com/FotoVerite/gulp-vinyl/commit/f56ac3dece382e15879246cb743f66cf43dfd0e3))
* Ensure isVinyl always returns a boolean ([afbbb05](https://github.com/FotoVerite/gulp-vinyl/commit/afbbb05278bcff57fb24b43cecf809a8420d9cf1))
* Ensure symbolic link files are cloned properly (closes [#143](https://github.com/FotoVerite/gulp-vinyl/issues/143)) ([#146](https://github.com/FotoVerite/gulp-vinyl/issues/146)) ([b5e1570](https://github.com/FotoVerite/gulp-vinyl/commit/b5e15706f8be45e7c2c28369dcb39173d034ff57))
* Proxy cwd if base is set to same value (fixes [#129](https://github.com/FotoVerite/gulp-vinyl/issues/129)) ([07e4093](https://github.com/FotoVerite/gulp-vinyl/commit/07e409300e8891bef644c2b83b586c42bfd1c716))


### Miscellaneous Chores

* Normalize repository, dropping node &lt;10.13 support ([#151](https://github.com/FotoVerite/gulp-vinyl/issues/151)) ([9302802](https://github.com/FotoVerite/gulp-vinyl/commit/9302802b411d6ce9e204d98d40d1d07fe2eaf1c2))
* Remove `inspect` method & rely on `util.inspect.custom` symbol ([9302802](https://github.com/FotoVerite/gulp-vinyl/commit/9302802b411d6ce9e204d98d40d1d07fe2eaf1c2))

### [3.0.1](https://www.github.com/gulpjs/vinyl/compare/v3.0.0...v3.0.1) (2025-05-31)


### Bug Fixes

* Drop clone-stats dependency by cloning with `Object.create` ([#162](https://www.github.com/gulpjs/vinyl/issues/162)) ([f56ac3d](https://www.github.com/gulpjs/vinyl/commit/f56ac3dece382e15879246cb743f66cf43dfd0e3))

## [3.0.0](https://www.github.com/gulpjs/vinyl/compare/v2.2.1...v3.0.0) (2022-09-26)


### ⚠ BREAKING CHANGES

* Clone streams with teex
* No longer await all streams to flow before emitting data
* Remove cloneable-readable (#155)
* Remove `inspect` method & rely on `util.inspect.custom` symbol
* Normalize repository, dropping node <10.13 support (#151)

### Features

* Clone streams with teex ([d4868f4](https://www.github.com/gulpjs/vinyl/commit/d4868f4ec1e8b43f1be5b066b55907b29d43c383))
* No longer await all streams to flow before emitting data ([d4868f4](https://www.github.com/gulpjs/vinyl/commit/d4868f4ec1e8b43f1be5b066b55907b29d43c383))
* Remove cloneable-readable ([#155](https://www.github.com/gulpjs/vinyl/issues/155)) ([d4868f4](https://www.github.com/gulpjs/vinyl/commit/d4868f4ec1e8b43f1be5b066b55907b29d43c383))


### Miscellaneous Chores

* Normalize repository, dropping node <10.13 support ([#151](https://www.github.com/gulpjs/vinyl/issues/151)) ([9302802](https://www.github.com/gulpjs/vinyl/commit/9302802b411d6ce9e204d98d40d1d07fe2eaf1c2))
* Remove `inspect` method & rely on `util.inspect.custom` symbol ([9302802](https://www.github.com/gulpjs/vinyl/commit/9302802b411d6ce9e204d98d40d1d07fe2eaf1c2))
