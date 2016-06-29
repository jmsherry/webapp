#Generated Webapp
##Intro
This project contains the code that is generated via [https://github.com/yeoman/generator-webapp](https://github.com/yeoman/generator-webapp)

It has been modified to use jade using the following instructions:
[https://github.com/yeoman/generator-webapp/blob/master/docs/recipes/jade.md](https://github.com/yeoman/generator-webapp/blob/master/docs/recipes/jade.md)

##Usage
Make sure that you have `yeoman` (just worth having), `gulp`, `gulp-cli` and `bower` installed, by typing `npm install -g yo gulp gulp-cli bower` into your terminal and hitting return.

Once you've unzipped this somewhere then you'll have to do `npm install`, to get the node modules that it uses.

When that's done, type `gulp serve` into the terminal and hit return. The terminal should start printing lines, then your browser should open with a new page visible. This is your start point...

##Technologies
* **SASS (scss)** - [http://sass-lang.com/](http://sass-lang.com/)
* **jade** - [http://jade-lang.com/](http://jade-lang.com/)

##Build process (just FYI)
[**yeoman**](http://yeoman.io/) is the tool that 'scaffolds' your project. It makes all the files by following a pattern known as a 'generator'. Depending on what type of project you are doing you'd install that generator and then use yeoman to run it. A searchable list of generators is available [here](http://yeoman.io/generators/).

[**bower**](http://bower.io/) is a package manager for front-end packages. You can search for which ones are available [here](https://bower.io/search/). Want to install moment.js?? Go to your command line and type `bower install moment --save`, and you're done! It'll be written straight into your page for you.

[**gulp**](http://gulpjs.com/) is a task runner. You use it to do common tasks, like image or javascript optimisation, running tests, running the live server that you're seeing when you do `gulp serve`, etc.
