dslibpy/CHANGELOG.md
====================
CHANGE LOG
----------
##### Darwinian Software Library for Python
Author: [Darwin Molero](http://blog.darwiniansoftware.com/about)

v0.11.1
-------
Removed template tag colored_date as it is specific to a particular application and not as a generic library.

Added documentation for date_tags.shorten_datetime template tag.


v0.11
-----
Added template tag date_tags


v0.10.1.0
---------
Renamed dslibpy.numbers to dslibpy.numlib to avoid collision with python's numbers package.

Fixed a bug in dslibpy.numlib.deccomma that removes the sign when converting negative fractions between -1 and 0.

Added the tests project to build test suites for dslibpy .


v0.10.0.2
---------
Fixed bugs in README.md documentation examples.


v0.10.0.1
---------
Lowered the requirement to Django 1.2

Fixed grammar errors in the documentation.


v0.10.0.0
---------
Packaged dslibpy into a Python redistributable.

Changed dslibpy.numbers.currency 
	to dslibpy.numbers.deccomma

Changed dslibpy.numbers.colored_currency
	to dslibpy.numbers.deccomma_color_html

Changed dslibpy.numbers.colored_percent
	to dslibpy.numbers.percent_color_html

Added documentation for dslibpy.numbers

Added documentation for dslibpy.templatetags 
