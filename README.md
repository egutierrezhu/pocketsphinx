# TIAGo Robot with ROS Kinetic and Pocketsphinx

To avoid false voice commands and noise interference, it is proposed to use a keyword "tiago". First, TIAGo robot waits for the keyword. Then he waits for the voice command. If the voice command is right, the mobile base is running through that command. The following voice commands have been used:

* backward  : {"backward", "go backward", "move backward", "back", "move back"}
* forward   : {"forward", "go forward", "move forward"}
* turn left : {"turn left", "left"}
* turn right: {"turn right", "right"}
* stop      : {"stop", "halt"}
* faster    : {"faster"}
* slower    : {"slower"}
* quater    : {"quarter speed", "quarter"}
* half      : {"half speed", "half"}
* full      : {"full speed", "full"}

Thanks to Michael Ferguson (https://github.cquaikeferguson/pocketsphinx), we can implement voice comnands for robot with ROS using the pocketsphinx package. After that, in (https://github.com/sunmaxwll/pocketsphinx) the author proposes voice commands for ROS Kinetic. Finally, more details can be found in Goebel (2015).

## References
Goebel, R. P. (2015). ROS by example. Lulu. com.
