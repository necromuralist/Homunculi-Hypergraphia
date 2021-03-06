Serial
======

The Serial function is part of the ``inputs`` module. You use it to combine other data functions. It passes the outputs from each layer to the next one in the series. It's a `closure <https://en.wikipedia.org/wiki/Closure_(computer_programming)>`_ that runs all the functions passed to it through ``trax.fastmath.numpy.tree_flatten``.

``Serial`` Docstring
--------------------

.. autofunction:: trax.data.Serial

``tree_flatten``
----------------

``tree_flatten`` is a recursive function that converts a tree into a flat list.

.. autofunction:: trax.fastmath.numpy.tree_flatten
