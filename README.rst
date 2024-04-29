============
database-shared
============

Quick start
-----------

1. Add "polls" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...,
        "database",
    ]

2. Run ``python manage.py migrate`` to create the models.

3. Start the development server and visit the admin to create a poll.