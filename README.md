# STM32HAL_H7
This is version 1.4.0 of the STM32H7 HAL, but modified slightly so that I can easily integrate it into my project's Boost.Build system. The only changes to the core HAL are modifying the #includes to be relative to a single directory, as that helps simplify the number of explicit include directories to the compiler.

In addition, the core CMSIS headers needed for compilation are included as well. 
