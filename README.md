# Mine-Safety
Mine Safety
[ Gas Sensor MQ-7/MQ-4 ]  
[ Temp/Humidity Sensor (SHT31) ]  
       │
       │ I2C / ADC
       ▼
  ┌────────────┐       UART/SPI       ┌─────────────┐
  │   STM32F4  │  <---------------->  │   ESP32-S3  │
  │
  └────────────┘                      └─────────────┘
       │
       │ GPIO
       ▼
 [ LED + Buzzer ]
