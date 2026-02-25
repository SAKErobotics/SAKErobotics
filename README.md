
# Updated Feb 2026
https://github.com/SAKErobotics/unitree-dex1-ezgripper-driver

We have developed a DDS based interface that signficantly improves the system level control over the EZGripper.  This new software has a visible 4 state algorithm: static, moving, contacting, grasping which is tuneable and a good place to integrate touch or other sensor input to natively enhance the gripper response.  There is a related configuration file that provides good tuneability of the grippers.  There are 2 DDS interfaces: a generic position and force control and a second interface with rich realtime data from the servo control and servo itself.  

The advanced control and status flows are great for teleop training of VLM, ALM and WM. 

For the Unitree G1, the "generic" interface has a permutation that can directly use the dex1 control in the unitree xr_teleop.  This is the default setup of this repository (hence the name).


# EZGripper Software on Github

EZGripper software for ROS is available at https://github.com/SAKErobotics/EZGripper

EZGripper software independent of ROS is available at https://github.com/SAKErobotics/libezgripper

EZGripper software for C# - C Sharp is available at https://github.com/SAKErobotics/ezgripper-csharp

EZGripper software for Universal Robots is available at https://github.com/SAKErobotics/ezgripper-ur

EZGripper 3D model in .STEP format is available at https://github.com/SAKErobotics/EZGripper3Dmodels
