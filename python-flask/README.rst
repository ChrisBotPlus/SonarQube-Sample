Flaskr
======

The basic blog app built in the Flask `tutorial`_.

.. _tutorial: https://flask.palletsprojects.com/tutorial/


Install
-------

Create a virtualenv and activate it::

    $ python3 -m venv venv
    $ . venv/bin/activate

Or on Windows cmd::

    $ py -3 -m venv venv
    $ venv\Scripts\activate.bat

Install Flaskr::

    $ pip install -e .



Run Application
----

.. code-block:: text

    $ flask --app flaskr init-db
    $ flask --app flaskr --debug run

Open http://127.0.0.1:5000 in a browser.


Unit Test
----
Install pytest and Run Unit Test
::
    $ pip install pytest
    $ pytest

Install coverage and Run with coverage report
::
    $ pip install coverage
    $ coverage run -m pytest
    $ coverage report
    $ coverage html  # open htmlcov/index.html in a browser
    $ coverage xml   # output coverage.xml
    
    
    
Sonar Scanner
----
Config file: sonar-project.properties

Run Sonar Scanner:
::
    $ sonar-scanner

