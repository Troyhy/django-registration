django-registration
===================
clone of https://bitbucket.org/chuck211991/django-registration

Why clone this app?
===================
Registration program is very good as it is, but when ading it to a new proect it's always missing templates. So my motivation was to clone project and add defautl templates that will make project easy to setup.

User quide
==========
You shoud look this documentation from original author. It's in  https://django-registration.readthedocs.org or generate one for yourself from docs directory

Templates
=========
Templates are ment to be overriden in your site template directory. You should loog aplication directory, under templates and copy them uder your own application.

All templates inherits from registration_base.html. It's easy to configure all templates to render content under right block-tag by using this base template.

