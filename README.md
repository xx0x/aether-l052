# Æther L052

A development board using the STM32L052K8U3, optimized for low-power use. Its form factor matches the Adafruit Feather series.

<a href="./photos/aether-l052-set.jpg"><img src="./photos/aether-l052-set.jpg" alt="Aether L052" width="500"></a>

## Schematic

<a href="./pcb/aether-l052-v1/aether-l052-v1-schematic.pdf"><img src="./photos/aether-l052-schematic-v1.png" alt="Aether L052" width="500"></a>  
*Click to see the full-size PDF*

## Specifications

### Microcontroller

| Name             | STM32L052K8U3       |
| ---------------- | ------------------- |
| Core             | ARM Cortex M0+      |
| Flash Size       | 64 kB               |
| RAM Size         | 8 kB                |
| Clock Frequency  | 32 MHz              |
| Peripherals      | USB, SPI, I2C, UART |
| External Crystal | None                |

### Voltage Regulator

| Name              | MCP1711T-33I/OT |
| ----------------- | --------------- |
| Output Voltage    | 3.3 V           |
| Output Current    | 150 mA          |
| Quiescent Current | 600 nA          |

### Lithium Battery Charger

| Name           | MCP73832T-2ACI/OT     |
| -------------- | --------------------- |
| Charge Current | 100 mA (set using R4) |
| Charge State   | Available through PB8 |

## Why it exists?

There was no entry-level development board for the STM32L052 series, especially for the compact STM32L052K8Ux variant.

## Where to get it?

Æther L052 is open source and not sold in shops. You can build your own; all required files are in the `pcb` folder. If you are a manufacturer, you may reuse the design under the License, or contact me first if you prefer.

## Code examples

Look at the [STM32 L052 examples](https://github.com/xx0x/stm32-l052-examples) repository.


## License

CERN-OHL-P-2.0 license


