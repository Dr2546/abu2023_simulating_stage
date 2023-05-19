# ABU2023_Simulating_Stage

This is Robocon2023 ABU Stage simulating in Gazebo with a 4 mecanum wheel robot.

# How to build package

1.Create your workspace with a ```src``` sub-directory.

2.Inside a ```src``` ,clone this git with ```git clone https://github.com/Dr2546/abu2023_simulating_stage.git```.

3.In the root of your workspace,run ```rosdep install -i --from-path src --rosdistro foxy -y``` to check dependencies.
> Note:Ros distro may vary depends on you,this project use Ros2 foxy.

4.Run ```colcon build``` or ```colcon build --packages-select abu2023_simulating_stage``` if your workspace has many packages and you only want to build this package.

# How to use/run package

1.Open up your workspace in terminal.

2.Run ```. install/setup.bash```

3.Run ```ros2 launch abu2023_simulating_stage launch_sim.launch.py```
