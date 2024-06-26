# ur_kinematics

This repository provides a Python implementation for the forward and inverse kinematics of a ur robot. The implementation focus the ur5 robot with a gripper offset and placed 0.1m above the ground (this is the default distance between world and the base_link). It also provides support for a simple ur10 robot. Other models can be implemented by changing the DH params, according to [universal robotics](https://www.universal-robots.com/articles/ur/application-installation/dh-parameters-for-calculations-of-kinematics-and-dynamics/).
For the inverse kinematics, it was followed an approach similar to (https://smartech.gatech.edu/handle/1853/50782)

The module provides example codes for: forward kinematics usage, inverse kinematics usage. The second example file includes a function to choose a joint combination among the inverse kinematics solution. The requirements include all joints to be above the ground and picking up the configuration closest to the current robot configuration
