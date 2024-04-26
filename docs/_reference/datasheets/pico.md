---
title: RPi Pico 
parent: Datasheets
nav_order: 2
---

# Raspberry Pi Pico (RP2040) Microcontroller

The standard microcontroller used in the labs, and on the Leeds Beckett development board, is the [Raspberry Pi RP2040](https://www.raspberrypi.com/documentation/microcontrollers/rp2040.html#welcome-to-rp2040) microcontroller. The official source of data for these microcontrollers can be found [on the Raspberry Pi site](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html).

The Raspberry Pi foundation currently also packages the RP2040 microcontroller onto four development boards. Shown below these are the Raspberry Pi Pico (far left), Pico H (middle left), Pico W (middle right), and Pico WH (far right). Boards with the 'H' designation have standard 0.1" headers (suitable for use on breadboards): the other boards have castellations for direct soldering.

![Pins for the Pico WH]({{ site.baseurl }}/assets/datasheets/pico/four_picos.jpg)

The Leeds Beckett development boards use the Pico WH, with both the Pi Pico and Pi Pico H available from the Helpdesk. A pin diagram for the Pico WH is also shown below, with printable versions for all four boards [below](#pin-diagrams).

![Pins for the Pico WH]({{ site.baseurl }}/assets/datasheets/pico/picow-pinout.svg)

{: .note }

In _most_ cases the Pico (Pico H) and Pico W (Pico WH) are interchangeable, apart from the additional user LED on the Pico W and Pico WH. For details of the component and electrical changes between the four boards, [see the official documentation](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html).

## Pico Board Pin Diagrams

* [Pico and Pico H]({{ site.baseurl }}/assets/datasheets/pico/Pico-R3-A4-Pinout.pdf)
* [Pico and Pico W]({{ site.baseurl }}/assets/datasheets/pico/PicoW-A4-Pinout.pdf)

## Pico Board Datasheet

As standard, the Pico boards come with 264kB of SRAM, and 2MB of on-board flash memory. All versions use a dual-core Arm Cortex M0+ processor, clocked by default to 133 MHz. Connections include 26 multi-function GPIO pins; which can also be reconfigured as a combination of 2x SPI, 2x I2C, 2x UART, 3x 12-bit ADC, or 16x controllable PWM channels. See the [pin diagrams above](#pin-diagrams), and the datasheet below, for the specific combinations allowed.

* [Pico Board Datasheet]({{ site.baseurl }}/assets/datasheets/pico/pico-datasheet.pdf)