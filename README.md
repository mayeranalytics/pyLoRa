# pyLoRa

It turns out the HopeRF has a family of LoRa capable transceiver chips [RFM92/95/96/98](http://www.hoperf.com/rf/lora/)
that have identical or almost identical SPI interface as the Semtech [SX127x family](http://www.hoperf.com/rf/lora/).

The [pySX127x](https://github.com/mayeranalytics/pySX127x) project will therefore be renamed to pyLoRa soon.


### Currently available LoRa transceiver ICs
* Semtech [SX1272/3](http://www.semtech.com/images/datasheet/sx1272.pdf) 860 MHz to 1020 MHz
* Semtech [SX1276/77/78/79](http://www.semtech.com/images/datasheet/sx1276.pdf) 137 MHz to 1020 MHz
* HopeRF [RFM95/96/97/98](http://www.hoperf.com/upload/rf/RFM95_96_97_98W.pdf) 
* Microchip [RN2483](http://ww1.microchip.com/downloads/en/DeviceDoc/50002346A.pdf)
* EM Microelectronic [EM9101](http://www.emmicroelectronic.com/products/wireless-rf/proprietary-protocols/em9101) (2.4GHz)
