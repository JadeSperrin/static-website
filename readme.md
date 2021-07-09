
# Static website setup
First switch to the correct version of node with `nvm use`. Then run npm install to obtain required packages and dependencies.


## Compilation with gulp
Compile SCSS & JS into dist folder by running `gulp`

### Useful to know about gulp compilation
- gulp-sourcemaps — maps the CSS styles back to the original SCSS file in your browser dev tools
- gulp-sass — compiles SCSS to CSS
- gulp-postcss — runs autoprefixer and cssnano (see below)
- autoprefixer — adds vendor prefixes to CSS
- cssnano — minifies CSS