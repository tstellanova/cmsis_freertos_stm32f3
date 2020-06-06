# cmsis_freertos_stm32f3

Builds FreeRTOS as a static library, 
intended to be invoked from the embedded rust
[freertos-sys crate](https://github.com/tstellanova/freertos-sys)

Creates a static FreeRTOS library for use with stm32f3xx.
This provides the API described in `cmsis_os2.h` -- in other words, 
the CMSIS RTOS v2 API. 