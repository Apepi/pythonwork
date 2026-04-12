  ### Summary

  Added hwdef files for the EchoUS-L431 CAN peripheral node and EchoUS-Airspeed SDP3x
  CAN airspeed sensor by Echo Unmanned Systems. Board ID 1337 reserved in
  `Tools/AP_Bootloader/board_types.txt`.

  ### Classification & Testing

  - [x] Checked by a human programmer
  - [x] Tested on hardware

  ### Description

  Adds board definitions for two EchoUS AP_Periph peripherals based on the STM32L431 microcontroller:

  #### EchoUS-L431
  A compact CAN peripheral node featuring:
  - DroneCAN interface
  - SPI1 with RM3100 magnetometer support
  - I2C2 bus
  - 3x UARTs (debug, MSP, GPS)
  - 5V input (5.5V max)

  [Product page](https://echounmanned.com/products/dronecan-ap_periph-module) | [Documentation](https://echo-us.github.io/can-node/overview)

  #### EchoUS-Airspeed
  A DroneCAN-connected SDP3x airspeed sensor node featuring:
  - SDP3x differential pressure sensor (DLVR 10", ±1500 Pa)
  - Maximum airspeed: 50 m/s
  - Dual CAN connectors for daisy-chaining
  - 5V input (5.5V max)

  [Product page](https://echounmanned.com/products/echouas-sensirion-airspeed-sensor-sdp33?variant=41177514672262) |
  [Documentation](https://echo-us.github.io/sdp3x-airspeed-sensor/can-version)

  Both boards are manufactured by Echo Unmanned Systems and are available for purchase.

> **Note:** Bootloader binary PR (`bootloaders: EchoUS-L431`) will follow.                                                                                            > Hardware is already in production and available for purchase. Binaries are                                                                                        > being re-validated before submission.
