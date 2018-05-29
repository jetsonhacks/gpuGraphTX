# gpuGraphTX
Simple moving graph of GPU activity for the Jetson TX1 and Jetson TX2. This allows visualization of GPU utilization.

<h1>Work In Progress</h1>

This is a simple moving graph of the GPU activity of a Jetson TX1 or Jetson TX2 Development Kit.

The graph is implemented as an animated Python Matplotlib graph. The app requires Matplotlib.

For Python 2.7, Matplotlib may be installed as follows:

$ sudo apt-get install python-matplotlib

For Python 3, Matplotlib may be installed as follows:

$ sudo apt-get install python3-matplotlib

You can run the app:

$ ./gpuGraph.py

or:

$ python gpuGraph.py

or:

$ python3 gpuGraph.py


