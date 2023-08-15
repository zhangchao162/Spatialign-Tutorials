Installation
==============
The Spatialign package is developed based on the pytorch framework and can be implemented on both CPU and GPU.

We recommend running the package on GPU. Please ensure that pytorch and CUDNN are installed correctly.

To run Spatialign, all dependencies included in the file 'requirement.txt' need to be installed.

We provide two ways to install the package of Spatialign.

Please note that the current Spatialign version offers full support of Linux operating system. Further version for other operating systems would be released soon.


1. Python
----------------
.. code-block:: python

	pip install spatialign

or downloading the package from `GitHub repository <https://github.com/STOmics/Spatialign.git>`_.

.. code-block:: python

    pip install spatialign-0.1.3-py3-none-linux_x86_64.whl

or

.. code-block:: python

    git clone https://github.com/STOmics/Spatialign.git

    cd Spatialign

    python setup.py install


2. Anaconda
---------------
For convenience, we suggest using a separate conda environment for running Spatialign. Please ensure Annaconda3 is installed.

Create conda environment and install Spatialign package.

.. code-block:: python

   # create an environment called Spatialign
   conda create -n Spatialign python=3.8

   # activate your environment
   conda activate Spatialign

   # install package

   pip install spatialign

   or

   git clone https://github.com/STOmics/Spatialign.git

   cd Spatialign

   python setup.py build

   python setup.py install --user

   #To use the environment in jupyter notebook, add python kernel for this environment.

   pip install ipykernel

   python -m ipykernel install --user --name=spatialign
