Gyroscope and accelerometer functional. 

Some noise in accelerometer datas which probably came from the environment. (50Hz peaks)
Some noise in Gyroscope datas, easily ignored with software treatment(random peaks up to 250units [~15°/s] ) 

Usable data: ACC_X[], ACC_Y[], ACC_Z[] and gyroX[], gyroY[], gyroZ[] (SRAM _ short acquisition time)
Usable data in continuous mode:  adc_values.adc_raw_x, adc_values.adc_raw_y, adc_values.adc_raw_z, sm_GYRO_struct._X_VALUE, sm_GYRO_struct._Y_VALUE, sm_GYRO_struct._Z_VALUE 

