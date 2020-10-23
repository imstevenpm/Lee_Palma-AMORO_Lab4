# Lab 4:  Kinematics and Dynamics of a Biglide

## Explanation steps for using the simulation

### Setup

* The following instructions were last tested using Windows 10, MATLAB 2020 and ADAMS 2020 on October 24th, 2020.
* Clone the repository of the project in a desired folder. \href{https://github.com/imstevenpm/Lee_Palma-AMORO_Lab4}{\underline{See repository}}
* Open MATLAB and Simulink and be sure to change the working directory to the folder that has the files cloned.


### Geometric, Kinematic and Dynamic Model

* For testing the Geometric, Kinematic and Dynamic model, run the MATLAB file called "Controls_Plant_1" from the MATLAB command window and open the Simulink file by running "Biglide_Lee_Palma".
* Set the simulation time to the desired value and start the Simulink simulation by pressing the green play button. 
* The results will be generated and they can be seen by double clicking the scopes elements. The graphs shown in the scopes are actually the difference between the values computed by Adams and the ones computed by MATLAB.


### Trajectory Tracking by Kinematic Control

* For testing the Kinematic Control, run the MATLAB file called "Controls_Plant_3" from the MATLAB command window and the open the Simulink file by running "Trajectory_Tracking". 
* Set the parameters of the desired trajectory in the elements on the left side of the scheme and before pressing the green play button, make sure that the simulation time is equal to the final time of the trajectory generator (tf). 
* After running the simulation, the results can be seen in the scopes. In these graphs, the desired trajectory generated and the trajectory followed by the end effector are shown, as well as the error between these. 
* You can now try to change the value of the gain called "lambda" to experiment its effects on the system.

### Trajectory Tracking by Dynamic Control

* For testing the Dynamic Control, run the MATLAB file called "Controls_Plant_5" from the MATLAB command window and the open the Simulink file by running "Torque_Control". 
* Set the parameters of the desired trajectory in the elements on the left side of the scheme and before pressing the green play button, make sure that the simulation time is equal to the final time of the trajectory generator (tf). 
* After running the simulation, the results can be seen in the scopes. In these graphs, the desired trajectory generated and the trajectory followed by the end effector are shown, as well as the error between these.
* You can now try to change the value of the gains called "Kp" and "Kd" by double clicking the "Torque Controller" MATLAB function block and changing their numerical value.

### Singularity Crossing

* To be done

## Authors
* Justin Lee: leej1996@gmail.com
* Steven Palma Morera: imstevenpm.work@gmail.com
