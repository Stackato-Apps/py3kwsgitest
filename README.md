# Python 3 WSGI Sample

This simple web app is implemented in Python 3 using bottle,
multipart, jinja2, and sqlalchemy. Its purpose is to test and
demonstrate a current solution for WSGI on Python 3.

Forked from https://github.com/wobsta/py3kwsgitest with additional
config added for HPE Helion Stackato.

## Deploy to HPE Helion Stackato

    $ cd py3kwsgitest.git
    $ stackato push -n

To open the app in a browser:

    $ stackato open

