==================
 LearningProgress
==================

.. image:: https://img.shields.io/travis/LearningProgress/LearningProgress.svg?
   :target: https://travis-ci.org/LearningProgress/LearningProgress

.. image:: https://img.shields.io/coveralls/LearningProgress/LearningProgress.svg?
   :target: https://coveralls.io/r/LearningProgress/LearningProgress

.. image:: https://img.shields.io/badge/license-MIT-blue.svg?
   :target: http://opensource.org/licenses/MIT

LearningProgress is a small server application based on Django for tracking
individual learning progress on a structured curriculum. It is still under
development.


Run development version
=======================

::

    $ python3 --version  # This should return Python 3.x
    $ git clone https://github.com/LearningProgress/LearningProgress.git
    $ cd LearningProgress
    $ virtualenv .virtualenv --python=python3
    $ source .virtualenv/bin/activate
    $ pip install -r requirements.txt
    $ python manage.py syncdb  # Prompts for input some superuser data.
    $ python manage.py loaddata extras/example-data-de.json
    $ python manage.py runserver


Requirements
============

LearningProgress uses

* `Python <https://www.python.org/>`_ 3.x
* `Django <https://www.djangoproject.com/>`_ 1.6.x
* `django-mptt <https://github.com/django-mptt/django-mptt/>`_ 0.6.0
* `Constance <https://github.com/comoga/django-constance/>`_ 0.6
* `django-picklefield <https://github.com/gintas/django-picklefield>`_ 0.3.1
* `Six <http://pythonhosted.org/six/>`_ 1.6.1
* `django-bootstrap3 <https://github.com/dyve/django-bootstrap3/>`_ 3.2.x
* `Bootstrap <http://getbootstrap.com/>`_ 3.1.1
* `jQuery <https://jquery.com/>`_ 1.11.0
* `jQuery Form Plugin <http://malsup.com/jquery/form/>`_ v20140218
* `CKEditor <http://ckeditor.com/>`_ 4.3.4


License
=======

LearningProgress is Free/Libre Open Source Software and distributed under
the MIT License, see LICENSE file. The authors are mentioned in the AUTHORS
file.
