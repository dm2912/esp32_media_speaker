# esp32_media_speaker
Home assistant connected media speaker using a chinese replica amazon echo device. 

No voice, purely a speaker with led's and utilising the existing button board for controls.

<img width="3000" height="4000" alt="IMG_20261122_133715" src="https://github.com/user-attachments/assets/42c71d12-0cd6-410a-98a1-6be957202db8" />

Parts:

ESP32 S3 N16R8 https://www.aliexpress.com/item/1005006418608267.html

MAX98357 Amplifier https://www.aliexpress.com/item/1005009601886478.html

Sperical design Speaker https://www.aliexpress.com/item/1005013234860983.html

WS2812B COB Ring https://www.aliexpress.com/item/1005010765963794.html

Teardown:

+ Fairly straightforward. Remove the adhesive ring from the foot of the device will reveal four screws

+ remove those four screws and then a further two screws will reveal. Remove those two and the front of the unit will start to come free. The rear of the cloth section is secured with two clips which are free'd with a pry tool. 

+ dispose of the circuit board, and the battery compartment. 

<img width="3000" height="4000" alt="IMG_20261122_134915" src="https://github.com/user-attachments/assets/a05293e3-4924-4f9d-9697-c5d727d4152e" />

+ The existing button board can be popped out and then repurposed using the wiring on the schematic

<img width="3000" height="4000" alt="IMG_20261122_143733" src="https://github.com/user-attachments/assets/e8f6a627-b4b3-4a56-9fe1-bc0085080dcf" />

+ Glue in place and then build the rest of the setup using the schematic

<img width="3000" height="4000" alt="IMG_20261122_144521" src="https://github.com/user-attachments/assets/9918a27e-3af3-4f28-9494-af0e6d5efa95" />

Schematic
---------

<img width="1536" height="1024" alt="schematic-final" src="https://github.com/user-attachments/assets/cd836055-1be5-440f-a41b-772527542b40" />

YAML
----

to follow. Flash through ESP Home as usual

