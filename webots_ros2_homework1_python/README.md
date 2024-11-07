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

### Controller

To use your controller copy your controller into this file:
<pre>
webots_ros2_homework1_python/webots_ros2_homework1_python/webots_ros2_homework1_python.py
</pre>

Then to run, in a new terminal, type:
<pre>
source /opt/ros/humble/setup.bash
cd Outdoor_Environment
source install/setup.bash
ros2 run webots_ros2_homework1_python webots_ros2_homework1_python
</pre>

### To Edit "Time of Day"

Simply edit the intensity of each pointlight to make it dimmer and essentially change the time of the day.
