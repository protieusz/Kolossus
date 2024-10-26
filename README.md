# Kolossus
Kolossus, a unisplit angled Katana layout with a 25mm trackball and a Panasonic roller encoder remixed from clops pcb designed by [calvin-mcd](https://github.com/calvin-mcd/clops). KLE by noelle (deer) and HA HA HA.

# PCBWay Sponsorship
The Kolossus PCB was sponsored by ![PCBWay](https://github.com/user-attachments/assets/82c17f69-5ef3-4789-b983-2240ba9ae99a). Thank you PCBWay! For all your PCB prototype prints and PCBA needs you can count on PCBWay. Easy and worry free service. You submit your gerber, BOM and placement files via their website. Enter the PCB dimensions and the quantity of the prints and select the recommend shipping service, for me it is the DHL Express (DTP) for hassle free delivery.  All customs paid for. PCBWay will email you component placement clear detailed pictures for validation before soldering the rest of the PCBs.

# Description
Kolossus "...is a qazlike unibody split sub40s keyboard. The KLE and firmware is by ha ha ha which itself is inspired by a KLE from Noelle. PCB is designed by Calvin0563." Copied from Calvin's GitHub linked above. 
Kolossus is a heavy remix of clops by adding a full case to the PCB that was made from scratch using EasyEDA by extracting vital files from the Calvin0563's clops PCB files. Initially the name was Colossus but changed to Kolossus via HA HA HA's suggestion to give it a more stylist name.
Here are the list of modifications:

-Center encoder is now a 25mm trackball powered by PMW3360 sensor.

-Full enclosure case with 4 RGB cut outs.

-5mm integrated switch plate to the top case.

-Use M2 brass hot inserts 3.2mm diameter and 4mm length for the M2 screws to secure the case. I forgot how long is my M2 screws are but they should be greater than 10mm so estimated around 14.6mm. Play around with and buy multiple M2 lenght screws.

-PCB is powered by [RP2040 Zero Super Mini](https://www.aliexpress.com/item/1005007292787135.html?spm=a2g0o.order_list.order_list_main.11.46301802CibF9u) where the bottom of the mcu is flush and can sit on top of the Excelsior PCB with no issues.

-For diodes, I decided to try out the BAV70 so that I solder less diodes. I would only need to solder on 17 diodes instead of 34

-QMK code is borrowed from aki27 bally and modified the matrix to fit my Kolossus. No suppport will be given since I just copy and paste.

-Below the trackball is the optional Panasonic EVQ roller encoder or a MX switch. Case cut out was done to acoomodate the Panasonic encoder.

-Stabilizers cutout was made but was not sure about the dimensions since I have never used stabs before so a STEP case file will be included so you can cut the stab cut out further if needed. I am planning to build mine without any stabs. As always print at your own risk. No support will be given.

-Case usb c opening will be adjusted in the future to accommodate the wider USB C magnetic port.

-New full case variant designs will be printed soon. Stay tuned.

-Full production build on Oct 22, 2024.

-For Encoder soldering, the MCU will need to be soldered a little bit to the left so that there is a little bit more space for the tiny GPIO pads to be exposed for surgical soldering. The pads are tiny so I suggest a ribbon cable type cables to be use. I have not solder build the pcb with roller encoder yet. I am currently still waiting for 2x RP2040 Super mini mcus to arrive from Aliexpress.

# Disclaimer (Also copied from Calvin0563's GitHub page)

Please note that this project is a work in progress with no guarantees of a working outcome. No-one involved in this project is responsible for any usage issues that may arise. However, feel free to edit, modify and otherwise utilise these files.

# Full Production Build

Zaku Case Oct 25, 2024
![IMG_3302](https://github.com/user-attachments/assets/0c1c5401-5f9c-49b8-9815-b108e9138a87)
![IMG_3301](https://github.com/user-attachments/assets/6d5d1873-649e-4ed1-9888-ae11212a8626)
![IMG_3298](https://github.com/user-attachments/assets/eb3bdd59-c924-4e5b-bb42-9405790eefa4)

![Uploading IMG_3299.JPG…]()
[IMG_3283](https://github.com/user-attachments/assets/3be696b9-bb7d-40f8-96e7-5dc84e3f6a7e)
![IMG_3288](https://github.com/user-attachments/assets/78abf4ae-5e4e-4c46-be71-286528e8b317)
![IMG_3287](https://github.com/user-attachments/assets/6e5900a5-a889-4af5-9cb0-5b8d3b9116c3)
![IMG_3286](https://github.com/user-attachments/assets/104d5df0-f0b0-4753-805d-cb4869411ab2)
![IMG_3282](https://github.com/user-attachments/assets/806d52be-7d97-47f5-8774-409f689d8fdd)
![IMG_3281](https://github.com/user-attachments/assets/3fd039f1-9d1e-4d6b-950c-bd304288762d)
![IMG_3280](https://github.com/user-attachments/assets/73e5aea5-ff6a-437b-81bf-cb1e72c92992)
![IMG_3279](https://github.com/user-attachments/assets/693ed9c2-74b1-4997-be5f-45229ae0b119)
![IMG_3278](https://github.com/user-attachments/assets/2e98fa68-82f6-4c3a-9291-2229addc862f)
![IMG_3276](https://github.com/user-attachments/assets/5df39593-bca7-4796-a2e1-d424a1bbe3cb)
![IMG_3275](https://github.com/user-attachments/assets/6dbc614c-f5f5-46d3-a7a1-8da27c97f580)
![IMG_3274](https://github.com/user-attachments/assets/2d97fc04-2dca-4435-aa81-4c9a1c6440f9)
![IMG_3273](https://github.com/user-attachments/assets/c027ec71-1175-4a85-adc2-ad134f2ec437)
![IMG_3272](https://github.com/user-attachments/assets/60196f04-d786-42a7-a3f1-38aba194dba2)
![IMG_3271](https://github.com/user-attachments/assets/d5542efb-9f8e-436e-8d28-3aac3ffd7739)
![IMG_3262](https://github.com/user-attachments/assets/3b112dba-d578-40dd-b02c-b05f65bfff65)
![IMG_3261](https://github.com/user-attachments/assets/f94ccb80-a357-44f8-bf01-ca7f09a836b5)
![IMG_3260](https://github.com/user-attachments/assets/16fbd354-9b1e-48a3-b5a0-28e2c9eb3e9a)
![IMG_3259](https://github.com/user-attachments/assets/dc117e9e-7233-47c5-86fa-a490f610a728)
![IMG_3258](https://github.com/user-attachments/assets/e8259cd6-9102-471a-8ef2-7b4c04785153)
![IMG_3257](https://github.com/user-attachments/assets/8790cc30-7a2c-4515-88c7-b51d4618e30b)
![IMG_3256](https://github.com/user-attachments/assets/1945b63c-dcb0-4a7c-b7fa-fcbe7d74c68d)
![IMG_3249](https://github.com/user-attachments/assets/ed447333-ef91-47b2-8749-d9cf46168b0f)
![IMG_3248](https://github.com/user-attachments/assets/1c051693-02d6-4aff-aeab-eda9e63afc56)
![IMG_3247](https://github.com/user-attachments/assets/0058cbf1-7aca-4dfe-86b7-7a9f50d4d573)
![IMG_3246](https://github.com/user-attachments/assets/3c933d22-055b-4361-8b6a-14fe9cbd09d4)
![IMG_3252](https://github.com/user-attachments/assets/2b23ef68-ef57-43e7-856e-d5813e7e4134)
![IMG_3251](https://github.com/user-attachments/assets/b0d8ec24-1efd-4a61-8be2-f80e039e2d97)
![IMG_3250](https://github.com/user-attachments/assets/4e005074-72ca-4f83-85eb-190772bd12b8)

# Render
![Screenshot 2024-09-26 at 8 04 03 AM](https://github.com/user-attachments/assets/ec9a115b-db2f-4f9d-aaca-1e2756ef8144)
![Screenshot 2024-09-26 at 8 04 16 AM](https://github.com/user-attachments/assets/a66406fb-8bb5-4d51-b947-68c3928154cf)
![Screenshot 2024-09-26 at 8 04 31 AM](https://github.com/user-attachments/assets/b12fa8b9-c00d-4159-8198-a1d57cd70bc3)
![Screenshot 2024-09-26 at 8 04 43 AM](https://github.com/user-attachments/assets/b26e6164-c2a6-4206-9b74-686d91a84068)
![Screenshot 2024-09-20 at 4 23 53 PM](https://github.com/user-attachments/assets/885f3d1f-4e60-45b8-9c4d-4102d6f56934)
![Screenshot 2024-09-20 at 4 23 34 PM](https://github.com/user-attachments/assets/66ec3739-0fcd-4242-8f99-9efc096cbd50)
![Screenshot 2024-09-20 at 4 19 32 PM](https://github.com/user-attachments/assets/8ad193bf-0be0-4417-a7e1-6aa376014497)
![Screenshot 2024-09-20 at 4 18 53 PM](https://github.com/user-attachments/assets/fdf5051f-7a88-42b9-a33c-4a7afa523c7c)
![Screenshot 2024-09-20 at 4 24 03 PM](https://github.com/user-attachments/assets/13861782-6918-46dc-8afe-3d4bab1e12d7)
![Screenshot 2024-09-20 at 10 55 51 AM](https://github.com/user-attachments/assets/f3c19e19-df7e-4781-992a-0562fea57d62)
![Screenshot 2024-09-20 at 10 55 34 AM](https://github.com/user-attachments/assets/b39d9842-5438-4a45-beaf-51534ed828f2)
![Screenshot 2024-09-20 at 10 55 24 AM](https://github.com/user-attachments/assets/60d1f5ef-b335-486c-8c3c-ea18dfa9211a)
![Screenshot 2024-09-20 at 1 13 23 PM](https://github.com/user-attachments/assets/4ae10bff-4a1a-4c67-b848-74d610c482b9)
![Screenshot 2024-09-20 at 1 34 12 AM](https://github.com/user-attachments/assets/e85a7f86-9a11-4ed2-a616-1b1eb7451701)
![Screenshot 2024-09-19 at 9 18 57 PM](https://github.com/user-attachments/assets/3dbb3735-79c6-433b-84cb-c371d4bd6e93)
![Screenshot 2024-09-19 at 9 19 31 PM](https://github.com/user-attachments/assets/f5515c14-5962-40bd-bf02-358b85a50d98)
