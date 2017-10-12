# MOVE CGI - A SMALL interfaceing tool with the robot controller 

http://robot_ip/KAREL/move_cgi?io_op=write&p=x,y,z,w,p,r

http://robot_ip/KAREL/move_cgi?io_op=read                               


## Installation
1. Build the `*.kl` files in the `karel` folder with Roboguide and copy them to the robot `MD:` folder
2. Copy the `*.htm` file from the `examples` folder to the robot `MD:` folder
3. Copy the `webmotion.tp` file from the `tpe` folder to the robot `MD:` folder

## Configuration
Set UNLOCK to HTTP authentication of KAREL: 
1. On the Teach Pendant select `Menu -> Setup -> Host Comm`
2. Set the cursor on `HTTP`
3. Push `F3[DETAIL]`
4. Set the cursor on `A` left side of KAREL. Select `F3[UNLOCK]`
