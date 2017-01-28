.. ipython:: python
   :suppress:

   import numpy as np
   np.random.seed(123456)
   from numpy.random import randn
   import pandas as pd
   import pandas.util.testing as tm
   np.set_printoptions(precision=4, suppress=True)
   pd.options.display.max_rows = 15

H1: document title
##################

Introduction text.

Sample H2
*********

Sample content.

Another H2
**********

Sample H3
=========

Sample H4
---------

Sample H5
^^^^^^^^^

Sample H6
"""""""""

.. note::

        this is a note

.. versionadded:: version

.. versionchanged:: version

.. seealso::

        see also

This is a statement.

.. warning::

   Never, ever, use this code!

.. versionadded:: 0.0.1

It's okay to use this code.

Here is something I want to talk about::

    def my_fn(foo, bar=True):
        """A really useful function.

        Returns None
        """

.. csv-table:: a title
   :header: "name", "firstname", "age"
   :widths: 20, 20, 10

   "Smith", "John", 40
   "Smith", "John, Junior", 20


This is me trying the ipython directive or whatever that is called.

.. ipython:: python

   df = pd.DataFrame(randn(10, 4))
   df.describe()
