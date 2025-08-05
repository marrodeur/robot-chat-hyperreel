# robot-chat-hyperreel
Projet de robot chat hyper réaliste — mécatronique, IA, impression 3D par Marrodeur
robot-chat-hyperreel/
├── ArduinoFirmware/
│   ├── src/
│   │   ├── sensors/
│   │   │   └── IMU.cpp
│   │   │   └── IMU.h
│   │   ├── actuators/
│   │   │   └── ServoControl.cpp
│   │   │   └── ServoControl.h
│   │   ├── communication/
│   │   │   └── UARTComm.cpp
│   │   │   └── UARTComm.h
│   │   ├── energy/
│   │   │   └── PowerMgmt.cpp
│   │   │   └── PowerMgmt.h
│   │   ├── utils/
│   │   │   └── Filters.cpp
│   │   │   └── Filters.h
│   │   └── main.ino
│   └── README.md
├── OdroidSoftware/
│   ├── vision/
│   │   └── cat_detector.py
│   ├── ia/
│   │   └── speech_recognition.py
│   ├── interface/
│   │   └── web_admin.py
│   ├── navigation/
│   │   └── docking.py
│   ├── audio/
│   │   └── audio_manager.py
│   ├── utils/
│   │   └── logger.py
│   └── main.py
│   └── README.md
├── 3DModels/
│   ├── BlenderFiles/
│   │   └── robot_chat_squelette.blend
│   ├── STL/
│   │   └── patte.stl
│   │   └── torse.stl
│   │   └── tete.stl
│   └── Docs/
│       └── modelling_instructions.md
├── Electronics/
│   ├── schematics/
│   │   └── alimentation_shema.pdf
│   ├── pcb/
│   │   └── robot_board.GBR
│   ├── datasheets/
│   │   └── servo_datasheet.pdf
│   │   └── imu_datasheet.pdf
│   └── README.md
├── Docs/
│   ├── ProjectPlan.md
│   ├── MaterialSelection.md
│   ├── EnergyManagement.md
│   ├── DebugGuides.md
│   └── README.md
├── .gitignore
├── LICENSE
└── README.md
