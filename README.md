# VBRS — Vertical Baseline Radar System [concept]

**GNSS-free 3-D tracking from two synchronized 2-D radars.**  

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
Counter-UAS (e.g., Shahed136-class), gap-filling air picture, range safety, perimeter airspace monitoring.

*VBRS-40 = 40 m vertical baseline reference configuration.*


# VBRS — Радарна система з вертикальною базою (Vertical Baseline Radar System) [концепція]

**3-D супровід без GNSS від двох синхронізованих 2-D радарів.**  

## Ключові характеристики (базова конфігурація VBRS-40)
- **Дальність:** ~20 км  
- **Діапазон висот:** ~5 км  
- **Синхронізація:** опора на атомний годинник (Rb/CSAC), 10 МГц по волокну + тригер, калібрована затримка лінії  
- **Відносна синхронізація:** ≤100 нс (тип.); опція: модуль **White Rabbit** (<1 нс)  
- **Діапазони:** S- або X-діапазон (залежно від сенсора)  
- **Вихідні дані:** файл 3-D-траєкторії (швидкість, висота), сирі/ПЧ-дані (опційно)  
- **ПЗ:** **VBRS Console** для налаштування, калібрування та візуалізації  
- **Залежність від GNSS:** відсутня (працює у середовищах без GPS)

## Що це таке
Повністю **готова до використання система** — сенсори, блок синхронізації та таймінгу, енергетика/зв’язок, крайовий процесор і UI — яка використовує **вертикальну базу** для відновлення висоти за даними **спарених 2-D радарів**.

## Опції
- Синхронізація **White Rabbit** (<1 нс)  
- Синхронізаційна інфраструктура **PTPv2** (з апаратними мітками часу)  
- **Набір розробника** (лабораторія/POC) або **Польова система** (розгортання)

## Сфери застосування
Протидія БпЛА (напр., клас **Shahed-136**), заповнення прогалин повітряної обстановки, безпека полігонів, моніторинг периметра повітряного простору.

*VBRS-40 = еталонна конфігурація з вертикальною базою 40 м.*

