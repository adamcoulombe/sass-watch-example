# How to Use
1. `git clone https://github.com/adamcoulombe/sass-watch-example new-project-folder` (downloads this repo into a new folder called `new-project-folder` )
2. `cd new-project-folder`
3. `npm install` (installs dependencies referenced in `package.json`  eg. `gulp` and `node-sass`)
4. `gulp sass` creates the css folder and file
5. `gulp sass:watch` (runs the `sass:watch` task, defined in the `gulpfile.js`)
6. modify `sass/styles.scss` and watch it (re)compile into a css folder