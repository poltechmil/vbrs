# VBRS — Vertical Baseline Radar System [concept]

GNSS-free 3-D tracking from two synchronized 2-D radars.
Timing is anchored by an atomic clock reference (Rb/CSAC) with fiber-distributed 10 MHz and deterministic hardware triggers, maintaining sub-µs inter-sensor alignment for coherent processing and reliable altitude estimation.

## Key Specs (baseline VBRS-40)
- Range: ~20 km
- Altitude coverage: ~5 km
- Timing: Atomic-clock referenced (Rb/CSAC), fiber 10 MHz + trigger, calibrated link delay
- Bands: S- or X-band (sensor-dependent)
- Outputs: 3-D track (azimuth, range, altitude, velocity); raw/IF data (optional)
- Software: VBRS Console for setup, calibration, and visualization

## Numeric Targets (VBRS-40 reference)
- Operational range: ~20 km
- Altitude coverage: ~5 km
- Vertical baseline: 40 m
- Altitude accuracy (goal): ±100 m at 20 km; ±50 m at 10 km; ±25 m at 5 km
- Relative timing alignment: ≤100 ns (typ.); option <1 ns with White Rabbit
- Revisit / update rate: ≥1 Hz per 3-D track (goal)
- Track output latency (goal): ≤500 ms from last hit to 3-D update
- Mast head deflection under wind load: ≤5 cm (peak)
- Bands: S- or X-band (sensor-dependent), tuned for Shahed-136-class RCS
- GNSS dependence: none (atomic-clock referenced)

## What it is
A complete turnkey system—sensors, timing & sync unit, power & comms integration, edge processor, and UI—using a vertical baseline to recover altitude from paired 2-D radars.

## Options
- White Rabbit timing (<1 ns)
- PTPv2 (HW-timestamped) timing plant
- Dev Kit (lab/POC) vs. Field System (deployable)

## Use Cases
Counter-UAS (e.g., Shahed-136 class), gap-filling air picture, range safety, perimeter airspace monitoring.

VBRS-40 = 40 m vertical-baseline reference configuration.

# VBRS — Радарна система з вертикальною базою [концепція]

3-D супровід без GNSS від двох синхронізованих 2-D радарів.
Синхронізація ґрунтується на опорному атомному годиннику (Rb/CSAC) з розподілом 10 МГц по волокну та детермінованими апаратними тригерами, що забезпечує субмікросекундне вирівнювання між сенсорами для когерентної обробки і надійної оцінки висоти.

## Ключові характеристики (базова конфігурація VBRS-40)
- Дальність: ~20 км
- Діапазон висот: ~5 км
- Синхронізація: атомний годинник (Rb/CSAC), 10 МГц по волокну + тригер, калібрована затримка лінії
- Діапазони: S- або X-діапазон (залежно від сенсора)
- Вихідні дані: 3-D трек (азимут, дальність, висота, швидкість); сирі/ПЧ-дані (за потреби)
- Програмне забезпечення: VBRS Console для налаштування, калібрування та візуалізації

## Числові цілі (референс VBRS-40)
- Робоча дальність: ~20 км
- Діапазон висот: ~5 км
- Вертикальна база: 40 м
- Точність за висотою (ціль): ±100 м на 20 км; ±50 м на 10 км; ±25 м на 5 км
- Відносне вирівнювання за часом: ≤100 нс (тип.); опція <1 нс з White Rabbit
- Частота оновлення/ревізиту: ≥1 Гц на один 3-D трек (ціль)
- Затримка формування треку (ціль): ≤500 мс від останнього відбиття до 3-D оновлення
- Відхилення вершини щогли під вітровим навантаженням: ≤5 см (пік)
- Діапазони: S або X (залежно від сенсора), налаштовано під ЕПР класу Shahed-136
- Залежність від GNSS: відсутня (опора на атомний годинник)

## Що це таке
Повністю готова до використання система — сенсори, блок синхронізації та таймінгу, інтеграція живлення та зв’язку, крайовий процесор і інтерфейс — яка використовує вертикальну базу для відновлення висоти за даними спарених 2-D радарів.

## Опції
- Синхронізація White Rabbit (<1 нс)
- Синхронізаційна інфраструктура PTPv2 (з апаратними мітками часу)
- Набір розробника (лабораторія/POC) або Польова система (до розгортання)

## Сфери застосування
Протидія БпЛА (наприклад, клас Shahed-136), заповнення прогалин повітряної обстановки, безпека полігонів, моніторинг периметра повітряного простору.

VBRS-40 = еталонна конфігурація з вертикальною базою 40 м.
*VBRS-40 = еталонна конфігурація з вертикальною базою 40 м.*

