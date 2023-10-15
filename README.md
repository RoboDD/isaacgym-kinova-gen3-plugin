# isaacgym-kinova-gen3-plugin

# Demo

[![Watch the video](https://img.youtube.com/vi/5W43jEBt8k4/maxresdefault.jpg)](https://youtu.be/5W43jEBt8k4)

# Installation

- Download [Isaac Gym](https://developer.nvidia.com/isaac-gym) `IsaacGym_Preview_4_Package.tar.gz` and install it;
- Move `kortex_description` to `isaacgym/assets`;
- Move `kinova_nut_bolt_ik_osc.py` to `isaacgym/python/examples`;
- Run `cd isaacgym/python/examples`, and then `python3 kinova_nut_bolt_ik_osc.py`.

# Known Issue

- The gripper is `panda_hande`, not `robotiq_2f_85`, will be modified later;
- Strange pose with panda_ik

# Source

- URDF file: [Kortex Description](https://github.com/Kinovarobotics/ros_kortex/tree/noetic-devel/kortex_description)
- ros_kortex/kortex_description/arms/gen3/7dof/
