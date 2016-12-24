
$ easy_install docutils

$ pip install docutils

.. Line with two dotes are special commands. But if no command can be found, the line is considered as a comment

=========================================================
Main titles are written using equals signs over and under
=========================================================

Note that theire must be as many equals signs as title characters.

Title are underlined with equals signs too
==========================================

Subtitles with dashes
---------------------

And sub-subtitles with tilde
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can  put text in *italic* or in **bold**, you can "mark" text as code with double backquote ``: ``print()``.

Lists are as simple as markdown:

- First item
- Second item
    - Sub item

or

* First item
* Second item
    * Sub item

Tables are really easy to write:

=========== ========
Country     Capital
=========== ========
France      Paris
Japan       Tokyo
=========== ========

More complexe tabless can be done easily (merged columns and/or rows) but I suggest you to read the complete doc for this :)

Their is multiple ways to make links:

- By adding an underscore after a word : Github_ and by adding the target after the text (this have the advantage to not insert un-necessary URL inside the readed text).
- By typing a full comprehensible URL : https://github.com/ (will be automatically converted in link)
- By making a more "markdown" link: `Github <https://github.com/>`_ .

.. _Github https://github.com/


$ rst2html myfile.rst output.html

