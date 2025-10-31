RTT
===

SEGGER RTT Sources

https://www.segger.com/products/debug-probes/j-link/technology/about-real-time-transfer  
https://wiki.segger.com/RTT

## Included files

  * `include/`
    * `SEGGER_RTT_Conf.h`          - RTT configuration file.
    * `SEGGER_RTT.h`               - Main header for RTT.

  * `src/`
    * `SEGGER_RTT_Syscalls_GCC.c`  - Low-level syscalls to retarget `printf()` to RTT with different toolchains.
    * `SEGGER_RTT.c`               - Main module for RTT.
    * `SEGGER_RTT_ASM_ARMv7M.S`    - Assembly-optimized implementation of RTT functions for ARMv7M processors.
    * `SEGGER_RTT_Printf.c`        - Simple implementation of printf (`SEGGER_RTT_Printf()`) to write formatted strings via RTT.
