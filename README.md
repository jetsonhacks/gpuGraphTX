# gpuGraphTX
A very simple moving graph of GPU activity for the NVIDIA Jetson TX1 and Jetson TX2. This allows visualization of GPU utilization.

![GPU Activity Window](https://github.com/jetsonhacks/gpuGraphTX/blob/master/gpuGraph.png)

The graph is implemented as an animated Python Matplotlib graph. The app requires the Python Matplotlib library.

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


