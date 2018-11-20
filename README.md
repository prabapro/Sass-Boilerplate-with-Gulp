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
