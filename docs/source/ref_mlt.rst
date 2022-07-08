Usando Python
================

TExto para el header

Subtitulo 1
------------

texto del subtitulo 

.. tabbed:: Julia

   .. jupyter-execute:: 

      using Plots
      plot(Plots.fakedata(12))
      # hist(mtcars$mpg)
   
.. tabbed:: Python

   .. ipython:: python

      import numpy as np
      import matplotlib.pyplot as plt 
      x = np.random.uniform(size = 12)
      y = np.random.uniform(size = 12)
      plt.plot(x, y)


.. code-cell:: r
   
   a <- 12

.. highlight:: r

::

    > logsouvenirtimeseries <- log(souvenirtimeseries)
    > plot.ts(logsouvenirtimeseries)