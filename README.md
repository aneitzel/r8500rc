
A Python/Tkinter desktop app for remote-controlling the **Icom IC-R8500**
communications receiver over CI-V (serial).




## Features

- **Frequency display** with clickable/scrollable digit steppers, mouse
  wheel support, and a keypad for direct entry
- **S-Meter** in three styles: Analog, Bar, and Tube (double-click to
  cycle), with dBm/S-value readout
- **Mode, Step, ATT, AGC, Bank, and Memory Slot** selectors, with memory
  channel names shown live
- **Memory Write (MW) / Memory Clear (MC)** — write the current settings
  to any memory slot, or erase one, directly from the main window
- **Skip-CH** — mark/unmark memory channels to be skipped during a
  MEMO scan
- **MEMO scan** with squelch-based channel name lookup and a fast
  blinking "SCAN" indicator
- **Program Scan** with a live results table (frequency, signal, time,
  hit count), CSV export, and "most active" sorting
- **Spectrum Sweep** with a bar/line graph and click-to-tune
- Persistent settings (port, levels, window positions, etc.) across
  restarts

## Requirements

- Python 3.9+
- [`pyserial`](https://pypi.org/project/pyserial/)
- A USB-to-CI-V (serial) adapter connected to the R8500

```bash
pip3 install pyserial
```

## Usage

```bash
python3 r8500rc.py
```

On the radio, set **CI-V Address = 0x4A** and **CI-V Baud Rate = 19200**
(the factory defaults), then choose your serial port in the app and
click **Connect**.

See [`installation_guide.md`](installation_guide.md) for full setup
instructions, including how to install the optional "Digital-7 Mono"
LCD-style font for the frequency display.

## Notes on Program Scan

Program Scan writes the two edge frequencies into the radio's special
"PROG" memory bank and starts the scan via CI-V. Changing the start/stop
frequency, tuning step, mode, or ATT while a scan is running restarts it
from the lower edge — this is a characteristic of the radio itself.

## License

*(add a license of your choice, e.g. MIT — see [choosealicense.com](https://choosealicense.com/))*

## Author

André Neitzel, HB9INA
