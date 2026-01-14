## Web Serial Flasher
A browser-based Web Serial implementation is included in `webserial_flasher.html`. Open the file in a Web Serial-enabled browser (Chrome/Edge), select the serial port, choose the firmware `.bin`, and flash. The protocol mirrors the desktop flasher: 115200 baud, erase packets (`0x39` to `0x3305` with `0x10` twice then `0x55`), followed by 1024-byte data packets (`0x57`) with checksum seeded by model selection.

[To try the web based flasher click here](https://nicsure.github.io/RT880-WebSerial-Firmware-Flasher/flash880.html)
