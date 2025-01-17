# STM32CubeG4 MCU Firmware Package

**STM32Cube** is an STMicroelectronics original initiative to ease the developers life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio. It includes a comprehensive embedded software platform delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the ARM(tm) core implemented in this STM32 product.
   * The STM32 HAL-LL drivers, an abstraction layer offering a set of APIs ensuring maximized portability across the STM32 portfolio.
   * The BSP drivers of each evaluation, demonstration or nucleo board provided for this STM32 series.
   * A consistent set of middleware components such as RTOS, USB, FatFS, graphics, touch sensing library...
   * A full set of software projects (basic examples, applications, and demonstrations) for each board provided for this STM32 series.

The **STM32CubeG4 MCU Package** projects are directly running on the STM32G4 series boards. You can find in each Projects/*Board name* directories a set of software projects (Applications/Demonstration/Examples).

## Matternet Addendum

* The Cube firmware package has template files in <code>./Drivers/STM32G4xx_HAL_Driver</code>.  The Cube software modifies these files for automatic code generation in the Cube environment.  These files have been renamed (appending ".org" to their filename) so that they are not automatically included in a project (our makefile will automatically include any C header and source files).

## Release note

Details about the content of this release are available in the release note [here](https://htmlpreview.github.io/?https://github.com/STMicroelectronics/STM32CubeG4/blob/master/Release_Notes.html).

## Boards available

  * STM32G4
    * [STM32G474E-EVAL](https://www.st.com/en/product/stm32g474e-eval.html)
    * [NUCLEO-G431KB](https://www.st.com/en/product/nucleo-g431kb.html)
    * [NUCLEO-G431RB](https://www.st.com/en/product/nucleo-g431rb.html)
    * [NUCLEO-G474RE](https://www.st.com/en/product/nucleo-g474re.html)
    * [B-G474E-DPOW1](https://www.st.com/en/product/b-g474e-dpow1.html)

## Troubleshooting

**Caution** : The issues and the pull-requests are **strictly limited** to submit problems or suggestions related to the software delivered in this repository.

**For any other question** related to the product, the hardware performance or characteristics, the tools, the environment, you can submit it to the **ST Community** on the STM32 MCUs related [page](https://community.st.com/s/group/0F90X000000AXsASAW/stm32-mcus).
