Laravel-Bower-Grunt
===================

A Laravel 4 - Bower, Bootstrap 3, Grunt Workflow with Live Reload

## Installation

1. `git clone https://github.com/JasonMortonNZ/Laravel-Bower-Grunt.git` into the root of your Laravel 4 project then change into that directory.
2. Run `npm install` (add `sudo` if on OSX or Linux)
3. Run `bower install`
4. Finally run `grunt` and you'll end up with two files in your public directory - style.min.css & script.min.js
5. If you want to watch for files changes, and trigger live reloading of the browser, simply run `grunt watch`.

**Note:** script.min.js includes jQuery ~1.10.3 and style.min.css includes font-awesome.
