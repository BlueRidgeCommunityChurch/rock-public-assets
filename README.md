# rock-public-assets

- css
  - [blue-ridge.css](https://blueridgecommunitychurch.github.io/rock-public-assets/css/blue-ridge.css)
  - [blue-ridge-fix.css](https://blueridgecommunitychurch.github.io/rock-public-assets/css/blue-ridge-fix.css)
  
- refactoring
  - The CSC I moved from "css/blue-ridge.css" to "vendor/assets/css/vendor.css" is marked with comments.
  - In "css/blue-ridge.css", I commented out the first 132 lines with no ill effects on http://rock.blue-ridge.org/
  - As far as I can tell the remaining code in "css/blue-ridge.css" is only twitter bootstrap code -- nothing else.
  - When I'd attempted to move that bootstrap code into the 'vendor' folder, the website got messed up.
  - Also, when I attempted to rename "blue-ridge.css" to "bootstrap-file.css" the website broke as well.  So I switched it back to the original name and kept the code in it.
  - BTW, I'd created a git branch off "gh-pages" called "refactored-gh-pages" to do these edits.
