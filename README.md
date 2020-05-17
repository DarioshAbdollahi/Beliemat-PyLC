**In The Name of God**
# PyLC
A PLC that is programmed with Python

**Open Source PyLC**

The PyLC is an open-source PLC (programmable logic controller) that can be programmed using open source Python language programming tools.

The Open Source PyLC was designed to provide a Python programmable PLC for embedded software engineers and programmers.

![](RackMultipart20200517-4-1pewsf9_html_c6e562918a0dac93.jpg)

This picture shows the large open source PyLC operating Festo Pneumatic valves and actuators in an automation demonstration.

# **PyLC Applications**

Some applications that the PyLC (Open Source PyLC) can be used in:

- Machine Control

- Automatic Test Equipment (ATE)

- Computer I/O and communication expansion

- Data logging to EEPROM memory

- Process Control

- Process Monitoring

- Home Automation
- Medical Devices Like MLC

**Open Source PyLC Features**

| **Power Supply** | 12 to 24 Volts DC |
| --- | --- |
| **Digital Inputs** | 22 Inputs with LED indicators (12 to 24V) |
| **Digital Outputs** | 16 NPN open-collector (current sinking) outputs rated at 200mA each |
| **Analogue Inputs** | 6 analogue inputs rated at 0V to 10V, 10-bit resolution |
| **Communications** | 1 × USB device port, 2 × RS-232 ports (TX and RX only), 1 × RS-485 port, 1 × JTAG debug port |
| **Real Time Clock** | Seconds, minutes, hours, day, month, years, and century
 Automatic leap year compensation
 Battery backup |
| **Memory** | 1024k bytes Flash memory for program and data storage
 192k bytes SRAM for program and data storage
 16k EEPROM for non-volatile storage, general-purpose use
 SD card socket for SD or MMC memory card |
| **Microcontroller** | STM32F405RG 32-bit ARM microcontroller from ST Electronics
 Clock speed 168MHz |
| **Mounting** | Uses standard DIN rail for mounting |
| **Programming** | MicroPython is loaded via the JTAG port .Code is loaded via the USB port |

The image below shows the bottom side of the PyLC. The communication ports, analogue inputs and digital (transistor) outputs can be seen.

![](RackMultipart20200517-4-1pewsf9_html_cebde8e7bfc06fae.jpg)

This picture shows a barcode scanner connected to the PyLC. It is easy to get the barcode and display it on the RS485 LCD display by writing software in Python

Components used to construct the Open Source PyLC including case, boards and connectors.

**PyLC Circuit Boards**

Open Source PyLC consists of three circuit boards:

- **CPU Board** – contains the microcontroller, RTC and other ICs.
- **IO Board** – contains the power supply regulator, optically isolated input and output circuitry and connectors.
- **Status Board** – input indicator LEDs, reset switch, status LED and USB connector.

**Design Source Files for the Open Source PyLC**

The boards were designed using Altium designer.

**CPU Board**

The PyLC CPU board is mounted on the IO board with two rows of pin headers.

**IO board**

The I/O board has components mounted on both sides of the board.

**Status Board**


# **Motivation for the Design**

Existing PLCs have restricted programming languages such as ladder logic. PLC software is proprietary and varies from manufacturer to manufacturer.

Embedded software engineers usually find PLC programming languages frustrating to use, but the advantage of a PLC is that it is an off-the-shelf general-purpose controller. There is no need to design new hardware when a controller is needed.

The Open Source PyLC was designed to be an off-the-shelf Python programmable general-purpose controller targeted to engineers and other embedded programmers. The idea is to have an industrially packaged and designed Python programmable microcontroller – packaged like and having an interface like a commercial PLC.
