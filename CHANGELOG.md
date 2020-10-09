# Changelog

## 3.4.0
 - Fix GPIO on ports > 0 on NRF SDK. 
 - Fix flash record delete on nRF5 SDK15 marking flash driver as busy after operation has already been executed.
 - Fix NFC data field language header, "da" -> "dt"

## 0.3.3 
 - Fix flash record delete on nRF5 SDK15 not marking flash driver as busy.

## 0.3.2
 - Add Generic Discoverable flag to advertisements. 
 - Do not configure a secondary PHY for 2 MBIT/s advertisement if data fits in primary adv.
 - Add GATT uninit task. 

## 0.3.1
 - Add explicit reserved bits to rd_sensor_data_bitfield_t to be zeroed in initialization.

## 0.3.0
 - Purge flash before flash integration test.
 - Require fixed flash area in nRF5_SDK15 implementation. 
 - Disable SPI MISO pull-up by default.
 - Fix UART read retriggering data received event.
 - Add yield uninit
 - Add helper functions for parsing sensor data.

## 0.2.6
 - Fix ADC task on multiple channel reads.

## 0.2.5
 - Return RD_ERROR_NOT_ENABLED from tasks not enabled.

## 0.2.4
 - Fix missing enable macro
 - Fix queue uninit
 - Add shorthands for accessing data fields in parse functions

## 0.2.3 
 - Add relative ADC, NTC, photodiode support.

## 0.2.2
 - Add PWM support.

## 0.2.1
 - Add I2C, SPI, LIS2DH12, SHTCX support.

## 0.2.0
 - Non-compatible changes to BLE interface and implementation.

## 0.1.6
 - Integration test DC/DC.
 - Integration test timer.
 - Integration test scheduler.
 - Unit test NFC task. Integration test NFC
 - NRF SDK 15: Use SD reset function if SD is enabled in power interface reset.

## 0.1.5
 - Add nrf15_sdk log enable macro to ruuvi_interface_log.h.
 - Fix nRF5 SDK15 watchdog reinitialization assert.
 - Unit test task_flash, integration test ri_flash.
 - Unit test and integration test GPIO.

## 0.1.4
 - Fix button task compilation when button task is not enabled.
 - Remove RTC, Power tasks as they unnecessarily wrap interface.
 - Add watchdog.

## 0.1.3
 - Add unit tests for tasks.
 - Support multiple button initialization.

## 0.1.2
 - Fix some globally visible names not following the refactored scheme.

## 0.1.1
 - Fix some globally visible names not following the refactored scheme.
 - Pass RI_COMMUNICATION_TIMEOUT to application from BLE Scan.

## 0.1.0 
 - Change to 0.x Semver to signal that project is in alpha.

## 3.3.0
 - Add semantic versioning string.

## 3.0.0 ... 3.2.0 
Alpha versions, do not use for anything.