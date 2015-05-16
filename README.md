# STM32F401RE-template-with-SPL
A template for projects for the STM32 Nucleo F401RE board, using the standard peripheral library (SPL).

I'm trying to set up a simple environment for compiling code using ST's SPL from the command line without the need for an IDE.

The template consists of an include-directory with header-files, a src directory with the necessary .c-files and a startup- and linker script.

The makefile assumes that the working directory is located in the directory that the stm32f4_dsp_stdperiph_lib.zip extracts to.
