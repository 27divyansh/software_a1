# Assignment 1
###Q1)

* created a world file demo_bot.world using the gazebo application. 

* made a custom model named scarecrow using the model editor and added it to this world.

* also added a custom physics solver profile named ode_70iters in addition to the defult profile in my world file.Tried adjusting the various parameters in this profile and also tried launching this world using the new custom profile through the terminal:

gz physics -o ode_70iters (while the default profile is allready running.
OR
gazebo demo_bot.world -o ode_70iters

* wrote a launch file for this world.

* the codework is present in the src folder where i have created two packages.

the screenshots are:
![screenshot](/divyansh.png)




###Q2)

* spent a lot of time on this urdf part. i made a urdf file named demo-bot.urdf present in ( src/demo_bot_description/urdf ) but dont kow why it did not work even after i tried adjusting so many of its parameters. i even refered other working urdf files but could not find out the problem with my urdf file (it did not appear in the gazebo interface even after adding its path in the GAZEBO_MODEL_PATH variable.

* finally i used a similar working urdf file (not written by me) for the robot.

* learnt about the plugin required for our simple differential drive robot and added this plugin through the urdf file of my robot.

* altered the world file to include my robot model in it and tried to launch it with the same launch file but the gazebo applicatio frozed everytime i executed this roslaunch command. tried many things to fix it but wasnt successful.

* therefore could launch the world file only without my robot.


