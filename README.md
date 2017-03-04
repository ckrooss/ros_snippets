## ROS snippets
Support package for the Robot Operating System ([ros.org](http://ros.org))
This package adds a couple of useful snippets and language definitions for roslaunch files (.launch, .test)
and for ros message and service files (.srv, .msg).

The snippets adds complete xml blocks, including the most used parameters.

 Example:

     node<TAB>
expands to

     <node name="name" pkg="package" type="name" output="screen" respawn="true" args="" />

Included snippets are: env, group, launch, node, param, remap, include and test.
## Build System
A new build system is added for .launch files. It just launches roslaunch --screen $file

## Changes
#### 2017-03-04 Syntax highlighting for msg/srv files
New support for message and service files was added by vmlane
#### 2016-07-17 <include> snippets
The missing include tag was added to the roslaunch snippets by gregorgebhardt
