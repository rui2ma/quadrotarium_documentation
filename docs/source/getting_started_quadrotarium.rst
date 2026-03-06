Getting Started with Quadrotarium
===================================

Quadrotarium-Python-Simulator (qps)
-------------------------------------

Installation
^^^^^^^^^^^^^

Clone the Quadrotarium-Python-Simulator git repo:

.. code-block:: none

   git clone https://github.gatech.edu/Robotarium/quadrotarium_python_simulator.git

Setup (Windows)
^^^^^^^^^^^^^^^^

#. Using the command prompt, navigate to inside the directory quadrotarium-python-simulator. (You should see the qps folder, setup.py, a requirements text file, and this README)

#. Create a virtual environment with any name (for example quadrotarium_env):

   .. code-block:: none

      python -m venv quadrotarium_env

#. Activate the virtual environment:

   .. code-block:: none

      quadrotarium_env\Scripts\activate

#. Install the required package dependencies:

   .. code-block:: none

      pip install -r requirements_venv.txt

#. Install the control package:

   .. code-block:: none

      pip install control

#. Install the quadrotarium_python_simulator as a package:

   .. code-block:: none

      pip install --use-pep517 -e .

Setup (Linux/ MacOS)
^^^^^^^^^^^^^^^^^^^^^

#. Using the command prompt, navigate to inside the directory quadrotarium-python-simulator. (You should see the qps folder, setup.py, a requirements text file, and this README)

#. Create a virtual environment with any name (for example quadrotarium_env):

   .. code-block:: none

      python -m venv quadrotarium_env

#. Activate the virtual environment:

   .. code-block:: none

      source quadrotarium_env/bin/activate

#. Install the required package dependencies:

   .. code-block:: none

      pip install -r requirements_venv.txt

#. Install the control package:

   .. code-block:: none

      pip install control

#. Install the quadrotarium_python_simulator as a package:

   .. code-block:: none

      pip install --use-pep517 -e .

Try Some Examples
^^^^^^^^^^^^^^^^^^

As a sanity check, run any of the example files under ``qps/examples``:

.. code-block:: none

   python qps\examples\go_to_point\gtp_scatter_lines_variable_colors.py

Quadrotarium-Python-Backend (qpb)
------------------------------------

.. todo:: 
    
   Install & setup instructions for qpb