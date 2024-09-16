# init_sensor_kit_launch

## Building

```
colcon build --symlink-install --cmake-args -DCMAKE_BUILD_TYPE=Release --packages-up-to <YOUR-VEHICLE-NAME>_sensor_kit_description <YOUR-VEHICLE-NAME>_sensor_kit_launch
```