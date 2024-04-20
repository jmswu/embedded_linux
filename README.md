# embedded_linux

# Boot order

**See TRM Table 26-7**

Boot SW released (SYSBOOT[4:0] = 0b11100)
* MMC1 (eMMC)
* MMC0 (SD Card)
* UART0
* USB0

Boot SW Pressed (SYSBOOT[4:0] = 0b11000)
* SPI0
* MMC0 (SD Card)
* USB0
* UART0