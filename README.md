# MandelbrotSetExplorer
An advanced Mandelbrot Set explorer in a jupyter notebook using python, numba, bokeh, distributed and datashader.

I came across some very fresh and exciting data science tools lately such as [bokeh](http://bokeh.pydata.org/en/latest/), [datashader](https://github.com/bokeh/datashader), [dask](http://dask.pydata.org/en/latest/) and its [distributed](https://github.com/dask/distributed) backend for scaling out work, and felt very motivated to try these.

I've worked on concepts to increase the execution performance for numerical problems in python using numba in the past and used speeding up the calculation of the [Mandelbrot Set](https://en.wikipedia.org/wiki/Mandelbrot_set) as an example for that.

The obvious result for this constellation was of course implementing a Mandelbrot Set explorer with interactive zoom and scale out capabilities in a jupyter notebook using bokeh, datashader, distributed and numba, which helped me a lot to understand the basics behind these fantastic packages and I am now more then happy to share.

Hope you like it.
