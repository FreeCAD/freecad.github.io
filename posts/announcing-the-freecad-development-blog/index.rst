.. title: Announcing the FreeCAD Development Blog
.. author: Kurt Kremitzki
.. slug: announcing-the-freecad-development-blog
.. date: 2018-03-04 19:09:59 UTC
.. tags: mathjax
.. category: 
.. link: 
.. description: 
.. type: text

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

Authorship for the blog is possible by `installing Nikola <https://getnikola.com/getting-started.html>`_
and then running::

  $ git clone --recursive https://github.com/freecad/freecad-blog && cd freecad-blog
  $ nikola auto -b # Install any dependencies mentioned in warnings
  $ nikola new_post # Follow the prompts and then edit posts/your_title.rst until satisfied
  $ git add posts/your_title.rst # Begin the pull request process...

... and then finishing by making a pull request with your new post at 
`the repository for the blog source <https://github.com/freecad/freecad-blog>`_. 
Once the pull request is merged, anyone with write permission to the 
`repository for built pages <https://github.com/freecad/freecad.github.io>`_
can then use ``nikola build && nikola deploy`` to build and deploy the new post.
