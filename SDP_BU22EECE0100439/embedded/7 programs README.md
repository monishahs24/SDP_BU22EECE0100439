**MONISHA H S BU22EECE0100439**

**HANDS ON ACTIVITY:**

**EMBEDDED SYSYTEM COMPARISON 8051 AND ARDUINO**

| **Feature** | **8051 Micro-**<br><br>**controller** | **Arduino** |
| --- | --- | --- |
| **Architecture** | **Harvard** | **Modified Harvard** |
| **Instruction Set** | **8-bit** | **8-bit (AVR) or 32-bit (ARM)** |
| **Clock Speed** | **Typically up to 12**<br><br>**MHz** | **8 MHz (Uno), 16 MHz (Mega), varies with**<br><br>**different boards** |
| **Memory** | **ROM, RAM, EEPROM** | **Flash, SRAM, EEPROM** |
| **GPIO Pins** | **Limited** | **Abundant, typically 20 or more** |
| **Analog Inputs** | **Usually limited** | **Typically multiple, 6 or more** |
| **Digital I/O** | **Limited** | **Abundant** |
| **Development Tools** | **Limited availability** | **Extensive community support, IDE like Arduino IDE** |
| **Programming** | **Assembly, C** | **Arduino Sketch (C/C++)** |
| **IDE Support** | **Limited** | **Arduino IDE, PlatformIO** |
| **Debugging** | **Limited** | **Limited (Serial debugging, LED blinking)** |
| **Cost** | **Affordable** | **Affordable** |

**To summarize:**

# Architecture and Instruction Set

- The 8051 is an 8-bit microcontroller with a simple architecture and instruction set.
- Arduino boards typically use AVR or ARM-based microcontrollers, which have more advanced architectures and instruction sets compared to the 8051.

# Memory Organization

- The 8051 typically has limited on-chip memory for program storage and data storage.
- Arduino boards often have more memory available compared to the 8051, both in terms of program memory (flash) and data memory (RAM).

# Peripheral Integration

- The 8051 usually requires external components for additional functionality such as timers, UART, and I/O ports.
- Arduino boards often integrate many peripherals on the board itself, such as UART, SPI, I2C, digital I/O pins, analog inputs, PWM channels, etc., making it easier to interface with external devices.

# Development Environment

- Programming the 8051 microcontroller typically involves using specific IDEs and compilers provided by the manufacturer, such as Keil or SDCC.
- Arduino provides a user-friendly development environment based on the Arduino IDE, which abstracts away much of the low-level details and simplifies the programming process. It also offers a vast library of pre-written functions for various tasks.

# Interrupt Handling

- Both the 8051 and Arduino support interrupts for handling asynchronous events.
- Arduino abstracts away much of the complexity of interrupt handling, making it easier for beginners to work with interrupts.

# Power Consumption

- The 8051 is known for its low power consumption, making it suitable for battery-powered applications.
- Arduino boards vary in power consumption depending on the specific microcontroller used and the peripherals connected to it.

# Performance

- The performance of the 8051 is modest and suitable for many embedded applications but may not be suitable for high-performance computing tasks.
- Arduino boards typically have better performance compared to the 8051, especially if they use ARM-based microcontrollers. This allows for more complex tasks and faster execution of code.
