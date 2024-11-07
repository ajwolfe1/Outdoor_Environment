### To Launch World

<pre>
source /opt/ros/humble/setup.bash
</pre>

<pre>
export WEBOTS_HOME=/mnt/c/Program\ Files/Webots
</pre>

<pre>
git clone https://github.com/ajwolfe1/Outdoor_Environment/
</pre>

<pre>
cd Outdoor_Environment
sudo colcon build
</pre>

<pre>
source install/setup.bash
</pre>

<pre>
ros2 launch webots_ros2_homework1_python f23_robotics_1_launch.py
</pre>

### To Edit "Time of Day"

Simply edit the intensity of each pointlight to make it dimmer and essentially change the time of the day.
