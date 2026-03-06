Concepts
=========

Quadrotarium ABC
^^^^^^^^^^^^^^^^^^^^

The quadrotarium_abc is a shared interface between quadrotarium frontend (qps) and quadrotarium backend (qpb). It ensures that the qps and qpb have a common set of commands that can be used regardless of whether user is running a simulation or a real hardware experiments.


Go-to-Points Control
^^^^^^^^^^^^^^^^^^^^^

Consider :math:`N` quadcopters, the go-to-points control takes a set of waypoints :math:`\mathbb{R}^{N\times 3}`, and the quadcopters are tracking the desired waypoints using a geometric controller :footcite:t:`Mellinger11`.



Trajectory Control
^^^^^^^^^^^^^^^^^^^^

Consider :math:`N` quadcopters, the Trajectory Control takes a  ``Trajectory``, which is consisted of many ``Poly4D`` polynomials. Since the quadcopter is differentially flat, and it's assumed that the trajectory will be a min-snap trajectory, then the trajectory is tracked using a geometric controller :footcite:t:`Mellinger11` (by producing control :math:`u`).


Velocity Control
^^^^^^^^^^^^^^^^^^

.. todo:: 
    
    Description of velocity control

Direct Dynamics Control
^^^^^^^^^^^^^^^^^^^^^^^^

A quadcoptor's dynamics can be modeled by the Euler-Lagrange Equations in terms of desired force :math:`F_d\in\mathbb{R}` and :math:`M_d\in\mathbb{R}^3` (i.e. :math:`u^T=[F_d\quad M_d]`). For more mature researchers, we can allow them to directly control :math:`u` (without going over to min-snap)


Barrier Certificates
^^^^^^^^^^^^^^^^^^^^

.. todo:: 
    
    Description of CBF
