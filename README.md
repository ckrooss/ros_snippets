# ROS snippets
This package adds a couple of useful snippets and language definitions for roslaunch files (.launch, .test)

The snippets adds complete xml blocks, including the most used parameters.

 Example:
 
     node<TAB>
expands to

     <node name="name" pkg="package" type="name" output="screen" respawn="true" args="" />

Included snippets are: env, group, launch, node, param, remap and test.
# Build System
A new build system is added for .launch files. It just launches roslaunch --screen $file
