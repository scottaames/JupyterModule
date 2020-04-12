Usage
=====

CartoCosmos is an interactive planetary map viewer, it is based on `ipywidgets <https://github.com/jupyter-widgets/ipywidgets/>`_ and 
`ipyleaflet <https://github.com/jupyter-widgets/ipyleaflet/>`_. Using these two librarys you can create maps of almost every target 
USGS has researched.
For example, you can create a map of Mars and interact with it:

.. jupyter-execute::

    import CartoCosmos as l
    map = l.planetary_maps('mars')
    map.display_map()



