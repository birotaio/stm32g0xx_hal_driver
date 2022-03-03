# STM32CubeG0 HAL Driver MCU Component

![latest tag](https://img.shields.io/github/v/tag/STMicroelectronics/stm32g0xx_hal_driver.svg?color=brightgreen)

## Overview

**STM32Cube** is an STMicroelectronics original initiative to ease developers' life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio. It includes a comprehensive embedded software platform delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the ARM(tm) core implemented in this STM32 product.
   * The STM32 HAL-LL drivers, an abstraction layer offering a set of APIs ensuring maximized portability across the STM32 portfolio.
   * The BSP drivers of each evaluation, demonstration or nucleo board provided for this STM32 series.
   * A consistent set of middleware libraries such as RTOS, USB, FatFS, graphics, touch sensing library...
   * A full set of software projects (basic examples, applications, and demonstrations) for each board provided for this STM32 series.

Two models of publication are proposed for the STM32Cube embedded software:
   * The monolithic **MCU Package**: all STM32Cube software modules of one STM32 series are present (Drivers, Middleware, Projects, Utilities) in the repository (usual name **STM32Cubexx**, xx corresponding to the STM32 series).
   * The **MCU component**: each STM32Cube software module being part of the STM32Cube MCU Package, is delivered as an individual repository, allowing the user to select and get only the required software functions.

## Description

This **stm32g0xx_hal_driver** MCU component repo is one element of the STM32CubeG0 MCU embedded software package, providing the **HAL-LL Drivers** part.

## License

Copyright (c) 2018 STMicroelectronics.

This software component is licensed by STMicroelectronics under BSD 3-Clause license. You may not use this file except in compliance with the License. 
You may obtain a copy of the License [here](https://opensource.org/licenses/BSD-3-Clause).

## Release note

Details about the content of this release are available in the release note [here](https://htmlpreview.github.io/?https://github.com/STMicroelectronics/stm32g0xx_hal_driver/blob/master/Release_Notes.html).

## Compatibility information

In this table, you can find the successive versions of this HAL-LL Driver component, in line with the corresponding versions of the full MCU package:

It is **crucial** that you use a consistent set of versions for the CMSIS Core - CMSIS Device - HAL, as mentioned in this table.

HAL Driver G0 | CMSIS Device G0 | CMSIS Core     | Was delivered in the full MCU package
------------- | --------------- | -------------- | -----------------------------------------------------
Tag v1.2.0    | Tag v1.2.0      | Tag v4.5_cm0   | Tag v1.2.0 (and following, if any, till next HAL tag)
Tag v1.3.0    | Tag v1.3.0      | Tag v5.4.0_cm0 | Tag v1.3.0 (and following, if any, till next HAL tag)
Tag v1.4.0    | Tag v1.4.0      | Tag v5.6.0_cm0 | Tag v1.4.0 (and following, if any, till next HAL tag)
Tag v1.4.1    | Tag v1.4.0      | Tag v5.6.0_cm0 | Tag v1.4.1 (and following, if any, till next HAL tag)
Tag v1.4.2    | Tag v1.4.1      | Tag v5.6.0_cm0 | Tag v1.5.0 (and following, if any, till next HAL tag)
Tag v1.4.3    | Tag v1.4.1      | Tag v5.6.0_cm0 | None (will be integrated into next HAL tag v1.4.4)

The full **STM32CubeG0** MCU package is available [here](https://github.com/STMicroelectronics/STM32CubeG0).

## Troubleshooting

If you have any issue with the **software content** of this repository, you can file an issue [here](https://github.com/STMicroelectronics/stm32g0xx_hal_driver/issues/new).

For any other question related to the product, the tools, the environment, you can submit a topic on the [ST Community/STM32 MCUs forum](https://community.st.com/s/group/0F90X000000AXsASAW/stm32-mcus).
