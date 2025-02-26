# esp32-h2-supermini-kicad
This project focuses on the comprehensive development of a KiCad library component for the ESP32-H2-Supermini module. The goal is to provide accurate and high-quality resources for designers using KiCad to integrate this powerful wireless microcontroller into their projects.

![ESP32-H2 Supermini Module Image](https://github.com/manupawickramasinghe/esp32-h2-supermini-kicad/blob/main/resources/0d1f210029fd1da4822f4db8de7f80b6fb9caa32_2_572x500.jpeg)

**ESP32-H2 Supermini Description**

The ESP32-H2 Supermini is a compact, low-power wireless module powered by the Espressif ESP32-H2 System-on-Chip (SoC). Designed for space-constrained IoT applications, it integrates a 32-bit RISC-V core, Bluetooth 5.2 Low Energy (BLE), and IEEE 802.15.4, supporting Thread, Zigbee, and Matter protocols. This module is perfect for smart home devices, wearables, and other applications requiring reliable, energy-efficient wireless connectivity. This KiCad library provides accurate symbols, footprints, and 3D models to simplify integration into your projects.

**Importing Symbols and Footprints into KiCad (Simplified Steps)**

1. **Download the Library:**  
   * Download or clone the ESP32-H2 Supermini KiCad library files (symbols: `.lib`, footprints: `.kicad_mod`).

2. **Open KiCad:**  
   * Launch KiCad's Project Manager.

3. **Add Symbol Library:**  
   * Go to "Preferences" -> "Manage Symbol Libraries."
   * Click the folder icon to add a new library.
   * Navigate to the downloaded `.lib` file and select it.
   * Click "OK."

4. **Add Footprint Library:**  
   * Go to "Preferences" -> "Manage Footprint Libraries."
   * Click the folder icon to add a new library.
   * Navigate to the folder containing the downloaded `.kicad_mod` files and select it.
   * Click "OK."

5. **Use the Components:**  
   * In the Schematic Editor, click "Add Symbol" and search for the ESP32-H2 Supermini symbol.
   * In the PCB Editor, click "Add Footprint" and select the corresponding footprint.

![KiCad Symbol Editor Screenshot](https://github.com/manupawickramasinghe/esp32-h2-supermini-kicad/blob/main/resources/Screenshot%20from%202025-02-26%2022-04-52.png)

![Zigbee Universal Sensor in KiCad](https://github.com/manupawickramasinghe/esp32-h2-supermini-kicad/blob/main/resources/zigbee-universal-sensor-kicad.png)

**ESP32-H2 Supermini Pinout Explanation**

**Important Note:** *Always refer to the official ESP32-H2 Supermini module datasheet for the precise pinout of your specific board variant.*

**General Pin Grouping:**

* **Power Supply:**
  * `VCC`: 3.3V Power input.
  * `GND`: Ground connection.

* **GPIO (General Purpose Input/Output):**
  * These pins can be configured as digital inputs or outputs.
  * Many GPIOs have alternate functions, including:
    * `ADC`: Analog-to-Digital Converter inputs for measuring analog signals.
    * `UART`: Serial communication pins for transmitting and receiving data.
    * `SPI`: Serial Peripheral Interface pins for communicating with SPI devices.
    * `I2C`: Inter-Integrated Circuit pins for I2C communication.

* **RF (Radio Frequency):**
  * `ANT`: Antenna connection for wireless communication.

* **Debug/Programming:**
  * `JTAG` (If applicable): Pins for debugging and programming the chip.

**Pinout Table (Example - Adapt to your specific board):**

![ESP32-H2 Module Image](https://github.com/manupawickramasinghe/esp32-h2-supermini-kicad/blob/main/resources/S6361424269644a4ab50544fc9f406a78m.jpg_960x960q75.jpg_.avif)

| Pin Name | Function(s) | Notes |
| :------- | :---------- | :---- |
| VCC      | Power       | 3.3V Input |
| GND      | Ground      | Ground connection |
| GPIO0    | GPIO, UART_TX | Configurable I/O, UART transmit |
| GPIO1    | GPIO, UART_RX | Configurable I/O, UART receive |
| GPIO2    | GPIO, ADC1_IN | Configurable I/O, Analog input |
| ANT      | RF Antenna  | 2.4 GHz antenna connection |
| ...      | ...         | ... |

**Key README Notes:**

* **Datasheet Link:** Provide a direct link to the ESP32-H2 Supermini module's datasheet.
* **Pin Multiplexing:** Clearly state that GPIO pins have multiple functions, and software configuration determines their use.
* **Board Variations:** Emphasize that pinouts may vary slightly between different ESP32-H2 Supermini boards.
* **Clear Graphics:** If possible, add a pinout diagram graphic to your README.

By including these refined instructions and explanations, you'll make it significantly easier for users to integrate the ESP32-H2 Supermini into their KiCad projects.


