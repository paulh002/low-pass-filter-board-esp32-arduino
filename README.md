# low-pass-filter-board-esp32-arduino
Lowpass filter board managed by ESP32

Low pass filter for RF amp managed by ESP32 VFO or RF Amp / SWR meter (also ESP32).
I use the same PCB as the VFO as controler but do not install the VFO components like si5351. The LPF can be direct managed from VFO software or stand alone with SWR / RFAMP software, from Loftur Jonasson, TF3LJ / VE2LJX (PSWR_T software). I made an adaption of this software for ESP32 and Adafruit 2.8 display. But I am not completly happy with it. Because it uses fixed spaced fonts which are not available in adafruit library. But for now it works with some GUI bugs which I still need to fix.
![VFO](https://github.com/paulh002/low-pass-filter-board-esp32-arduino/blob/master/lpf1.jpg)
