Installation
============

.. note::
    CasperJS requires `PhantomJS <http://phantomjs.org/>`_ 1.5.0.

Install PhantomJS following its `installation instructions
<http://code.google.com/p/phantomjs/wiki/Installation>`_, and:

-  Ensure to always install the latest available version of PhantomJS,
   and prefer **static builds** over other package installation methods;

-  Ubuntu users, please double check the version of PhantomJS provided by your
   apt repository. Often, only PhantomJS 1.2 is provided.

Once PhantomJS's installed on your machine, you should obtain something
like this::

    $ phantomjs --version
    1.5.0

Now just follow these instructions::

    $ git clone git://github.com/n1k0/casperjs.git
    $ cd casperjs
    $ git checkout tags/0.6.7
    $ ln -sf `pwd`/bin/casperjs /usr/local/bin/casperjs

So now you should get something like this::

    $ casperjs --version
    0.6.7

You are now ready to write your first script!

.. note::
    The casperjs executable is written in
    `Python <http://python.org/>`_, so you can also run it using the python
    command::

        $ python /path/to/casperjs/bin/casperjs
        CasperJS version 0.6.7 at /Users/niko/casperjs
        Usage: casperjs script.(js|coffee) [options...]
        Read the docs http://casperjs.org/

    If for some reason you don't have access to Python, please check
    this FAQ entry.
