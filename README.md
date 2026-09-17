
**R8500RC - Ultimate ICOM R8500 remote control**

A Python/Tkinter desktop app for remote-controlling the Icom IC-R8500 communication receiver over CI-V (serial).

![Main GUI](https://github.com/aneitzel/r8500rc/blob/main/R8500rc_gui1.jpg?raw=true)

### Features

- ****Frequency display**** with clickable/scrollable digit steppers, mouse wheel support, and a keypad for direct entry

- ****S-Meter**** Smooth Meter in different styles: Analog, Bar, and Tube with dBm/S-value readout

- ****MEMO scan**** with real time name lookup

- ****Mode, Step, ATT, AGC, Bank, and Memory Slot**** selectors, with memory channel names shown live

- ****Memory Write (MW) / Memory Clear (MC)**** — write the current settings to any memory slot, or erase one, directly from the main window

- ****Program Scan**** with a live results table, CSV export, and "most active" sorting

![Program scan](https://github.com/aneitzel/r8500rc/blob/main/R8500rc_gui3.jpg?raw=true)

- ****Spectrum Sweep**** with a bar/line graph and click-to-tune
  
![Spectrum Sweep](https://github.com/aneitzel/r8500rc/blob/main/R8500rc_gui2.jpg?raw=true)


Latest Download: https://github.com/aneitzel/r8500rc/releases

### Requirements

- Python 3.9+
- [`pyserial`](https://pypi.org/project/pyserial/)
- serial connection or adapter connected to the R8500

You can change the "Frequency Display FONT" in Settings. There is a nice free LCD-like Font available under https://www.dafont.com/digital-7.font. Simply install the Font TTF-file, restart R8500RC and choose "Digital-7 Mono"

### Author
André Neitzel, HB9INA
