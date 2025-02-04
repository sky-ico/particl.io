# Particl.io

> Don't edit files in `_site/` directory directly! Those files are automatically generated. Any changes manually edited there will be overwritten. Edit `.md` files in root dir or corresponding files in `_layouts/` and `_includes` directories depending on your change.

## Howto

* **Update wallet version numbers:** edit `_data/versions.yml`


## Info

* use `gulp`!
    - don't edit `app.css` CSS directly! edit files in `scss/` instead
    - don't edit `all.js` => add/edit files in `js/src/` (if you're adding new files, you'll have to add them also in `gulpfile.js` in `gulp.task('scripts')` section)


## Contribute

1. clone the repo
2. install `node` and `npm` if you don't have them already
3. `npm install` to fetch dependencies
4. `gulp watch` for:
    - Sass => CSS autocompiling when changed
    - concat/minify & uglify JS
    - start local BrowserSync server with realtime reloading


### FYI

* site works without JavaScript (newsletter sign-up suprisingly as well)
* site is mobile-first
* local links should have `scroll` class (for smooth scrolling); external `ext` class


## TODO

* Tweaks
    - [ ] illustrations to SVG
    - [ ] decently animate them
    - [ ] graphs for PART Token > Distribution
    - [ ] "learn more" buttons to each section in mobile (toggle content)
    - [ ] Piwik/Analytics?
