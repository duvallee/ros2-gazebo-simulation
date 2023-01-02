# ROS2 URDF 시뮬레이션(simulation) workspace 만들기

ROS2-foxy 버전에서 URDF 시뮬레이션을 위한 작업 공간을 만드는 예 입니다. URDF는 간단한 실린더를 보여줍니다.

본 예제는 우분투(uBuntu 20.04.5) 데스크탑 버전에 ROS2-foxy 버전에서 테스트 되었습니다.

* [ROS2-foxy 설치](https://duvallee.tistory.com/9)

빌드는 다음과 같습니다.

\$ colcon build

\$ source ./install/local_setup.bash

실행은 다음과 같습니다.

\$ ros2 launch manipulator manipulator.launch.py

![screenshot](https://user-images.githubusercontent.com/6201935/210193167-78549a7f-6959-41dd-ab90-45a71fc8bd9c.png)