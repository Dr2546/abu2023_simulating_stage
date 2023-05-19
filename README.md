# ABU2023_Simulating_Stage

This is Robocon2023 ABU Stage simulating in Gazebo with a 4 mecanum wheel robot.

# How to build package

1.Create your workspace with a ```src``` sub-directory.

2.Inside a ```src``` ,clone this git with ```git clone https://github.com/Dr2546/ABU2023_Simulating_Stage.git```.

3.In the root of your workspace,run ```rosdep install -i --from-path src --rosdistro foxy -y``` to check dependencies.
> Note:Ros distro may vary depends on you,this project use Ros2 foxy.

4.Run ```colcon build``` or ```colcon build ABU2023_Simulating_Stage``` if your workspace has many packages and you only want to build this package.

# How to use/run package

1.Open up your workspace in terminal.

2.Run ```. install/setup.bash```

3.Run ```ros2 launch ABU2023_Simulating_Stage launch_sim.launch.py```
