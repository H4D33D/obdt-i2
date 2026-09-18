# OBDT-i2

**On-Board Diagnostics & Telemetry — Iteration 2**

> **O-BEE** (Obadiah) for short — *On-Board Embedded Electronic*

---

## Hardware

### Microcontroller

~~**Arduino Nano R4**~~

> The Nano R4 uses a **Renesas architecture**, which differs from the original Nano used in OBDT-i1.  
> The current OBD-II hardware, libraries, and existing code were not working properly with the Renesas platform.

**Mega 2560 Pro Embed — USB-C**

- Uses the **ATmega2560** architecture.
- More compatible with the existing OBDT-i1 Arduino code and hardware.
- Provides significantly more I/O, memory, and serial interfaces than the original Nano.
- Compact embedded form factor despite being based on the Mega 2560.

### Display

**1.5" SH1107 128×128 OLED Display Module**

- Larger display than the previous version.
- Square 128×128 resolution.
- Requires updated display configuration/libraries compared with OBDT-i1.

### Storage

**MicroSD Card Adapter — HW-125**

- Same SD card adapter used in OBDT-i1.
- Already had several available.
- Physical size may become an issue when designing the final enclosure.

### Tools

**YIHUA 926 III Soldering Station**

- Budget soldering station.
- More than sufficient for prototyping and assembling OBDT-i2.

---

## Arduino IDE Configuration

**Board**

```text
Arduino Mega or Mega 2560
