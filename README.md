# STM32L4xx_Read-Write_Flash

**Note:**
+ I write the data at 0x08030000.
  ![alt text](https://github.com/ilhamahendra14/STM32L4xx_Read-Write_Flash/blob/593a3f20310d50314495664b9267ca53c951207e/Images/0x08030000_memory.png?raw=true)
+ For calculate the page is 0x08030000 - 0x080000000 = 0x00030000/2048 = 96.
+ Data from flash will be loaded in 'dataString'.
  ![alt text](https://github.com/ilhamahendra14/STM32L4xx_Read-Write_Flash/blob/593a3f20310d50314495664b9267ca53c951207e/Images/dataString.png?raw=true)
+ STM32L43KCU6 support write to flash with DOUBLEWORD data type, can be changed if it supports other data type.
