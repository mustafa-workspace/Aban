# Aban

**Aban** is an application designed to enable people to share their articles on various topics from around the world. This platform simplifies the process of utilizing these articles for your research and writing needs.

---

## Features
- **Global Sharing**: Share articles on diverse topics from around the globe.
- **User-Friendly**: Easy to use for everyone, whether researching or writing.
- **Optimized Design**: Built with modern tools and responsive frameworks.

---

## Built With

The project utilizes the following technologies:
- **HTML**, **CSS**, **JavaScript**
- **Sass**
- **PugJS**
- **GulpJS**
- **Bootstrap**
- **Awesome Lib**

---

## Installation

Follow these steps to set up and run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/mustafa-worksapce/Aban.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Aban
   ```

3. Install the required dependencies:
   ```bash
   npm install
   ```

4. Required gulp plugins (add these to your `gulpfile.js`):
   ```javascript
   const gulp = require("gulp"); // Include gulp
   const gulpconcat = require("gulp-concat"); // Concatenation
   const prefix = require("gulp-autoprefixer"); // Prefix webkit
   const sass = require("gulp-sass")(require('sass')); // Sass
   const pugjs = require("gulp-pug"); // PugJS
   const sourcemaps = require("gulp-sourcemaps"); // Search inside files
   const livereload = require('gulp-livereload');
   const uglify = require('gulp-uglify'); // Compress JavaScript
   const minifed = require("gulp-minify");
   const notify = require("gulp-notify"); // Notifications
   const compres_zip = require("gulp-zip"); // Compress files
   ```

5. Start the development server:
   ```bash
   gulp
   ```

6. Open your browser and go to `http://localhost:<8000>` to see the application in action.

---

## Contribution

Currently, no contributions are being accepted. You can contact me directly for further discussions.

---

## Contact

- **Email**: [mjofficialdeveloper@gmail.com](mailto:mjofficialdeveloper@gmail.com)
- **LinkedIn**: [Mustafa Jamal](https://www.linkedin.com/in/mustafajamalofficial/)

---

Thank you for checking out **Aban**! Feel free to explore, use, and share your valuable feedback.
