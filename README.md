example-ember-with-middleman, Write Ember.js App With Middleman
=================================================================

Check out [Live Demo](https://gutenye.github.com/example-ember-with-middleman)

* Use `sprockets` to manage javascript assets. 
* Use `sass` to manage css assets.
* Use `sprockets-handlebars_template` to compile handlebars.

**Source Code Layout**

	vendor/
		javascripts/
		stylesheets/
	source/
		index.html
		stylesheets/
		images/
		app/
			main.js
			routes.js
			models/ foo.js
			views/ foo_view.js
			templates/ foo.handlebars

**Development**

	build install
	rake server
	
**Build The Site**

	rake build

**Deploy To Github Pages**

	rake deploy

**Resources**

* [ember.js](http://www.emberjs.com/): A JavaScript framework for creating ambitious web applications 
* [middleman](http://middlemanapp.com/): Hand-crafted frontend development 
* [sprockets-handlebars_template](https://github.com/GutenYe/sprockets-handlebars_template): a handlebars template for sprockets 

**Copyright**

(the MIT License)

Copyright (c) 2012 Guten

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.