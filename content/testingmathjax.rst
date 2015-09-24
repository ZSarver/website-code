Testing MathJax
###############

:date: 2015-9-23 20:24
:modified: 2015-9-23 20:24
:tags: math, latex
:category: blog
:slug: testing-mathjax
:authors: Zachary Sarver
:summary: Testing!

 .. role:: raw-latex(raw)
    :format: latex html

 .. These define a role (that double quote thing) for inline latex

In this post I'd like to test MathJax rendering, and its inclusion in the
ReStructured Text files used by Pelican (the static site generator powering this
site.) So here's some inline math: :raw-latex:`\( (p^\alpha q^\alpha)^{1/\alpha}
\prec_G (p^\beta q^\beta)^{1/\beta} \)` And here's some display style math:

.. raw:: latex html

   \[ J_\lambda = 
     \begin{pmatrix}
       \lambda & 1 \\
       & \ddots & \ddots \\
       & & \lambda & 1 \\
       & & & \lambda
     \end{pmatrix}
   \]

And there we have it! A special shoutout to the following webpages that helped me piece this all together:

* The official Pelican documentation, specifically `this
  page <http://docs.getpelican.com/en/3.6.3/content.html>`_.
* The official MathJax documentation, specifically `this
  part <http://docs.mathjax.org/en/latest/start.html>`_.
* This `ReStructured Text quick
  reference <http://docutils.sourceforge.net/docs/user/rst/quickref.html#external-hyperlink-targets>`_
* And this quick how-to for getting `MathJax to play nice with
  ReST <http://forrestyu.net/art/math-in-restructuredtext/#use-mathjax-in-restructuredtext>`_
