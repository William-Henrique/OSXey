OSXey
===============

Repo is being maintained regally again.

A script for OS X to display system information.

!['Screenshot'](https://raw.github.com/Gary00/OSXey/master/screenshot_normal.png)
!['Screenshot'](https://raw.github.com/Gary00/OSXey/master/screenshot_color.png)


Auto Install / Uninstall
------------
Use 'install.sh` to both install and uninstall.


Options
------------
	-c,  --color
		Color Logo

	-red
		Red Text

	-green
		Green Text

	-yellow
		Yellow Text

	-blue
		Blue Text

	-purple
		Purple Text

	-grey
		Grey Text

Recent Changes
--------------

* (Addition) Included 10.10 OSX Version
* (Addition) Added more model fields
* (Feature) IP Address Field
* (Addtion) Options for changing text color
* (Optimization) Removed Escape Characters from ASCII art
* (Optimization) Renamed color variables to all be same length - helps when echoing
* (Optimzation) Aligned ASCII art / text in echo statement
* (Addition) Added model field to display Mac Model ID
* (Features) Display more precise model details (e.g. iMac 27-inch, Late 2012)
* (Features) Smarter install script (create directory if doesn't exist, prompt if already uninstalled)
* (Features) Display Total Hard Drive Space on Disk (currently shows only a percentage)
* (Features) Display Graphics Card Model (system_profiler SPDisplaysDataType)


To-Do List
------------

Bug Fixes / Optimization
* Look into $terminalText bug. Maybe find a better way of displaying colors then current method
* Code cleanup
* Update Screenshots
* Better way of changing text color (use ""-text blue"" or "-text red" rather then "-red" or "-blue")
* Test Units (For growing information such as hardware models and OSX versions)
* Add manual install instructions in manual for those who don't want to use installer

Features
* Look into being able to install via package manager (homebrew / macports)
* Resolution information
* Easy way to change info being displayed (maybe a config file ?)
