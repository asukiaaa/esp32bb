# esp-wroom-32-break
A kicad project for ESP-WROOM-32 module.

# Modification plan
I plan to change design of this board for the following points.

- Put mosfets for toggling bood mode automatically.
- etc..

# Components
Boutght them from [akizukidenshi](http://akizukidenshi.com/catalog/top.aspx).

- [esp-wroop-32](http://akizukidenshi.com/catalog/g/gM-11647/)
- [FT232RQ](http://akizukidenshi.com/catalog/g/gI-04365/)
- [NJU7223DL1: 3.3V 500mA Regurator](http://akizukidenshi.com/catalog/g/gI-03705/)
- [Hirose-microB-USB](http://akizukidenshi.com/catalog/g/gC-05254/)
- [Diode](http://akizukidenshi.com/catalog/g/gI-05951/)
- [transistor MMBT3904](http://akizukidenshi.com/catalog/g/gI-05969/)
- [Hirose-microSD-holder](http://akizukidenshi.com/catalog/g/gC-02395/)
- [switch SKRPACE010](http://akizukidenshi.com/catalog/g/gP-06185/)
- [10uf condensor](http://akizukidenshi.com/catalog/g/gP-07768/)
- [0.1uf condensor](http://akizukidenshi.com/catalog/g/gP-04940/)
- [10k registor](http://akizukidenshi.com/catalog/g/gR-06103/)

# Footprints
- [ESP32-kiCAD-Footprints](https://github.com/adamjvr/ESP32-kiCAD-Footprints)
- [FT232RQ: KiCadLib](https://github.com/upverter/schematic-file-converter/blob/master/upconvert/library/kicad/parts/ftdi4.lib)
- [NJU7223DL1: KiCadLib](https://github.com/hirakuni45/RX/blob/master/rx63t_chager/KiCAD/akizuki.lib)
- [Hirose-microB-USB: KiCadMod](https://github.com/lab11/kicad/blob/master/parts/pcb/lab11-connectors.pretty/USB_MICRO_B-HIROSE-ZX62R-B-5P.kicad_mod)
- [SKRPACE010.kicad_mod](https://github.com/nosuz/kicad-lib/blob/master/module.pretty/SKRPACE010.kicad_mod)

# License
MIT

# References
- [esp_wroom_32_datasheet_en.pdf](https://espressif.com/sites/default/files/documentation/esp_wroom_32_datasheet_en.pdf)
- [Enginursday: First Impressions of the ESP32](https://www.sparkfun.com/news/2017)
- [ESP32 Development Board with TELEC Memorial photograph](https://macsbug.wordpress.com/2016/12/12/esp32-development-board-with-telec-memorial-photograph/)
- [DS_FT232R](http://www.ftdichip.com/Support/Documents/DataSheets/ICs/DS_FT232R.pdf)
- [SparkFun FTDI Basic Breakout - 3.3V](https://www.sparkfun.com/products/9873)
- [Sehematic of SparkFun FTDI Basic Breakout - 3.3V](http://cdn.sparkfun.com/datasheets/BreakoutBoards/FTDI%20Basic-v22-3.3V.pdf)
- [esp32-thing.sch](https://cdn.sparkfun.com/assets/learn_tutorials/5/0/7/esp32-thing-schematic.pdf)
