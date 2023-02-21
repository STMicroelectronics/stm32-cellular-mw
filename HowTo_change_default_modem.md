# How To change default modem

## Modem status

Cellular middleware supports multiple modems.
X-CUBE-CELLULAR promotes STM32 Cellular middleware and contains different projects.
For configurations based on a STM32 MCU and a standalone modem it is possible to change the default used modem in the projects.
Note, STM32 MCU and modem are connected through STMod+ connectors.
Note there is a configuration (B-L462E-CELL1) based on a module that contains STM32 MCU and the modem, in this case the default modem can't be change.

## change modem procedure

There are 2 possibilities:
* project's IDE includes modem files from the original modem directory (ex BG96)
* project's IDE includes modem files from the generic "_embedded" modem directory

### original modem directory

Replace all the content of the original modem directory (ex BG96) with all the content from new modem directory (ex T1SC)

### generic modem directory

Replace all the content of the generic "_embedded" modem directory with all the content from new modem directory (ex T1SC)

