Changes
=======

0.8 (2013-02-21)
----------------

Enhancements:

- Use `itsdangerous <http://pythonhosted.org/itsdangerous/>`_ to sign SQL queries
- Expose the jQuery object as ``fldt.$`` so extensions can use the toolbar's
  copy of jQuery (#42)

Fixes:

- Don't intercept redirects on XHR requests (#41)
- Fix SQL query time display as milliseconds (#36)
- Fix ``functools.partial`` error (#35)
- Fix werkzeug request logging with logging panel (#33)
- Fix SQL panel unicode encoding error (#31)


0.7.1 (2012-05-18)
------------------

Fixes:

- loading template editor in-place over current page


0.7 (2012-05-18)
----------------

Enhancements:

- Add an in-browser template editor to the template panel
- ``DEBUG_TB_PROFILER_ENABLED`` config option to enable the profiler on all
  requests (normally it is user-enabled by clicking the checkmark)


0.6.3.1 (2012-04-16)
--------------------

New release to add missing changelog for 0.6.3


0.6.3 (2012-04-16)
------------------
Fixes:

- Compatibility with Flask-SQLAlchemy 0.16 package name


0.6.2 (2012-02-18)
------------------

Fixes:

- Installation issue on Windows with trailing slashes in MANIFEST.in

- JavaScript error when using conditional comments for ``<html>`` tag
  (like in HTML5 Boilerplate)


0.6.1 (2012-02-15)
------------------

Fixes:

- Memory leak when toolbar was enabled

- UnicodeDecodeError when request data contained binary data (e.g. session values)


Enhancements:

- ``DEBUG_TB_ENABLED`` config setting to explicitly enable or disable the toolbar

- ``DEBUG_TB_HOSTS`` config setting to enable toolbar only for specific remote hosts

- New logo for Flask instead of Django

- Monospaced font on table data

Thanks to kennethreitz and joeshaw for their contributions.


0.6 (2012-01-04)
----------------

Flask 0.8 or higher is required

Enhancements:

- Flask 0.8 compatibility

Thanks to mvantellingen
