<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

## About this template

This template intergrates Laravel with some addons, most important the [Custom Module Loader](https://github.com/zonneplan/laravel-module-loader) from [@Zonneplan](https://github.com/zonneplan/).

Because of the module loader some customization is needed. Most of the work is already done. When using the module loader most (almost all of) the `artisan` command won't work anymore. This is because the namespace has changed too much; Laravel can not see everything you want it to. To tackle this problem two solutions have been provided, one of them needs more customization to let it work in your way. 

These _two sollutions_ conclude the usage of the following two.
- https://github.com/jondot/hygen
- https://github.com/diego-rlima/artisan-make-file-location

Please take a look at these packages. You can still use this template with reading the above, but it will much simpler if you did so. Hygen and artisan-make-file-location (amfl) are (of use) both some kind of templating engine. Hygen is a JS templating engine itself, where amfl uses the existing `artisan make:...` commands intstead.
