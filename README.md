# stm32h723-freertos-blinky

Blinky example for NUCLEO-H723ZG using freertos. Two threads run that both control one of the onboard LEDs.


# VS Code
To compile the code the VS Code extension stm32-for-vscode was used. It can install all the dependencies automatically once the project is opened.
It can then be used to compile and flash.


# Project setup
Used CubeMX to generate the files. (Mostly followed [this post](https://www.digikey.com/en/maker/projects/getting-started-with-stm32-introduction-to-freertos/ad275395687e4d85935351e16ec575b1) adapted to the H723. 
When generating the files make sure to use "the option to create a Makefile project under Project Manager->Project->Toolchain/IDE" as stated by stm32-for-vscode.
