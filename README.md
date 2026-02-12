# ros2_ws
~/ros2_ws/
├── src/
│   ├── tutorial_interfaces/     # 自定义消息包 (ament_cmake)
│   │   ├── msg/
│   │   │   └── Num.msg
│   │   ├── CMakeLists.txt
│   │   └── package.xml
│   └── py_calc_nodes/          # Python节点包 (ament_python)
│       ├── py_calc_nodes/
│       │   ├── __init__.py
│       │   ├── publisher.py
│       │   └── subscriber.py
│       ├── setup.py
│       └── package.xml
