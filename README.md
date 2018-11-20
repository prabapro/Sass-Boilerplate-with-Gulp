# Sass Boiler Plate with Gulp

### Included Gulp Tasks
* Compile .scss & .js
* Compress as min.css
* Image optimization

### Getting started
1. Install gulp globally (if you don't have already)\
```sudo npm install gulp-cli -g```

1. Initialize Node Packages\
```npm init```

1. Install Gulp locally to the project directory\
```npm install gulp -D```

1. Create ```gulpfile.js```
```touch gulpfile.js```

1. Install plugins\
```npm install node-sass gulp-sass gulp-autoprefixer gulp-sourcemaps gulp-imagemin --save-dev```

1. Create your markup files (HTML) in ```dist\``` directory

### How to run
1. Run ```gulp``` to start watching CSS & JS
1. Run ```gulp image``` to optimize images


#### Tree

```
├── README.md
├── dist
│   ├── css
│   │   ├── app.min.css
│   │   └── app.min.css.map
│   ├── images
│   └── js
│       └── script.js
├── gulpfile.js
└── src
    ├── js
    │   └── script.js
    └── scss
        ├── 1-utils
        │   ├── _functions.scss
        │   ├── _mixins.scss
        │   └── _variables.scss
        ├── 2-vendors
        │   ├── _bootstrap.scss
        │   ├── _jquery-ui.scss
        │   └── _reset.scss
        ├── 3-base
        │   ├── _base.scss
        │   └── _typography.scss
        ├── 4-layout
        │   ├── _footer.scss
        │   ├── _forms.scss
        │   ├── _grid.scss
        │   ├── _header.scss
        │   ├── _navigation.scss
        │   └── _sidebar.scss
        ├── 5-components
        │   ├── _buttons.scss
        │   ├── _carousel.scss
        │   ├── _cover.scss
        │   └── _dropdown.scss
        ├── 6-pages
        │   ├── _contact.scss
        │   └── _home.scss
        ├── 7-themes
        │   └── _default.scss
        ├── 8-vendors-extensions
        │   └── _addons.scss
        └── app.scss
  ```
