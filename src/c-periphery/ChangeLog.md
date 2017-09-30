* v1.1.1 - 04/25/2017
    * Fix blocking `gpio_poll()` for some platforms.
    * Add library version macros and functions.
    * Contributors
        * Михаил Корнилов, @iTiky - 0643fe9

* v1.1.0 - 09/27/2016
    * Add support for preserving pin direction to `gpio_open()`.
    * Fix enabling input parity check in `serial_set_parity()`.
    * Fix enabling hardware flow control in `serial_set_rtscts()`.
    * Include missing header to fix build with musl libc.
    * Omit unsupported serial baudrates to fix build on SPARC.
    * Contributors
        * Thomas Petazzoni - 27a9552, 114c715

* v1.0.3 - 05/25/2015
    * Fix portability of serial baud rate set/get with termios-provided baud rate functions.
    * Fix unlikely bug in `spi_tostring()` formatting.
    * Clean up integer argument signedness in serial API.

* v1.0.2 - 01/31/2015
    * Fix `gpio_supports_interrupts()` so it does not return an error if interrupts are not supported.
    * Fix `errno` preservation in a few error paths, mostly in the open functions.

* v1.0.1 - 12/26/2014
    * Improve Makefile.
    * Fix _BSD_SOURCE compilation warnings.

* v1.0.0 - 05/15/2014
    * Initial release.
