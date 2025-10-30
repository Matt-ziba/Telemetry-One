## **Telemetry One** keyboard
*This is my submission for the second round of the HackPad YSWS event.*

#### Description:

The **Telemetry One** is a 75%, hot-swappable keyboard with an included accessory port (meant for a display but can be used for any I2C accessory :D ). 

#### Design goal:

The main goal wasn´t exactly to make something extremely original, just to make something that I think I would like using - a compact, easily modifiable (hot-swappable) keyboard with an accessory port. I think I succeeded in that. While the design could be way better, i´m still quite happy with it, as it is my first time making a larger keyboard.

#### Parts description:

The PCB itself is pretty decent, it also took the longest :D. The overall design isn´t too complex but I took my time really polishing it. I´m sure that I´ll find lots of flaws in it during assembly or during usage, but that´s just part of the process!

The case is pretty bare bones, but that is intentional. Instead of a full fledged case, I wanted something that could easily be mounted in different "sleeves" depending on the desired look. I have yet to model the "sleeve" designs I have in mind, but I do have a couple of ideas for them. The assembly of the case is pretty simple, with screws going from the bottom through the entirety of the case into the top part, which will have embedded nuts.

The firmware is absolute dogwater, that´s unfortunately not intentional :D. Yeah to be honest I procrastinated on the firmware until the last day and had to write it while hungover with not enough time to do proper research. I will definitely rewrite it once the keyboard actually arrives, as that will make debugging way easier. Currently it´s some weird ahh code that should probably work, but I honestly have no clue. 



## PCB Screenshots

![Schematic Screenshot](https://hc-cdn.hel1.your-objectstorage.com/s/v3/8606ffc5d3b71add5b74d8276a71e425fcad2469_schematic_telemetry-one_2025-03-23.png)
![PCB Screenshot](https://hc-cdn.hel1.your-objectstorage.com/s/v3/abf148292ebd2d5235615d70e712fcb228d957bf_pcb_pcb_telemetry-one_0.96-2025-03-23.png)
![PCB-3D Screnshot](https://hc-cdn.hel1.your-objectstorage.com/s/v3/96f16a1badb6166a47ab76a20113734bba9d5b03_image.png)
![PCB-3D Screnshot](https://hc-cdn.hel1.your-objectstorage.com/s/v3/baa7fcb84ed8f8d9ff2235192dc0af89dce81ecb_image.png)

## Case Screenshots

![Case Screenshot](https://hc-cdn.hel1.your-objectstorage.com/s/v3/a7934ac4f17744844d096650c5ef1e4783f2b6f5_image.png)
![Case Layers Screenshot](https://hc-cdn.hel1.your-objectstorage.com/s/v3/eaa2e37b30fe8209a7ec79f82412e20b49397071_image.png)
![Case Bottom Screenshot](https://hc-cdn.hel1.your-objectstorage.com/s/v3/3da96ce598d08c6fad1beae4e0e0f762dc1531d2_image.png)
![Case Top Part Screenshot](https://hc-cdn.hel1.your-objectstorage.com/s/v3/757867e6f043dea7e1247b13883f6d6ffe2ae52c_image.png)

## BILL OF MATERIALS
| Item                           | Quantity                 | Price                               | Link                                                                          |
|--------------------------------|--------------------------|-------------------------------------|-------------------------------------------------------------------------------|
| Akko V3 Creamy Blue Pro Switch | 1x 90pcs pack            | 18USD (0.2USD per piece)            | https://en.akkogear.com/product/akko-v3-cream-blue-pro-switch-45pcs/          |
| Kailh Hotswap sockets          | 2x 50pcs pack            | 16USD (0.16USD per piece)           | https://splitkb.com/products/kailh-hotswap-sockets                            |
| TX AP stabilizers              | 1x pack                  | 23USD (3USD over budget paid by me) | https://divinikey.com/products/tx-ap-stabilizers-rev-4                        |
| Keycap Set from Aliexpress     | 1x set                   | 22USD                               | https://www.aliexpress.com/item/1005007393936770.html                         |
| L1N4148 Diodes from LCSC       | 2x 50pcs                 | 1.3USD (0.013USD per piece)         | https://lcsc.com/product-detail/Switching-Diodes_LRC-L1N4148FT1G_C132821.html |
| 0.91" Display from LCSC        | 1x                       | 2.3USD                              | https://lcsc.com/product-detail/OLED-Display_HS-HS91L02W2C01_C5248081.html    |
| PCB                            | 1x (JLCPCB 5pcs minimum) | <20USD                              | N/A                                                                           |
| Orpheus Pico board             | 1x                       | N/A                                 | N/A                                                                           |

Materials cost in total: Around **84USD** (not including the cost of the PCB, so closer to about **90USD**)

I do not need the 3D printed parts, as I have access to a 3D printer and thus I don´t want to waste HackClub resources by requesting the parts when I can print them myself.  
I also don´t need fasteners, as I intentionally designed the keyboard around fasteners which I have at home.

