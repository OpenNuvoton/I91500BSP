-------------
I91500 BSP -V1.00.001 2021/06/04
-------------
[Add]
1.   Provide user all hardware drivers.
2.   Provide user the driver samples, includes:
     (1)   BOD: This sample code shows how to configure ¡§Brown-Out detection¡¨.
     (2)   DAC: Demonstrate how to use ¡¥DAC¡¦ to play audio file.
     (3)   FMC: How to load/write APROM or LDROM.
     (4)   GPIO_OutputInput:  Demonstrate  the usage of gpio driver, includes(Output mode/Input mode/External interrupt(trigger irq when high to low(falling)))
     (5)   I2C_Master: Demonstrate the usage of I2C driver in Master mode.
     (6)   I2C_Slave: Demonstrate the usage of I2C driver in Slave mode.
     (7)   I2S_Master: Demonstrate I2S data transfer in Master mode.
     (8)   I2S_Slave: Demonstrate I2S data transfer in Slave mode.
     (9)   ISP_HID: This demo is the firmware of HID connection on ISP Tool.
     (10)  PDMA :  Demonstrate the usage of PDMA driver to read/write data.
     (11)  PMU_DeepSleep: Demonstrate how to power down in DeepSleep mode.
     (12)  PMU_DPD: Demonstrate how to power down in DeepPowerDown mode.
     (13)  PMU_Sleep: Demonstrate how to power down in Sleep mode.
     (14)  PMU_SPD: Demonstrate how to power down in StandbyPowerDown mode.
     (15)  PWM: Demonstrate the usage of PWM driver to output pulse.
     (16)  PWM_Capture: Demonstrate the usage of PWM driver to capture input pulse.
     (17)  PWM_DeadZone: Demonstrate the usage of PWM driver to show dead zone state.
     (18)  SARADC_SingleEnd: Demonstrate the usage of SARADC driver to get input analog at single end mode.
     (19)  SDADC_DAC_Loopback: Demonstrate SDADC input and DAC output.
     (20)  SPI_Master: Demonstrate SPI data transfer in Master mode.
     (21)  SPI_Slave: Demonstrate SPI data transfer in Slave mode.
     (22)  SPIFlash: Demonstrate how to control SPI flash via SPI interface.
     (23)  SYS: Demonstrate the usage of SYS driver to change clock frequency and source.
     (24)  Timer: Demonstrate the usage of Timer driver to delay, counte time and trigger interrupt.
     (25)  UART_TXRX: Demonstrate the usage of UART driver to transfer data.
     (26)  USBD_HID_Mouse: This sample code shows how to implement a HID device as mouse.
     (27)  USBD_HID_Transfer: Demonstrate how to implement a humane interface device to transfer data.
     (28)  USBD_Printer_And_HID_Transfer: Demonstrate how to implement a composite device.(USB micro printer device and HID Transfer).
     (29)  USBD_UAC_I2S: Demonstrate how to implement an UAC device to output data to 88L21(codedc device) via I2S interface.
     (30)  USBD_UAC_SDADC_DAC: Demonstrate how to implement an UAC device to input from SDADC(micphone) and output to DAC(headphone).
     (31)  USBD_VCOM_And_HIDTransfer: Demonstrate how to implement a composite device.(Virtual comport and HID Transfer).
     (32)  WDT: Demonstrate the usage of WDT driver to trigger interrupt.