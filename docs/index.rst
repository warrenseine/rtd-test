Kuyruk: A distributed task runner
==================================

Welcome to Kuyruk’s documentation. This documentation covers the usage of the
library and gives information about running workers.

.. image:: minko.png
   :height: 100px
   :width: 200 px
   :scale: 50 %
   :alt: alternate text
   :align: right

About Kuyruk
------------

Kuyruk is a simple and easy way of distributing tasks to run on servers.

It uses `RabbitMQ <http://www.rabbitmq.com>`_ as message broker and depends on
`Pika <http://pika.readthedocs.org/en/latest/>`_
which is a pure-Python RabbitMQ client library.

User's Guide
------------

.. toctree::
   :maxdepth: 1

   features
   gettingstarted
   configuration
   commands
   signals
   events
   classtasks
   extending


API Reference
-------------

.. toctree::
   :maxdepth: 2

   api


Indices and tables
------------------

* :ref:`genindex`
* :ref:`search`
