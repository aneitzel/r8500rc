
**R8500RC - Ultimate ICOM R8500 remote control**

A Python/Tkinter desktop app for remote-controlling the Icom IC-R8500 communication receiver over CI-V (serial).

![Main GUI](https://github.com/aneitzel/r8500rc/blob/main/R8500rc_gui1.gif?raw=true)


MiniMode:

![MiniGUI](https://github.com/aneitzel/r8500rc/blob/main/R8500rc_gui5.jpg?raw=true)


### Features:

- ****Multi Bank Scanning**** enables R8500RC to scan multiple banks

![Multi Bank Scan](https://github.com/aneitzel/r8500rc/blob/main/R8500rc_gui4.jpg?raw=true)

- ****Frequency Display**** with clickable digit steppers (mouse wheel support and a keypad for direct entry)

- ****S-Meter**** smooth SIGNAL Meter in different styles (Analog, Bargraph, Tube with dBm-value)

- ****MEMO Scan**** with real time name lookup

- ****Memory Slot**** selectors, with memory channel names shown live

- ****Simple Memory Editor**** MemClear / MemWrite including Name directly from the main window

- ****Program Scan**** with a live results table, CSV export, and "most active" sorting
  
![Program scan](https://github.com/aneitzel/r8500rc/blob/main/R8500rc_gui3.jpg?raw=true)

- ****Spectrum Sweep**** with bar or line graph style and click-to-tune
  
![Spectrum Sweep](https://github.com/aneitzel/r8500rc/blob/main/R8500rc_gui2.jpg?raw=true)

Latest Download: https://github.com/aneitzel/r8500rc/releases

### Requirements

- python 3.9+
- [`pyserial`](https://pypi.org/project/pyserial/)
- serial connection to the IC-R8500

You can change the "Frequency Display FONT" in Settings. There is a nice free LCD-like Font available under https://www.dafont.com/digital-7.font. Simply install the Font TTF-file, restart R8500RC and choose "Digital-7 Mono".

### Author
André Neitzel, HB9INA
