---
title: Troubleshooting common issues and possible fixes
updated: 28-05-2020
---

This page will be updated often with most common things people seem to run into so check back from time to time. In principle if you have read [this guide](/) from the begining you should be familiar with most of this issues and how to fix them and this section should act as a short summary. Most of the trouble people are having comes from an improper [setup](setup.html), general lack of knowlege about the [3D printing process](understanding-3d-printing.html) in general and understanding the role of the basic components of [your 3D printer](3d-printer-overview.html). Issues can also be caused by [slicer settings](slicer.html) that are not adapted to the model that you are trying to print.

> A good starting point is Simplify3D's [Print Quality Troubleshooting Guide](https://www.simplify3d.com/support/print-quality-troubleshooting/)

> Another excelent guide is [The Ultimate 3D Print Quality Troubleshooting Guide 2019](https://rigid.ink/pages/ultimate-troubleshooting-guide)

## Can't connect to the printer from a PC software

If you can't connect to the printer from a PC software like [Pronterface](https://www.pronterface.com/) there could be one of the following issues:
- You are using the wrong baudrate, printer is set to work at **250000**, or wrong serial port
- You did not install the [CH341 serial driver](http://www.wch-ic.com/downloads/CH341SER_EXE.html)
- Other software (like Cura or Slicer) is using the serial port and you need to close it 
- The USB cable is bad and you need to replace it

## Prints not sticking to the bed

- See [bed care](tips.html#bed-care) first and make sure your bed is clean.
- Keep in mind the temperature you set is not the actual temperature at the bed's surface and the further you go in the direction of the bed's edges the colder it gets.
- Increase your bed temperature by 5C and try again.
- Let the bed preheat 5-10 minutes before starting to print if your print is close to the edges of the bed.
- PETG in my experience likes a hot bed and I print it around 90-95C. Funny enough the ABS I tried was sticking fine at 80C.

## Prints not releasing (sticking too hard)

This is usually an isue with PLA, but I have experienced it with ABS also.

- **Always let the bed cool down to room temperature** (about 24C) before removing your prints - this will take some time due to the insulation below it so be patient.
- You can use an ice bag to speed the cooling process (make sure it does not leak).
- Spray some IPA around the base of the print and let it soak in for 2-3 min and try removing the print again.
- If all else fails, use a spatula, but be careful not to scratch the bed too much.

## Extruder making funny noises

If the extruder motor is making cracking noises or if it's not rotatating and just twitching in place you should:
- Make sure the [ribon cable is inserted properly](setup.html#screws-and-connections) in the extruder block.
- Make sure your nozzle is heated to the temperature suited to your filament, in case of doubt increse temp a bit. I usually start in the middle of the temp range recomended by the filament's manufacturer and go from there based on observations of the first few prints.
- Adjust the [extruder idler lever tension](setup.html#extruder-screw-pressure)
- You might have a clogged nozzle, either do a [cold pull](setup.html#check-extrusion) or replace it
- It is also possible that there is something wrong with the driver for the extruder motor, you can try to swap it with a driver from another axis but it's better to [contact support](https://desk.zoho.com/portal/evnovo/home)


> More topics soon(tm)


## Contact support

If all else fails ...

> [Artillery Sidewinder Owners Facebook group](https://www.facebook.com/groups/artilleryswx1/) - Lots of friendly and helpful people

> [Artillery Genius Owners Facebook group](https://www.facebook.com/groups/artillerygenius/) - Lots of friendly and helpful people

> [Artillery support portal](https://desk.zoho.com/portal/evnovo/home) - here you can open a ticket and discuss your issue directly with Artillery support team. They are very helpful and helped people with lots of issues, especially on the hardware side where parts were broken. 

> [Artillery website](https://artillery3d.com/) - Still a work in progress

> [Artillery github](https://github.com/artillery3d) - Firmware source code

