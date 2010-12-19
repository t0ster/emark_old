Installation
============

* Install the JDK if it's not on your system already
* Install jruby_ if you don't already have it.
* Install `the Android SDK`_
* Add the sdk's `tools/` directory to your `$PATH`
* Generate an Emulator_ image unless you want to develop using your phone.

::

	git clone git://github.com/t0ster/emark.git
	cd emark
	cp local.properties.default local.properties
	
* Edit your local.properties
* Launch Emulator

::

	jruby -S rake
	jruby -S rake installl
	
* Enjoy! :)


Develop
=======

All ruby scripts are at `assets/scripts`. Entry point is in `assets/scripts/e_mark.rb`


.. _jruby: http://jruby.org/
.. _`the Android SDK`: http://developer.android.com/sdk/index.html
.. _Emulator: http://developer.android.com/guide/developing/tools/emulator.html