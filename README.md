# vector-control-of-ac-drive-using-single-phase-asynchronous-motor
Electric Drive   The function of an electric drives system is the controlled conversion of electrical energy to a mechanical form, and vice versa, via a magnetic field.


Summary
A single phase asynchronous machine rated 1/4 HP, 110 V, 60Hz is fed by a current-controlled PWM inverter which is built using a Universal Bridge block. The speed control loop uses a proportional-integral-derivative regulator to produce the quadrature-axis current reference iq* which controls the motor torque. 
The motor flux is controlled by the direct-axis current reference id*. The block DQ-AB is used to convert id* and iq* into current references ia*, and ib* for the current regulator. Current and Voltage Measurement blocks provide signals for visualization purpose.

Simulation
Observed on the scope the motor currents, voltage, speed, and torque during the starting. Double click on the two Manual Switch blocks to switch from the constant wref=1500 rpm and TL blocks to the Step blocks. (Reference speed wref changed from 1500 to 750 rpm at t = 2 s and load torque changed from 0 to 1 N.m at t= 1s). Restarted the simulation and observed the drive response to successive changes in speed reference and load torque.
