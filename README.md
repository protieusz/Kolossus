# Kolossus
Kolossus, a unisplit angled Katana layout with a 25mm trackball and a Panasonic roller encoder remixed from clops pcb designed by [calvin-mcd](https://github.com/calvin-mcd/clops). KLE by noelle (deer) and HA HA HA.

# Description
"clops is a qazlike unibody split sub40s keyboard. The KLE and firmware is by ha ha ha which itself is inspired by a KLE from Noelle. PCB is designed by Calvin0563." Copied from Calvin's GitHub linked above. 
Kolossus is a heavy remix of clops by adding a full case to the PCB that was made from scratch using EasyEDA by extracting vital files from the Calvin0563's clops PCB files. Initially the name was Colossus but changed to Kolossus via HA HA HA's suggestion to give it a more stylist name.
Here are the list of modifications:

-Center encoder is now a 25mm trackball powered by PMW3360 sensor.

-Full enclosure case with 4 RGB cut outs.

-5mm integrated switch plate to the top case.

-Use M2 brass hot inserts 3.2mm diameter and 4mm length for the M2 screws to secure the case. I forgot how long is my M2 screws are but they should be greater than 10mm so estimated around 14.6mm. Play around with and buy multiple M2 lenght screws.

-PCB is powered by [RP2040 Zero Super Mini](https://www.aliexpress.com/item/1005007292787135.html?spm=a2g0o.order_list.order_list_main.11.46301802CibF9u) where the bottom of the mcu is flush and can sit on top of the Excelsior PCB with no issues.

-For diodes, I decided to try out the BAV70 so that I solder less diodes since this pcb is not sponsored. I would only need to solder on 17 diodes instead of 34

-QMK code is borrowed from aki27 bally and modified the matrix to fit my Excelsior. No suppport will be given since I just copy and paste.

-Below the trackball is the optional Panasonic EVQ roller encoder or a MX switch. Case cut out was done to acoomodate the Panasonic encoder.

-Stabilizers cutout was made but was not sure about the dimensions since I have never used stabs before so a STEP case file will be included so you can cut the stab cut out further if needed. I am playing to build mine without any stabs. As always print at your own risk. No support will be given.

# Disclaimer (Also copied from Calvin0563's GitHub page)

Please note that this project is a work in progress with no guarantees of a working outcome. No-one involved in this project is responsible for any usage issues that may arise. However, feel free to edit, modify and otherwise utilise these files.

# Render

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
