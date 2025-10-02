# VBRS — Vertical Baseline Radar System

**GNSS-free 3-D tracking from two synchronized 2-D radars.**  
Timing is anchored by an **atomic clock reference (Rb/CSAC)** with **fiber-distributed 10 MHz** and deterministic hardware triggers, maintaining **sub-µs** inter-sensor alignment for coherent processing and reliable altitude estimation.

## Key Specs (baseline VBRS-40)
- **Range:** ~20 km  
- **Altitude coverage:** ~5 km  
- **Timing:** Atomic-clock referenced (Rb/CSAC), fiber 10 MHz + trigger, calibrated link delay  
- **Relative sync:** ≤100 ns (typ.); option: **White Rabbit** module (<1 ns)  
- **Bands:** S- or X-band (sensor-dependent)  
- **Outputs:** 3-D track file (velocity, altitude), raw/IF data (optional)  
- **Software:** VBRS Console for setup, calibration, and visualization  
- **GNSS dependence:** None (GPS-denied capable)

## What it is
A complete **turn-key system**—sensors, timing & sync unit, power/comms integration, edge processor, and UI—using a **vertical baseline** to recover altitude from **paired 2-D radars**.

## Options
- White Rabbit timing (<1 ns)  
- PTPv2 (HW-timestamped) timing plant  
- Dev Kit (lab/POC) vs. Field System (deployable)

## Use Cases
Counter-UAS (e.g., Shahed-class), gap-filling air picture, range safety, perimeter airspace monitoring.

*VBRS-40 System = 40 m vertical baseline reference configuration.*
