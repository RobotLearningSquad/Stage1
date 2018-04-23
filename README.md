# Stage1

##ROS中使用gstreamer完成语音输入与识别

- 前置条件：启用麦克风 
- 安装语音识别包
    - 安装依赖库：
        - sudo apt-get install gstreamer0.10-pocketsphinx
        - sudo apt-get install ros-indigo-audio-common
        - sudo apt-get install ros-indigo-audio-common
        - sudo apt-get install gstreamer0.10-gconf
    - 安装ROS包
        - sudo apt-get install ros-indigo-pocketsphinx
- 启用gstreamer
    - roslaunch pocketsphinx robocup.launch
    - rostopic echo /recognizer/output
