������ROS
$ roscore

1. ����gmapping���ܰ�����SLAM
��1���������滷����gmapping�ڵ�
   $ roslaunch mycar_gazebo laser_nav_gazebo.launch 
   $ roslaunch mycar_navigation gmapping_demo.launch 
 (2) �ü��̿���С���ƶ�
   $ roslaunch mrobot_teleop mrobot_teleop.launch
    
    i     ǰ��
    u,o   ��/��ת
    k     ͣ
    j,l   ԭ����/��ת
    <     ����
    m,>   ����/��ת

2. ����hector���ܰ�����SLAM
 ��1���������滷����hector�ڵ�
    $ roslaunch mycar_gazebo laser_nav_gazebo.launch
    $ roslaunch mycar_navigation hector_demo.launch
  (2) �ü��̿���С���ƶ�
    $ roslaunch mrobot_teleop mrobot_teleop.launch

3. ����̽������������ʾ
  (1) �������滷������ع��ܰ�
    $ roslaunch mycar_gazebo laser_nav_gazebo.launch
    $ roslaunch mycar_navigation exploring_slam_demo.launch
  (2) ��������̽��Python�ű�
    $ rosrun mycar_navigation exploring_slam.py


