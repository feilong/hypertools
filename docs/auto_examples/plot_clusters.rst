

.. _sphx_glr_auto_examples_plot_clusters.py:


=============================
Discovering clusters
=============================

The `n_clusters` kwarg can be used to discover clusters in your dataset.  It
relies on scikit-learn's implementation of k-mean clustering to find clusters,
and then labels the points accordingly. You must set the number of clusters
yourself.




.. image:: /auto_examples/images/sphx_glr_plot_clusters_001.png
    :align: center





.. code-block:: python


    # Code source: Andrew Heusser
    # License: MIT

    # import
    import hypertools as hyp

    # load example data
    geo = hyp.load('mushrooms')

    # plot
    geo.plot(n_clusters=10)

**Total running time of the script:** ( 0 minutes  0.336 seconds)



.. only :: html

 .. container:: sphx-glr-footer


  .. container:: sphx-glr-download

     :download:`Download Python source code: plot_clusters.py <plot_clusters.py>`



  .. container:: sphx-glr-download

     :download:`Download Jupyter notebook: plot_clusters.ipynb <plot_clusters.ipynb>`


.. only:: html

 .. rst-class:: sphx-glr-signature

    `Gallery generated by Sphinx-Gallery <https://sphinx-gallery.readthedocs.io>`_
