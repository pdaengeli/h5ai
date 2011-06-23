# <img src="http://github.com/lrsjng/h5ai/raw/master/src/h5ai/images/folder.png" width="24px" height="24px" alt="logo" title="logo" style="display: inline" /> &#160; h5ai v0.3 &#160; · &#160; a beautified Apache index


## Screenshots

<a href="http://github.com/lrsjng/h5ai/raw/master/resources/h5ai-v0.2.1-details.png" target="_blank">
	<img src="http://github.com/lrsjng/h5ai/raw/master/resources/h5ai-v0.2.1-details.png" width="400px" alt="screenshot" title="screenshot" style="display: inline" />
</a>
&#160; &#160; &#160;
<a href="http://github.com/lrsjng/h5ai/raw/master/resources/h5ai-v0.2.1-icons.png" target="_blank">
	<img src="http://github.com/lrsjng/h5ai/raw/master/resources/h5ai-v0.2.1-icons.png" width="400px" alt="screenshot" title="screenshot" style="display: inline" />
</a>


## Live example

View a [sample folder](http://repo.larsjung.de/h5ai-sample)  
*(the files are all empty to save webspace)*


## Install

Everything you need is located in folder `target`.

* Copy folder `h5ai` to the web-root directory of your server or alternativly set an alias `/h5ai/` to
  this folder.
* Add the content of file `dot.htaccess` to the `.htaccess` file inside the directory
  you want to be styled (you might have to create this file). This directory and any subdirectories will be
  styled by h5ai.

Optionally add `h5ai.header.html` and/or `h5ai.footer.html` files to any of the styled folders to [display
custom top or bottom sections](http://repo.larsjung.de/h5ai-sample/customize). The content of those files
will be wrapped by `<header>` and `<footer>` tags.


## Changelog

### v0.3
*2011-06-23*

* included build stuff, files previously found in the base directory are now located in folder `target`
* styles and scripts are now minified
* added Modernizr 2.0.4 for future use
* updated jQuery to version 1.6.1


### v0.2.3
*2011-06-17*

* more refactoring in main.js
* ~~added custom js support, and global includes~~ *removed, only custom top and bottom sections supported*


### v0.2.2
*2011-06-16*

* refactored a lot, added some comments
* included fixes from [NumEricR](http://github.com/NumEricR/h5ai)
* added top/bottom message support, only basicly styled


### v0.2.1
*2011-06-16*

* fixed croped filenames
* fixed missing .png extension in header
* added some color to the links
* added changelog


### v0.2
*2011-06-15*

* added icon view


## Author

[Lars Jung](http://larsjung.de)  
[h5ai on github](http://github.com/lrsjng/h5ai)  


## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a>  
This project is licensed under the [CC BY-SA 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/).  
It is based on
[HTML5 Boilerplate](http://html5boilerplate.com),
[jQuery](http://jquery.com),
[Modernizr](http://www.modernizr.com) and
[Faenza icon set](http://tiheum.deviantart.com/art/Faenza-Icons-173323228),
please respect their rights.

