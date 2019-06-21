git-joke
========

.. image:: https://travis-ci.org/vitakrya/git-joke-cli.svg?branch=master
    :target: https://travis-ci.org/vitakrya/git-joke-cli

.. image:: https://readthedocs.org/projects/git-joke-cli/badge/?version=latest
    :target: https://git-joke-cli.readthedocs.io/en/latest/?badge=latest

Usage
-----

You can use this as an api to fetch joke by using

.. code-block::

    from gitjoke.extractor import get_joke, get_jokes

    # Get all jokes in list
    jokes = get_jokes()

    # Get random joke
    joke = get_joke()

Example from the internal help command::

    $ git-joke -h
    Display random git joke or all git jokes
    Usage:
        git-joke [--all]

    Options:
        -h --help  Show this help message
        -v --version  Show version
        -a --all  Show all jokes

License
-------

MIT
