Video Server
====================================

This demo illustrates establishing peer connections with multiple
browsers and broadcasting to them the server's camera feed.

Running
-------

First install the required packages:

.. code-block:: console

    $ pip3 install aiohttp aiortc opencv-python

When you start the demo, it will create an HTTP server which you
can connect to from your browser:

.. code-block:: console

    $ python3 server.py

You can then browse to the following page with your browser:

http://127.0.0.1:8080 or http://<server'sIP>:8080

Once you click `Start` the browser will receive the video from the server's camera.
