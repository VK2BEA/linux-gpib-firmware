# linux-gpib-firmware
Firmware for Agilent/Keysight and NI USB GPIB adapters

Packaged from https://linux-gpib.sourceforge.io/firmware/

* This firmware is required for use with adapters compatible with the:
  - NI GPIB-USB-B (the NI GPIB-USB-HS/HS+ do not need firmware)
  - HP/Agilent/Keysight 82341C (High-Performance GPIB Interface Card)
  - HP/Agilent/Keysight 82341D (High-Performance GPIB Interface Card)
  - HP/Agilent/Keysight 82350A (PCI High-Performance GPIB Interface Card)
  - HP/Agilent/Keysight 82357A (USB/GPIB Interface)
  - HP/Agilent/Keysight 82357B (USB/GPIB Interface High-Speed USB 2.0)

`udev` rules are installed that trigger the loading of firmware (via `systemd` service files) when the USB devices are connected (or on boot).

This package is derived from  https://github.com/vddvss/linux-gpib-firmware-packaging


