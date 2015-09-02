OE Sphinx Theme
================

This is a custom `Sphinx <http://sphinx.pocoo.org/>`_ theme.


Installing
----------

There are no current releases of this theme but you can install directly from Github::

    pip install git+git://github.com/OnroerendErfgoed/oe-sphinx-theme

Once installed you should change your Sphinx ``conf.py`` to include::

    import oe_sphinx_theme
    html_theme = 'oe_sphinx'
    html_theme_path = [oe_sphinx_theme.get_theme_dir()]