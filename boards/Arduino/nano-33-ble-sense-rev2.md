# Arduino Nano 33 BLE Sense Rev2

Product page: https://store-usa.arduino.cc/products/nano-33-ble-sense-rev2

Arm IP:
- [Cortex-M4](/ip/cortex-m.md#cortex-m4f)

Use Cases:
- [AI/ML](/use-cases/ai-ml.md#embedded)
- [IoT](/use-cases/iot.md)

## Specifications

- Cortex-M4F @ 64 MHz ([Nordic nRF52840 datasheet](https://content.arduino.cc/assets/Nano_BLE_MCU-nRF52840_PS_v1.1.pdf))
- 256kb on-chip SRAM, 1mb flash
- 14 GPIO pins
- PWM on all GPIO pins
- Peripherals
  - UART (x1)
  - SPI (x1)
  - I2C (x1)
  - Analog In (x8, ADC 12 bit 200 k samples)
  - Analog Out (only through PWM)
  - External Interrupts on all GPIO pins
  - USB Native in the nRF52840 Processor
  - Sensors
    - IMU
      - BMI270 (datasheet https://content.arduino.cc/assets/bmi270-ds000.pdf)
      - BMM150 (datasheet https://content.arduino.cc/assets/bmm150-ds001.pdf)
    - User LED on pin 13    
    - Gesture, light, proximity, color APDS9960 (datasheet https://content.arduino.cc/assets/Nano_BLE_Sense_av02-4191en_ds_apds-9960.pdf)
    - Microphone MP34DT06JTR (datasheet https://content.arduino.cc/assets/MP34DT06J.pdf)
    - Barometric pressure LPS22HB (datasheet https://content.arduino.cc/assets/Nano_BLE_Sense_lps22hb.pdf)
    - Temperature, humidity HS3003 (datasheet https://content.arduino.cc/assets/HS300x.pdf)
