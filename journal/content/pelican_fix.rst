Path Issues With Pelican
########################

:date: 2016-07-02 23:22
:category: pelican
:slug: path-issues-with-pellican
:authors: Tristian Celestin
:summary: Sites to help me get started

I was repeatedly publishing this log using Pelican, but the page would never get styled correctly. Developer tools revealed that the path to ``main.css`` was incorrect.

Turns out I needed to specify the site URL in ``pelicanconf.py``:

.. code-block :: python

    SITEURL = 'https://tristianc.github.io/mt7610u





