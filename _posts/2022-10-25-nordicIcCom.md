---
title:  "Nordic IC Comparison"
excerpt: "-----"

categories:
  - Blog
tags:
  - Blog
last_modified_at: 2022-10-20T08:06:00-05:00
---

| Features | nRF52803 | nRF52810 | nRF52811 | nRF52820 | nRF52832 | nRF52833 | nRF52840 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CPU | Cortex-M3 | Cortex-M4 | Cortex-M4 | Cortex-M4 | Cortex-M4 with FPU | Cortex-M4 with FPU | Cortex-M4 with FPU |
| 63 MHz | 64 MHz | 64 MHz | 64 MHz | 64 MHz | 64 MHz | 64 MHz |  |
|  |  |  |  |  |  |  |  |
| Memory | 191 kB flash | 192 kB flash | 192 kB flash | 256 kB flash | 512/256 kB flash | 512 kB flash | 1 MB flash |
| - | - | - | - | Cache | Cache | Cache |  |
| 23 kB RAM | 24 kB RAM | 24 kB RAM | 32 kB RAM | 64/32 kB RAM | 128 kB RAM | 256 kB RAM |  |
|  |  |  |  |  |  |  |  |
| EasyDMA MAXCNT bit length | I1S | - | - | - | - | 14 | 14 |
| PDM | - | 14 | 15 | - | 15 | 15 | 15 |
| PWM | - | 14 | 15 | - | 15 | 15 | 15 |
| RADIO | 7 | 8 | 8 | 8 | 8 | 8 | 8 |
| SAADC | - | 14 | 15 | - | 15 | 15 | 15 |
| SPIM | 13 | 10 | 14 | 15 | 8 | 16 | 16 |
| SPIS | 13 | 10 | 14 | 15 | 8 | 16 | 16 |
| TWIM | 13 | 10 | 14 | 15 | 8 | 16 | 16 |
| TWIS | 13 | 10 | 14 | 15 | 8 | 16 | 16 |
| UARTE | 9 | 10 | 10 | 15 | 8 | 16 | 16 |
| NFCT | - | - | - | - | 8 | 9 | 9 |
| USBD | - | - | - | 6 | - | 7 | 7 |
| QSPI | - | - | - | - | - | - | 19 |
|  |  |  |  |  |  |  |  |
| Crypto | AES engine | AES engine | AES engine | AES engine | AES engine | AES engine | AES engine |
| - | - | - | - | - | - | CryptoCell™309 |  |
|  |  |  |  |  |  |  |  |
| Radio | Protocols | Bluetooth Low Energy/ANT/1.4 GHz | Bluetooth Low Energy/ANT/2.4 GHz | Bluetooth Low Energy/ANT/2.4 GHz/IEEE 802.15.4 | Bluetooth Low Energy/Bluetooth mesh/Thread/ Zigbee/ANT/2.4 GHz/IEEE 802.15.4 | Bluetooth Low Energy/Bluetooth mesh/ANT/2.4 GHz | Bluetooth Low Energy/Bluetooth mesh/Thread/ Zigbee/ANT/2.4 GHz/IEEE 802.15.4 |
| Bluetooth 4 PHYs | 2 Mbps | 2 Mbps | 2 Mbps/Long range | 2 Mbps/Long range | 2 Mbps | 2 Mbps/Long range | 2 Mbps/Long range |
| Bluetooth 4.1 support | - | - | Yes | Yes | - | Yes | - |
| Output power | +3 dBm | +4 dBm | +4 dBm | +8 dBm | +4 dBm | +8 dBm | +8 dBm |
| Sensitivity | -98 dBm (Bluetooth 1 Mbps) | -96 dBm (Bluetooth 1 Mbps) | -97 dBm (Bluetooth 1 Mbps) | -95 dBm (Bluetooth Low Energy 1 Mbps) | -96 dBm (Bluetooth Low Energy 1 Mbps) | -95 dBm (Bluetooth Low Energy 1 Mbps) | -95 dBm (Bluetooth Low Energy 1 Mbps) |
|  |  |  |  |  |  |  |  |
| Clock | 31 MHz crystal | 32 MHz crystal | 32 MHz crystal | 32 MHz crystal | 32 MHz crystal | 32 MHz crystal | 32 MHz crystal |
| 63 MHz on chip (PLL) | 64 MHz on chip (PLL) | 64 MHz on chip (PLL) | 64 MHz on chip (PLL) | 64 MHz on chip (PLL) | 64 MHz on chip (PLL) | 64 MHz on chip (PLL) |  |
| 31.768 kHz crystal (optional) | 32.768 kHz crystal (optional) | 32.768 kHz crystal (optional) | 32.768 kHz crystal (optional) | 32.768 kHz crystal (optional) | 32.768 kHz crystal (optional) | 32.768 kHz crystal (optional) |  |
| 31.768 kHz on-chip RC | 32.768 kHz on-chip RC | 32.768 kHz on-chip RC | 32.768 kHz on-chip RC | 32.768 kHz on-chip RC | 32.768 kHz on-chip RC | 32.768 kHz on-chip RC |  |
| External 31.768 kHz clock | External 32.768 kHz clock | External 32.768 kHz clock | External 32.768 kHz clock | External 32.768 kHz clock | External 32.768 kHz clock | External 32.768 kHz clock |  |
|  |  |  |  |  |  |  |  |
| Power management | 0.7 V to 3.6 V supply voltage | 1.7 V to 3.6 V supply voltage | 1.7 V to 3.6 V supply voltage | 1.7 V to 5.5 V supply voltage |
| 0 stage LDO and DC/DC | 1 stage LDO and DC/DC | 1 stage LDO and DC/DC | 2 stage regulator LDO for high voltage and DC/DC or LDO for low voltage | 1 stage LDO and DC/DC | 2 stage regulator LDO for high voltage and DC/DC or LDO for low voltage | 2 stage LDO and DC/DC |  |
| - | - | - | On-chip VBUS 2.3 V reg | - | On-chip VBUS 3.3 V reg | On-chip VBUS 3.3 V reg |  |
| - | - | - | - | - | - | Regulated supply for external components |  |
|  |  |  |  |  |  |  |  |
| Digital interfaces | 0 × SPI master and slave | 1 × SPI master and slave | 2 × SPI master and slave | 2 × SPI master and slave | 3 × SPI master and slave | 4 × SPI master and 3 × SPI slave | 4 × SPI master and 3 × SPI slave |
| 0 × TWI master and slave | 1 × TWI master and slave | 1 × TWI master and slave | 2 × TWI master and slave | 2 × TWI master and slave | 2 × TWI master and slave | 2 × TWI master and slave |  |
| 0 × UARTE | 1 × UARTE | 1 × UARTE | 1 × UARTE | 1 × UARTE or UART | 2 × UARTE | 2 × UARTE |  |
| - | 0 × PWM | 1 × PWM | - | 3 × PWM | 4 × PWM | 4 × PWM |  |
| - | QDEC | QDEC | QDEC | QDEC | QDEC | QDEC |  |
| - | PDM | PDM | - | PDM | PDM | PDM |  |
| - | - | - | - | I1S | I2S | I2S |  |
| - | - | - | 0 × USB Full-speed device | - | 1 × USB Full-speed device | 1 × USB Full-speed device |  |
| - | - | - | - | - | 0 × high-speed SPI master | 1 × high-speed SPI master |  |
| - | - | - | - | - | - | 0 × Quad SPI (w.XIP) |  |
|  |  |  |  |  |  |  |  |
| Analog interfaces | - | 63-level analog comp | 64-level analog comp | 64-level analog comp | 64-level analog comp | 64-level analog comp | 64-level analog comp |
| - | - | - | - | 14-level low-power comp | 15-level low-power comp | 15-level low-power comp |  |
| 1-channel 12-bit ADC | 8-channel 12-bit ADC | 8-channel 12-bit ADC | - | 8-channel 12-bit ADC | 8-channel 12-bit ADC | 8-channel 12-bit ADC |  |
| - | - | - | - | NFC Tag | NFC Tag | NFC Tag |  |
| True Random Number Generator | True Random Number Generator | True Random Number Generator | True Random Number Generator | True Random Number Generator | True Random Number Generator | True Random Number Generator |  |
| Temperature sensor | Temperature sensor | Temperature sensor | Temperature sensor | Temperature sensor | Temperature sensor | Temperature sensor |  |
|  |  |  |  |  |  |  |  |
| Timers | 2 × 32-bit 16 MHz timers | 3 × 32-bit 16 MHz timers | 3 × 32-bit 16 MHz timers | 4 × 32-bit 16 MHz timers | 5 × 32-bit 16 MHz timers | 5 × 32-bit 16 MHz timers | 5 × 32-bit 16 MHz timers |
| 1 × 32.768 kHz RTC | 2 × 32.768 kHz RTC | 2 × 32.768 kHz RTC | 2 × 32.768 kHz RTC | 3 × 32.768 kHz RTC | 3 × 32.768 kHz RTC | 3 × 32.768 kHz RTC |  |
| Watchdog timer (31.768 kHz) | Watchdog timer (32.768 kHz) | Watchdog timer (32.768 kHz) | Watchdog timer (32.768 kHz) | Watchdog timer (32.768 kHz) | Watchdog timer (32.768 kHz) | Watchdog timer (32.768 kHz) |  |
|  |  |  |  |  |  |  |  |
| Other interfaces | SWI debug interface | SWI debug interface | SWI debug interface | SWI debug interface | SWI debug interface | SWI debug interface | SWI debug interface |
|  |  |  |  |  |  |  |  |
| PPI | 9 programmable channels | 20 programmable channels | 20 programmable channels | 20 programmable channels | 20 programmable channels | 20 programmable channels | 20 programmable channels |
| 11 fixed channels | 12 fixed channels | 12 fixed channels | 12 fixed channels | 12 fixed channels | 12 fixed channels | 12 fixed channels |  |
| 5 channel groups | 6 channel groups | 6 channel groups | 6 channel groups | 6 channel groups | 6 channel groups | 6 channel groups |  |
|  |  |  |  |  |  |  |  |
| Other features | BPROT | BPROT | BPROT | BPROT | BPROT | ACL | ACL |
| 5 × SWI | 6 × SWI | 6 × SWI | 6 × SWI | 6 × SWI | 6 × SWI | 6 × SWI |  |
| 1 × EGU | 2 × EGU | 2 × EGU | 6 × EGU | 6 × EGU | 6 × EGU | 6 × EGU |  |
| - | - | - | - | MWU | MWU | MWU |  |
|  |  |  |  |  |  |  |  |
| Power failure | Power-fail comparator and brownout | Power-fail comparator and brownout | Power-fail comparator and brownout | Power-fail comparator and brownout | Power-fail comparator and brownout | Power-fail comparator and brownout | Power-fail comparator and brownout |
|  |  |  |  |  |  |  |  |
| GPIO | Up to 9 pins | Up to 32 pins | Up to 32 pins | Up to 18 pins | Up to 32 pins | Up to 42 pins | Up to 48 pins |
| 7 × GPIOTEs channels | 8 × GPIOTEs channels | 8 × GPIOTEs channels | 8 × GPIOTEs channels | 8 × GPIOTEs channels | 8 × GPIOTEs channels | 8 × GPIOTEs channels |  |
|  |  |  |  |  |  |  |  |
| Packages | - | 5×6 mm QFN48 w/32 GPIOs | 6×6 mm QFN48 w/32 GPIOs | - | 6×6 mm QFN48 w/32 GPIOs | 7×7 mm AQFN73 w/42 GPIOs | 7×7 mm AQFN73 w/48 GPIOs |
| - | 4×5 mm QFN32 w/17 GPIOs | 5×5 mm QFN32 w/17 GPIOs | 5×5 mm QFN40 w/18 GPIOs and USB | - | 5×5 mm QFN40 w/18 GPIOs and USB | 6×6 mm QFN48 w/30 GPIOs |  |
| 1.5×2.5 mm WLCSP w/10 GPIOs | 2.5×2.5 mm WLCSP w/15 GPIOs | 2.5×2.5 mm WLCSP w/15 GPIOs | 2.5×2.5 mm WLCSP w/18 GPIOs and USB | 3.0×3.2 mm WLCSP w/32 GPIOs | 3.2×3.2 mm WLCSP w/42 GPIOs and USB | 3.5×3.6 mm WLCSP w/48 GPIOs and USB |  |
|  |  |  |  |  |  |  |  |
| Temperature | -41 to 85°C | -40 to 85°C | -40 to 85°C | -40 to 105°C | -40 to 85°C | -40 to 105°C | -40 to 85°C |
