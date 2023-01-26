# Zuuu ROS2 services


How to install:

```bash
cd ~/ros_ws/src
git clone https://github.com/kraft2k/zuuu_interfaces.git
cd ~/ros_ws/
colcon build --packages-select zuuu_interfaces
```

## Services
* **DistanceToGoal.srv** - Return delta x, delta y, delta theta and distance from the last goal position sent using GoToXYTheta. 
* **GetBatteryVoltage.srv** - Get the mobile base's battery voltage.
* **GetOdometry.srv** - Get the mobile base's odometry.
* **GetZuuuMode.srv** - Get the mobile base's drive mode.
* **GoToXYTheta.srv** - Send GoTo instruction to the mobile base.
* **IsGoToFinished.srv** - Return if the mobile base has reached the goal of its last GoTo sent, modulo tolerances along x, y and theta.
* **ResetOdometry.srv** - Reset the mobile base's odometry.
* **SetFrontsLights.srv** - Turn on / turn off Front Lights of the mobile base.
* **SetSpeed.srv** - Send velocities commands to the mobile base.
* **SetZuuuMode.srv** - Set the mobile base's drive mode.
* **SetZuuuSafety.srv** - Disable / enable the mobile base's anti-collision safety provided by the Lidar.

---
