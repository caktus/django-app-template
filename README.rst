{% if False %}

django-app-template
========================
This is a template for creating a new reusable application for Django.
This uses the template feature added to the ``startapp`` command in Django 1.4. While
creating the app requires using Django 1.4 you can choose to support earlier versions
once it has been created.

To start a new app with this template::

    # Install Django
    pip install django>=1.4
    django-admin.py startapp --template=https://github.com/caktus/django-app-template/zipball/master --extension=py,rst,in <app_name>

{% endif %}

{{ app_name }}
========================

Welcome to the documentation for django-{{ app_name }}!


Documentation
-----------------------------------

Documentation on using django-{{ app_name }} is available on 
`Read The Docs <http://readthedocs.org/docs/django-{{ app_name }}/>`_.


Running the Tests
------------------------------------

You can run the tests with via::

    python setup.py test

or::

    python runtests.py


License
--------------------------------------

django-{{ app_name }} is released under the BSD License. See the 
`LICENSE <https://github.com/caktus/django-{{ app_name }}/blob/master/LICENSE>`_ file for more details.


Contributing
--------------------------------------

If you think you've found a bug or are interested in contributing to this project
check out `django-{{ app_name }} on Github <https://github.com/caktus/django-{{ app_name }}>`_.

Development sponsored by `Caktus Consulting Group, LLC
<http://www.caktusgroup.com/services>`_.
