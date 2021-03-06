bade
####

.. image:: docs/source/_static/bade.png
           :alt: bade
           :width: 400px

Micro-blogging with rST
-----------------------

Bade is a small command line utility to allow the user to maintain a simple
HTML website and weblog using only plaintext rST for their content. It also
bundles an rST directive (see `the docs`_) for rendering DOT graphs as SVG.

It's very similar in spirit to some other things. It's like Pelican_ but it's a
lot simpler and uses Mako_ instead of Jinja2_. It's also like Tinkerer_ but
without the dependency on Sphinx_.

Bade is opinionated and simplistic, I wrote it mostly my own usage, so you
probably shouldn't use it.

.. _`the docs`: http://pythonhosted.org/bade/
.. _Pelican: http://docs.getpelican.com/
.. _Mako: http://www.makotemplates.org/
.. _Jinja2: http://jinja.pocoo.org/docs/
.. _Tinkerer: http://tinkerer.me/
.. _Sphinx: http://sphinx-doc.org/

Plans to extend
===============
In writing Bade, I came up with a few things more I'd like to do:

    - **Test suite**: Everything should be tested, right?
    - **Git integration**: For dirty checking on build, maybe stamping a
      rendered file with its latest commit hash. There are `a few`_ GitHub
      `issues`_ for it.
    - **Hooks**: Let people hook in at interesting points, ie. call ``grunt``
      pre-build, commit after build, etc.

.. _`a few`: https://github.com/bmcorser/bade/issues/5
.. _`issues`: https://github.com/bmcorser/bade/issues/4

Documentation
=============

It's here_, there's a tutorial_.

.. _here: http://pythonhosted.org/bade/
.. _tutorial: http://pythonhosted.org/bade/tutorial.html
