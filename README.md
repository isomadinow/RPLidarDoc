# Шаги подкючение RPLidar и Камеры к nano_jets
Вначале инициализацируем ros2 
```no-highlight
source /opt/ros/foxy/setup.bash
```
После инициализации заходим в каталог ros_ws
```no-highlight
cd ros_ws/
```
Делаем инициализацию для текущего файла

```no-highlight
source ./install/setup.bash
```
Как проделали все инициализация, заходим в каталог launch 
```no-highlight
cd rplidar_ros/launch/
```
Запускаем RPLidar

```no-highlight
ros2 launch rplidar_ros view_rplidar_a1_launch.py
```
![image](https://github.com/isomadinow/nano_jets/assets/88080221/165bce28-d89b-44b5-be91-332393011e94)
