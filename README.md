# KinT Blackpill Edition

![kinesis-3](https://user-images.githubusercontent.com/800930/186173690-8d34ccd0-7eec-4b3d-93a0-488730113e12.jpg)

This is a fork of Michael Stapelberg's [KinT project](https://github.com/kinx-project/kint) with the following modifications:

* Replaced Teensy with STM32F411 Blackpill controller (`blackpill` directory)
* Reduced PCB size to 100 x 86 mm
* Use Vial firmware.  Source code is in my [fork of Vial](https://github.com/dcpedit/vial-qmk/tree/vial/keyboards/dcpedit/kint_bp)

## Parts for Build
| Component              | Qty | Notes |
| ---------              | --- | ----- |
| SMD LEDs               | 4   | Can be any color [Link](https://octopart.com/apt3216qbc%2Fd-kingbright-5355642?r=sp)
| SMD 10k resistors      | 4   | [Link](https://octopart.com/crcw120610k0fkeac-vishay-20811529)
| Molex 13 pin connectors| 4-6 | Needed if you don't want to desolder old ones [Link](https://octopart.com/39-53-2135-molex-7670149?r=sp)
| STM32F411 Blackpill    | 1   | Search on Aliexpress.com
| Panel mount USB-C      | 1   | [Link](https://www.amazon.com/dp/B075R7QBQD)
| Laser cut USB plate    | 1   | AI file [Link](https://github.com/dcpedit/kinesismod/blob/master/model/acrylic_plate.ai)
| Socketed headers       |     | Only needed if you want to socket your Blackpill.
