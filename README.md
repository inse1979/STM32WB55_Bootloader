# STM32WB55 USB DFU Bootloader Example

## Hardware
  ### [P-NUCLEO-WB5](https://www.st.com/en/evaluation-tools/p-nucleo-wb55.html)
  ![P-NUCLEO-WB55](https://www.st.com/bin/ecommerce/api/image.PF265562.en.feature-description-include-personalized-no-cpn-medium.jpg)
  -

## FLASH
|        | Start Sectors |  length | End Sectors | Description |
|  ----  | ------------  | ------- | ------------|-------------|
|    1   |  0x08000000   |   64K   | 0x080FFFFF  | bootloader  |
|    2   |  0x08010000   |   64K   | 0x0801FFFF  | user date   |
|    3   |  0x08020000   |  192K   | 0x0804FFFF  | freertos    |
|    4   |  0x08050000   |  192K   | 0x0807FFFF  | empty       |

---
