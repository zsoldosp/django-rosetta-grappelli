========================
Django-Rosetta-Grappelli
========================

Compatibility template for rosetta when grappelli is installed

**Note:** As of Jan 2017 a new maintainer took over and a new pip package had to be created for it. The releases
now are Django 1.8+ compatible and go under the name django-rosetta-grappelli2.

See: http://pypi.python.org/pypi/django-rosetta-grappelli2/

The last release of the original author can be found here: http://pypi.python.org/pypi/django-rosetta-grappelli/

All credits should go to **Haineault.com** for creating grappelli-fit

Installation
============

Add rosetta-grappelli **before** `rosetta` in your installed apps:
  ::

    INSTALLED_APPS = (
        'grappelli',
        ...
        'rosetta-grappelli',
        'rosetta',
        ...
    )

That's it


Release Notes
=============

* 1.2 - support current Django versions

  * drops support for Django 1.5, 1.6,  and 1.7
  * adds support for Django 1.8, 1.9, 1.10, 1.11 with all supported python versions

* 1.1 - first release by the new maintainer, supporting Django 1.5+
