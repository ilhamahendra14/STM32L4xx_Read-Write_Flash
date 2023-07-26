# STM32L4xx_Read-Write_Flash

**Note:**
+ I write the data at 0x08030000.
+ For calculate the page is 0x08030000 - 0x080000000 = 0x00030000/2048 = 96.
+ Data from flash will be loaded in 'dataString'.
+ STM32L43KCU6 support write to flash with DOUBLEWORD data type, can be changed if it supports other data type.
