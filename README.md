[K-MUG](http://k-mug.net) official website source code
=================

[![Build Status](https://travis-ci.org/k-mug/k-mug.github.io.svg?branch=master)](https://travis-ci.org/k-mug/k-mug.github.io)
<img src="https://k-mug.herokuapp.com/badge.svg">

### About 
All the geeks of the community can look into contributing to this repo and make this an epic mess :) 

### Quick-start guide
1. [Fork](https://github.com/k-mug/k-mug.github.io/fork) this repo
2. Clone locally
3. Create a new topic branch
4. Commit your changes in logical chunks
5. Locally merge (or rebase) the upstream development branch into your topic branch
6. Push your topic branch up to your fork
7. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/)

[Check out the detailed contibution explainer](https://github.com/k-mug/k-mug.github.io/blob/master/CONTRIBUTING.md)


## Local development

Check if you have [all requirements for local environment](http://jekyllrb.com/docs/installation/).
To install all development dependencies install [Bundler](http://bundler.io/).
```bash
    gem install bundler
``` 
and run next command from root folder:

```bash
  bundle install
```  

To start Jekyll run:
```bash
    jekyll serve -w
```

Or try this:
```bash
    bundle exec jekyll serve
```
Site will be available at http://127.0.0.1:4000/ or http://localhost:4000/ (on Windows)

**NOTE:** in this mode all changes to html and data files will be automatically regenerated, but after changing ```_config.yml``` you have to restart server.

### Sass(Compass) support
**Note:** You need to install [Node.js](http://nodejs.org/download/)

To watch changes of `.sass` files and compile it to the `.css` on a fly change property `safe: true` to `safe: false` in `_config.yml`.
**Note: It works only on local machine, because GitHub runs Jekyll in `--save` [mode](https://help.github.com/articles/using-jekyll-with-pages/#configuration-overrides)**

Learn more about Sass development from [documentation](https://github.com/k-mug/k-mug.github.io/wiki/Sass-development).


### Resource optimizations (optional)

You can optimize images and minify css and javascript automatically (for now only on Windows).
But for Mac OS users available amazing tool - [imageoptim](https://imageoptim.com/). Thanks [@raphaelsavina](https://github.com/raphaelsavina) for link.
Optimize all images by running this script from `/automation/images/` folder:
```bash
    all_image_optimization.bat -d -jtran -pout -pquant -optip -gsicle -svgo
```

To minify CSS and JS run `minify_js.bat` (for Windows) and `minify_js.sh` (for Linux and MacOS) from `/automation/minifying/` folder:
```bash
    minify_js.bat
```

Learn more about available optimization options from [documentation](https://github.com/k-mug/k-mug.github.io/wiki/Resources-optimizations).

### Documentation
Quick-start guide is not enough? Checkout [full documentation](https://github.com/k-mug/k-mug.github.io/wiki).

### Used libraries
* [Bootstrap](https://github.com/twbs/bootstrap)
* [Animate.css](https://github.com/daneden/animate.css)
* [Waves](https://github.com/publicis-indonesia/Waves)
* [jquery.appear](https://github.com/bas2k/jquery.appear)
* [jQuery countTo Plugin](https://github.com/mhuggins/jquery-countTo)
* [Typed.js](https://github.com/mattboldt/typed.js)
* [Sticky-kit](https://github.com/leafo/sticky-kit)


See [list of contributors](https://github.com/k-mug/k-mug.github.io/graphs/contributors)

Maintainers: [@jerriclynsjohn](https://github.com/jerriclynsjohn) and [@anuraj](https://github.com/anuraj).



