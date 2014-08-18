# Alloy *Loading* widget - Test

This is the test branch for the [nl.fokkezb.loading](https://github.com/FokkeZB/nl.fokkezb.loading/tree/master) widget.

* Source code: [https://github.com/FokkeZB/nl.fokkezb.loading/tree/master](https://github.com/FokkeZB/nl.fokkezb.loading/tree/master)
* Test app: [https://github.com/FokkeZB/nl.fokkezb.loading/tree/test](https://github.com/FokkeZB/nl.fokkezb.loading/tree/test)

## Preparing [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

The repo has a `Gruntfile.js` for [Grunt](http://gruntjs.com/getting-started) to replace the app's `app/widgets/nl.fokkezb.loading` with a copy from the `master` branch. The configuration assumes to find this branch at `../master`.

Install Grunt and the dependencies via:

	$ sudo npm i -g grunt
	$ sudo npm install

## Running
To replace the app's copy of the widget and build the app for the simulator simply execute:

	$ grunt
	
There are also tasks to build for Android (`grunt android`) or to just update the widget from master (`grunt update`).