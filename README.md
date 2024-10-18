# meta-raspberrypi-delia

This is an added layer on top of the [meta-raspberrypi](https://github.com/agherzan/meta-raspberrypi) layer maintained by Andrei Gherzan.

# Dependencies

All the necessary layers needed by `meta-raspberrypi` are also required by this layer.
Additionally, this layer also depends on [meta-delia](https://github.com/Melbourne-Instruments/meta-delia) and [meta-swupdate-delia](https://github.com/Melbourne-Instruments/meta-swupdate-delia) for the delia swupdate feature.

Any new recipe that is common for products built with delia Pi as a platform should be in this layer.

Customizations done through bbappend recipes for meta-raspberrypi or OE recipes which are
common to products built with delia Pi as a platform shall also be in this layer.

# Main components

The key contributions of this layer to delia OS image are:

  * Custom Linux kernel with I-Pipe and Xenomai enabled.
  * U-boot configuration and boot scripts for delia Pi.
  * Elk System configurations.
  * SWUpdate configuration for delia Pi.
  * Other system-related modifications.

---
Copyright 2021-2024 Melbourne Instruments, Australia.
