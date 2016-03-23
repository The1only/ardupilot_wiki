.. _apmcopter-programming-libraries:

===============================
ArduPilot Programming Libraries
===============================

The \ `the libraries <https://github.com/diydrones/ardupilot/tree/master/libraries>`__ are
shared with Copter, Plane and Rover. Below is a high level list of
libraries and their function.

**Core libraries:**

-  `AP_AHRS <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_AHRS>`__ -
   attitude estimation using DCM or EKF
-  `AP_Common <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_InertialNav>`__ -
   core includes required by all sketches and libraries
-  `AP_Math <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_Math>`__ -
   various math functions especially useful for vector manipulation
-  `AC_PID <https://github.com/diydrones/ardupilot/tree/master/libraries/AC_PID>`__ -
   PID controller library
-  `AP_InertialNav <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_InertialNav>`__ -
   inertial navigation library for blending accelerometer inputs with
   gps and baro data
-  `AC_AttitudeControl <https://github.com/diydrones/ardupilot/tree/master/libraries/AC_AttitudeControl>`__
   -
-  `AP_WPNav <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_InertialNav>`__
   - waypoint navigation library
-  `AP_Motors <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_Motors>`__
   - multicopter and traditional helicopter motor mixing
-  `RC_Channel <https://github.com/diydrones/ardupilot/tree/master/libraries/RC_Channel>`__ -
   a library to more convert pwm input/output from APM_RC into internal
   units such as angles
-  `AP_HAL <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_HAL>`__,
   `AP_HAL_AVR <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_HAL_AVR>`__,
   `AP_HAL_PX4 <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_HAL_PX4>`__
   - libraries to implement the "Hardware abstraction layer" which
   presents an identical interface to the high level code so that it can
   more easily be ported to different boards.

**Sensor libraries:**

-  `AP_InertialSensor <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_InertialSensor>`__ -
   reads gyro and accelerometer data, perform calibration and provides
   data in standard units (deg/s, m/s) to main code and other libraries
-  `AP_RangeFinder <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_RangeFinder>`__ -
   sonar and ir distance sensor interfaced library
-  `AP_Baro <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_Baro>`__ -
   barometer interface library
-  `AP_GPS <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_GPS>`__ -
   gps interface library
-  `AP_Compass <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_Compass>`__ -
   3-axis compass interface library
-  `AP_OpticalFlow <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_OpticalFlow>`__ -
   optical flow sensor interface library

**Other libraries:**

-  `AP_Mount <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_Mount>`__, \ `AP_Camera <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_Camera>`__, \ `AP_Relay <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_Relay>`__ -
   camera mount control library, camera shutter control libraries
-  `AP_Mission <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_Mission>`__
   - stores/retrieves mission commands from eeprom
-  `AP_Buffer <https://github.com/diydrones/ardupilot/tree/master/libraries/AP_Buffer>`__ -
   a simple FIFO buffer for use with inertial navigation