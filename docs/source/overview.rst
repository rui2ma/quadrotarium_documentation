Overview
=========

Diagram
^^^^^^^^

.. todo::
    organize qps, qpb, and crazyswarm into a diagram

.. .. image:: /images/overview.png
..     :width: 60%

.. The TRINITY (qps-qpb-crazyswarm)
.. ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. 1.  crazyflies to crazyswarm
.. 2. crazyswarm how does it interact backend
.. 3. how the backend interact with python frontend.
.. 4. how to use crazyswarm directly (bypassing the backend APIs)

Quadrotarium-Python-Simulator (qps)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The Robotarium's quadcopter python simulator (Python 3.8 - 3.13).

The purpose of the Quadrotarium simulator is to ensure that algorithms perform reasonably well before deployment onto the Robotarium's quadcopters (COMING SOON!). The objective is to make scripts created for the simulator directly applicable with the Robotarium's quads. To ensure minimum modification after deployment, the simulator has been created to closely approximate the actual behavior of the real quads.

Regarding user-level control, for safety purposes, the user only gets to specify a desired position for each quadcopter at each timestep, which is tracked using a differential flatness controller as in [1]. Also, a collision avoidance solution based on [2] is provided to the user.


Quadrotarium-Python-Backend (qpb)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: 
    
    Description of qpb

Crazyswarm (external)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: 
    
    Description of crazyswarm
