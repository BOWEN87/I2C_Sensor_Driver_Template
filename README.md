# I2C_Sensor_Driver_Template
模擬 NB Camera 中點sensor的過程（初始化、register map、read ID等）  
模擬 I2C driver + sensor init 流程  可加入 register log、流程圖、debug log 解析範例  

i2c_sensor_driver_template/  
├── src/  
│   ├── main.c  
│   ├── i2c_mock.c   # 模擬I2C傳輸  
│   ├── sensor_xyz.c # 模擬某顆sensor  
├── inc/  
│   └── sensor_xyz.h  
├── README.md  
└── doc/  
    └── sensor_init_sequence.md  
