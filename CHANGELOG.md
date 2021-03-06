# Change log for fortune

Version 1.1.0 (7 March, 2019)

- Now _requires_ Python 3.
- Got rid of the need for a binary index. It's not all that slow just to read
  the whole file, parse it, and find a random fortune.

Version 1.0 (14 March, 2011)

- Removed setup.py dependency on ez_setup.
- Graduated to 1.0; it's been stable long enough now.
- Changed to refer to 'grizzled-python', instead of 'grizzled'

Version 0.5.2 (11 January, 2011)

- Minor change to setup.py to handle import failure

Version 0.5.1 (28 March, 2010)

- Changed URL to new GitHub page.

Version 0.5 (22 March, 2010)

- Embedded epydoc documentation now uses reStructuredText.
- Got rid of camel case.
- Updated to new version of ez_setup.py
- Added --version option.
- Now uses random.SystemRandom, if it's available.

Version 0.4 (21 May, 2008)

- Fortune cookie file is now opened in universal newline mode.

Version 0.3 (20 May, 2008)

- Updated to correspond to changes in the dependent Grizzled API.

Version 0.2 (28 April, 2008)

- Fixed off-by-one error in calculation of random fortune index when
  retrieving a fortune.
- Fixed bug leading to an empty fortune if fortune cookie file contains
  "%%" at the top of the file.

Version 0.1 (16 April, 2008)

- Initial version posted to the web.
