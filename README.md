# CMSIS Ports for uCOS-II and uCOS-III


## uCOS-II

### Introduction

    Based on version 2.92.14 [UCOS-II Port to Linux](https://github.com/jcdubois/uCOS-II)

    Port based on the [uC/OS-II Port to STM3232746G](https://www.micrium.com/download/stm32746g-proto_os2/)

### Main points

  	* Data types redefined as standard C types from stdint.h.

  	* OS_CPU_SysTickHandler renamed to SysTick_Handler (CMSIS)

  	* OS_CPU_PendSVHandler renamed to PendSV_Handler (CMSIS)


###  References

    *  [μC/OS-II and ARM Cortex-M3 Processors Application Note AN-1018](http://users.ece.utexas.edu/~valvano/EE345M/Micrium-ARM-uCOS-II-Cortex-M3.pdf)
    *  [Micrium uCOS-II ARM Port](https://courses.washington.edu/cp105/uCOS%20Port/uCOS%20Port.html)
    *  [µC/OS-II Release Notes](https://doc.micrium.com/pages/viewpage.action?pageId=12851586)
    *  [uC/OS-II Port to STM3232746G](https://www.micrium.com/download/stm32746g-proto_os2/)


## uCOS-III

    TBD
