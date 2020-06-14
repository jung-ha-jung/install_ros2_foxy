install_ros2_foxy

ROS2 foxy 설치 (Ubuntu 20.04)

    ROS2 1줄 설치 방법

$ sudo wget https://raw.githubusercontent.com/jung-ha-jung/install_ros2_foxy/master/install_ros2_foxy.sh && chmod 755 ./install_ros2_dashing.sh && ./install_ros2_dashing.sh

    ROS2 수동 설치 방법

    ROS2 설치 : https://index.ros.org/doc/ros2/Installation/Foxy/Linux-Install-Debians/

    빌드를 위한 colcon 사용 : https://index.ros.org/doc/ros2/Tutorials/Colcon-Tutorial/

    turtlesim 설치 : https://index.ros.org/doc/ros2/Tutorials/Turtlesim/Introducing-Turtlesim/

    ROS2 환경 설정 : $ gedit .bashrc 입력한 후 bash 파일의 마지막에 "source /opt/ros/foxy/setup.bash” 추가

    ros2 bag 설치 :

    $ sudo apt install ros-dashing-ros2bag ros-foxy-rosbag2-transport

    $ sudo apt install ros-foxy-rosbag2-storage-default-plugins # ROS1과 데이터 저장방식이 달라서 플러그인을 설치해야 한다.

