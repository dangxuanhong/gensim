:orphan:

.. _about:

============
About
============

History
--------

Gensim started off as a collection of various Python scripts for the Czech Digital Mathematics Library `dml.cz <http://dml.cz/>`_ in 2008,
where it served to generate a short list of the most similar articles to a given article (**gensim = "generate similar"**).
I also wanted to try these fancy "Latent Semantic Methods", but the libraries that
realized the necessary computation were `not much fun to work with <http://soi.stanford.edu/~rmunk/PROPACK/>`_.

Naturally, I set out to reinvent the wheel. Our `2010 LREC publication <http://radimrehurek.com/gensim/lrec2010_final.pdf>`_
describes the initial design decisions behind Gensim (clarity, efficiency and scalability)
and is fairly representative of how Gensim works even today.

Later versions of Gensim improved this efficiency and scalability tremendously. In fact,
I made algorithmic scalability of distributional semantics the topic of my `PhD thesis <http://radimrehurek.com/phd_rehurek.pdf>`_.

By now, Gensim is---to my knowledge---the most robust, efficient and hassle-free piece
of software to realize unsupervised semantic modelling from plain text. It stands
in contrast to brittle homework-assignment-implementations that do not scale on one hand,
and robust java-esque projects that take forever just to run "hello world".

In 2011, I started using `Github <https://github.com/piskvorky/gensim>`_ for source code hosting
and the Gensim website moved to its present domain. In 2013, Gensim got its current logo and website design. In 2018, we reworked the documentation style and started using the `ReadTheDocs theme <https://sphinx-rtd-theme.readthedocs.io/en/latest/>`_.


Licensing
----------

Gensim is licensed under the OSI-approved `GNU LGPLv2.1 license <http://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>`_.

This means that it's free for both personal and commercial use, but if you make any
modification to Gensim that you distribute to other people, you have to disclose
the source code of these modifications.

Apart from that, you are free to redistribute Gensim in any way you like, though you're
not allowed to modify its license (doh!).

My intent here is to **get more help and community involvement** with the development of Gensim.
The legalese is therefore less important to me than your input and contributions.
`Contact me <mailto:me@radimrehurek.com>`_ if LGPL doesn't fit your bill but you'd like the LGPL restrictions liften.

.. seealso::

    We built a high performance server for NLP, document analysis, indexing, search and clustering: scaletext.ai.
    ScaleText is a commercial product, available both on-prem or via SaaS.
    Reach out at info@scaletext.com if you need an industry-grade tool with professional support.

Contributors
--------------

Credit goes to all the people who contributed to gensim, be it in `discussions <http://groups.google.com/group/gensim>`_,
ideas, `code contributions <https://github.com/piskvorky/gensim/pulls>`_ or `bug reports <https://github.com/piskvorky/gensim/issues>`_.

It's really useful and motivating to get feedback, in any shape or form, so big thanks to you all!

Some honorable mentions are included in the `CHANGELOG.txt <https://github.com/piskvorky/gensim/blob/develop/CHANGELOG.md>`_.
