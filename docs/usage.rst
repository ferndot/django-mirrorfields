=====
Usage
=====

To use Django Mirror Fields in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_mirrorfields.apps.DjangoMirrorfieldsConfig',
        ...
    )

Add Django Mirror Fields's URL patterns:

.. code-block:: python

    from django_mirrorfields import urls as django_mirrorfields_urls


    urlpatterns = [
        ...
        url(r'^', include(django_mirrorfields_urls)),
        ...
    ]
