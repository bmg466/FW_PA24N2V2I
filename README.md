# FW_PA24N2V2I
project used USART1, ADC, DAC, I2C;

USART1 for communicate with client (hope to make application on QT for Windows and Linux);
ADC for monitoring thresholds of the preamp, monitoring for source voltage (+2.5V);
DAC for controlling threshold by adjusting the lower threshold;
I2C for monitoring temperature on the PCB (hottest point) and in the gas space via AD7415;

Known issues:
DAC:
still used 8 bit resolution // have to improve to 12 bit;
I2C:
in case a slave device not responded the mcu gets stuck // there are no timers for interrupts waiting the answer;

 Mikhail B. 2016
