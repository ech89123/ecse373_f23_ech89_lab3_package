# ecse373_f23_ech89_lab3_package

This ROS package has the dependancy of package `https://github.com/ech89123/ecse373_f23_ech89_lab3_package`.

This package is ran using `roslaunch <lab3_package_name> lab3.launch`.

`lab3.launch` has the following parameters:
<br>
&emsp;`use_sim_time` default set to `false`
<br>
<br>
&emsp;`use_xacro` default set to `true`
<br>
<br>
&emsp;`use_gui` default set to `true`
<br>
<br>
&emsp;`old_config` default set to `false`
<br>

If `use_sim_time` is set to `true`, then you will also need to run:
<br>
`rosbag play --clock <full_path_to_bag_file> /tf_trajectory:=/tf`
