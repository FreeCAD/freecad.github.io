.. title: Announcing the FreeCAD Development Blog
.. author: Kurt Kremitzki
.. slug: announcing-the-freecad-development-blog
.. date: 2018-03-04 19:09:59 UTC
.. tags: mathjax
.. category: 
.. link: 
.. description: 
.. type: text

.. figure:: /images/EmojiOne.png
   :align: center

   CC-BY-SA: `EmojiOne <https://www.emojione.com/>`_

This is the debut post for the FreeCAD Development Blog, which provides a unique
opportunity to bring the best FreeCAD development news and updates from the
community of developers and users.

The blog uses the Python-based `Nikola <https://getnikola.com/>`_ which provides an
intuitive command-line interface (see ``nikola help`` after installation)
and consumes `reStructuredText <http://www.sphinx-doc.org/en/stable/rest.html>`_ files.

`Custom themes <https://themes.getnikola.com/>`_ are available, and standard CSS/JS
customization is possible as well. Nikola supports :math:`\LaTeX` equation rendering.
It also has good multilingual support, key for FreeCAD's international community.
Nikola also comes with RSS support out of the box, so readers of this site can
subscribe for automatic updates.

You can contribute posts by following a few steps. First, visit the `the repository
for the blog source <https://github.com/freecad/freecad-blog>`_ and click the "Fork" button.
You can read about `installing Nikola <https://getnikola.com/getting-started.html>`_ or (assuming you have pip)
just run ``sudo apt install python3-pip && pip3 install --user -U nikola webassets ws4py watchdog``. Then you need to clone your forked repository
by running::

  $ git clone https://github.com/<your-username>/freecad-blog && cd freecad-blog
  $ nikola auto -b # Run autobuild and open an auto-refreshing browser window
  $ nikola new_post # Follow the prompts and then edit posts/your_title.rst until satisfied
  $ git add posts/your_title.rst # Begin the pull request process...

... and then finishing by making a pull request on the main repository using the commits you've
pushed to your fork.

Once the pull request is merged, anyone with write permission to the 
`repository for built pages <https://github.com/freecad/freecad.github.io>`_
can then use ``nikola build && nikola deploy`` to build and deploy the new post.
