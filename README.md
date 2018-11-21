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

1. Install plugins\
```npm install node-sass gulp-sass gulp-autoprefixer gulp-sourcemaps gulp-imagemin gulp—rename --save-dev```

1. Create your markup files (HTML) in ```dist\``` directory

### How to run
1. Run ```gulp``` to start watching CSS & JS
1. Run ```gulp image``` to optimize images


#### Tree

```
├── dist
│   ├── css
│   │   ├── app.min.css
│   │   └── app.min.css.map
│   ├── images
│   ├── index.html
│   └── js
│       └── script.min.js
├── gulpfile.js
└── src
    ├── js
    │   └── script.js
    └── scss
        ├── _base_main.scss
        ├── _base_typography.scss
        ├── _components_buttons.scss
        ├── _components_carousel.scss
        ├── _components_cover.scss
        ├── _components_dropdown.scss
        ├── _layout_footer.scss
        ├── _layout_forms.scss
        ├── _layout_grid.scss
        ├── _layout_header.scss
        ├── _layout_navigation.scss
        ├── _layout_sidebar.scss
        ├── _pages_contact.scss
        ├── _pages_home.scss
        ├── _themes_main.scss
        ├── _utils_functions.scss
        ├── _utils_mixins.scss
        ├── _utils_variables.scss
        ├── _vendors_bootstrap.scss
        ├── _vendors_extensions_main.scss
        ├── _vendors_jquery_ui.scss
        ├── _vendors_reset.scss
        └── app.scss
  ```
