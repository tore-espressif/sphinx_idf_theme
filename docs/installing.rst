************
Installation
************

Install the package (or add it to your ``requirements.txt`` file):

.. code:: console

    $ pip install sphinx_idf_theme (???)

In your ``conf.py`` file:

.. code:: python

    import sphinx_idf_theme

    extensions = [
        ...
        'sphinx_idf_theme',
    ]

    html_theme = "sphinx_idf_theme"


.. note::
    Adding this theme as an extension is what enables localization of theme
    strings in your translated output. If these strings are not translated in
    your output, either we lack the localized strings for your locale, or you
    are using an old version of the theme.

Via Git or Download
===================

Symlink or subtree the ``sphinx_idf_theme/sphinx_idf_theme`` repository into your documentation at
``docs/_themes/sphinx_idf_theme`` then add the following two settings to your Sphinx
``conf.py`` file:

.. code:: python

    html_theme = "sphinx_idf_theme"
    html_theme_path = ["_themes", ]
