Henry's sublime-settings
=========================

Henry's variant of https://github.com/oisinmulvihill/sublime-text-3-settings & https://github.com/vaxXxa/sublime-text-3-settings

Installation
------------

Start new ST3 and enter the license.

First install `Sublime Package Control`_ (quickest way is ``cmd+shift+p`` -> 'Install Package Control')

And reopen ``Sublime Text 3``.

You can clone the repository wherever you want (I keep it in ``~/Documents/Projects/sublime-settings``). The bootstrapper script will pull in the latest version and copy the files to your home folder.

.. code:: bash

    $ git clone git@github.com:henry131/sublime-text-3-settings.git sublime-settings


Run
---

To update, ``cd`` into your local ``sublime-settings`` repository and then:

.. code:: bash

    $ make

After that open ``Sublime Text 3`` and wait a few minutes. All packages are downloaded automatically. Then restart ``Sublime Text 3``.


OS X Command Line
-----------------

You may want to create a symlink to subl. Assuming you've placed Sublime Text 3 in the Applications folder, you can run:

.. code:: bash

    $ ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl

Reopen terminal and try:

.. code:: bash

    $ subl --help


.. _`Sublime Package Control`: https://sublime.wbond.net/installation
