Cache 1.5.2 Released
====================

We are happy to announce the immediate availability of Doctrine Cache
`1.5.2 <https://github.com/doctrine/cache/releases/tag/v1.5.2>`_.

Cache 1.5.2
~~~~~~~~~~~

This release corrects a few bugs:

Fetching ``false`` values from the cache via ``fetchMultiple` was causing
incorrect misses (`#105 <https://github.com/doctrine/cache/pull/105>`_).

Cache paths were exceeding the windows ``MAX_PATH``
length (`#107 <https://github.com/doctrine/cache/pull/107>`_).

The ``MongoDBCache`` was not failing silently in case of DB-side exceptions
(`#108 <https://github.com/doctrine/cache/pull/108>`_).

You can find the complete changelog for this release in the
`v1.5.2 release notes <https://github.com/doctrine/cache/releases/tag/v1.5.2>`_.

Installation
~~~~~~~~~~~~

You can install the Cache component using the following ``composer.json`` definitions:

.. code-block:: json

  {
      "require": {
          "doctrine/cache": "~1.5.2"
      }
  }

Please report any issues you may have with the update on the mailing list or on
`Jira <http://www.doctrine-project.org/jira>`_.

.. author:: Marco Pivetta <ocramius@gmail.com>
.. categories:: Release
.. tags:: none
.. comments::
