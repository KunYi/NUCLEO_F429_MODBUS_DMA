# NUCLEO_F429_MODBUS_DMA
the repository for verify MODBUS-LIB on NUCLEO-F429ZI

the source base on https://github.com/alejoseb/Modbus-STM32-HAL-FreeRTOS/tree/master/Examples/ModbusF429DMA

want easy and quick to verify Modbus library on NUCLEO-F429ZI

so use SWO for debugging message output (printf redirection)

the code setting USART3 and USART2 for Modbus operations
* Modbus Slave on USART3
* Modbus Master on USART2

and USART3 connection to ST-Link Virtual COM port, let we can verify with a PC Host
