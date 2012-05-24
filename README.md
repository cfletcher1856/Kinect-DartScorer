Kinect-DartScorer
=================

Installation
------------
1. You need to have installed: IPython, Matplotlib, OpenCV 2.1, PyOpengl, wxPython
2. Build the latest version of libfreenect.
  https://github.com/openkinect/libfreenect
		
3. Build and install the python wrappers for libfreenect
		cd libfreenect/wrappers/python
		python setup.py install

4. Download the latest version of this project
		git clone https://github.com/amiller/libfreenect-goodies.git
		cd pykinect
		
5. Test that python can find libfreenect by running:
		python demo_freenect.py