# Minimal LL template for STM32F3xxx

## Credits
From https://www.purplealienplanet.com/node/69 and the templates and examples in the STM32CubeF3 package documentation.

## Installation
### Clone this repo
    git clone https://github.com/Seveen/stm32-minimal-f3.git
    cd stm32-minimal

You need the STM32CubeF3 soft package from ST https://my.st.com/content/my_st_com/en/products/embedded-software/mcu-mpu-embedded-software/stm32-embedded-software/stm32cube-mcu-mpu-packages/stm32cubef3.html
Copy Drivers directory from ST soft package to ./Drivers

## Usage
### Compilation
    make

### Flash
    st-flash --reset write project.bin 0x08000000
