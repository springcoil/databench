.. Databench documentation master file, created by
   sphinx-quickstart on Tue Jun 10 23:44:51 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


.. _overview:

Overview
========

Databench is a Python package that you can install using ``pip`` inside a ``virtualenv``:

.. code-block:: bash
	
	$ virtualenv venv
	$ source venv/bin/activate
	(venv)$ pip install git+https://github.com/svenkreiss/databench.git

It provides an executable ``databench`` and the Python module ``databench`` as well as a JavaScript library for the frontend with the same name. Running the executable creates a local web server which you can access at http://localhost:5000. A good way to start is to jump right into :ref:quickstart.

Some features are shown in the `live demos`_. They do not include examples with parallelization or database interfaces (like asynchronously subscribing to a Redis channel) but those examples are available in the `databench_examples`_ repository.

.. image:: images/mpld3pi_demo.png
   :height: 270

.. image:: images/mpld3_heart_path.png
   :height: 270

.. image:: images/bagofcharsd3.png
   :height: 270

The `live demos`_ and `databench_examples`_ also show seemless integration with markdown_ and MathJax_ as well as with `angular.js`_.

.. _`live demos`: http://databench-examples-viewer.svenkreiss.com/
.. _`databench_examples`: https://github.com/svenkreiss/databench_examples
.. _markdown: http://daringfireball.net/projects/markdown/syntax
.. _MathJax: http://www.mathjax.org/
.. _`angular.js`: https://angularjs.org/


Contents
--------

.. toctree::
   :maxdepth: 4

   self
   quickstart
   deploy
   backend_api
   frontend_api
   dev


Feedback
--------

The `GitHub page`_ provides a few ways for feedback in terms of *Issues* and *Pull Requests* and I am happy to receive and incorporate those. Or you can `send me an email`_.

.. _`GitHub page`: https://github.com/svenkreiss/databench
.. _`send me an email`: mailto:me@svenkreiss.com


Contributors
------------

.. include:: ../AUTHORS.rst


License
-------

Databench was written by Sven Kreiss and made available under the 
`MIT license`_.

.. _`MIT license`: https://github.com/svenkreiss/databench/blob/master/LICENSE



.. Indices and tables
.. ==================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`
