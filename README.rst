cryptop (EUR Version)
=======
cryptop is a lightweight command line based cryptocurrency portfolio.
Built on Python 3 and ncurses with simplicity in mind, cryptop updates in realtime.
This version is just modified to display the EUR price instead of the USD price without having to change the config files.


.. image:: img\cryptop.png

Installation
------------

cryptop requires Python 3 to run, and has only tested in Python 3.6 so far.

The easiest way to install cryptop (EUR Version) is through git

.. code:: bash

    git clone git://github.com/stenhh/cryptop
    
download the repo and run

.. code:: bash

    sudo python setup.py install

setup.py can be run with a --user flag if you would prefer not to sudo. It requires setuptools which is included in most python installs and many distros by default

Usage
-----

Start from a terminal.

.. code:: bash

    cryptop

Follow the on screen instructions to add/remove cryptocurrencies from your portfolio.

Credits
-------

Uses the `cryptocompare.com API
<http://www.cryptocompare.com/>`_.
huwwp on Github for the original

Disclaimer
----------

I am not liable for the accuracy of this program’s output nor actions
performed based upon it.
