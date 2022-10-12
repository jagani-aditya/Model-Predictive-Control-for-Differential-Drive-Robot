# Error Tracking Model Predictive Control for Differential Drive Mobile Robots


## Installation

1- Clone the repository in catkin_workspace
```shell
    git clone https://github.com/jagani-aditya/Model-Predictive-Control-for-Differential-Drive-Robot.git
```
2- Perform catkin_make 
```shell
    cd ..
    catkin_make
```

## How To Run

1- Go to your catkin_ws directory
```shell
    cd ~/catkin_ws
    catkin_make
```
2- in the first terminal
```shell
    roslaunch mpc_differential_drive gazebo_mpc.launch
```
3- in the second terminal
```shell
    roslaunch mpc_differential_drive mpc.launch
```

## Results

**Oval Trajectory**

<img src="/Assets/ezgif.com-gif-maker.gif" width="400">    <img src="/Assets/ezgif.com-gif-maker-3.gif" width="400">
<img src="/Assets/ezgif.com-gif-maker-4.gif" width="400">

**Lissajous Trajectory**

![](/Assets/ezgif.com-gif-maker-5.gif)
![](/Assets/ezgif.com-gif-maker-7.gif)
![](/Assets/ezgif.com-gif-maker-6.gif)

