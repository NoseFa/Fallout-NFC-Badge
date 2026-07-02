# Fallout NFC badge

An NFC badge made for Hack Club Fallout. This project was done on the first full day of Hack Club Fallout as a PCB sprint project. We had around like 7-8h from start to finish. The badge was made to fit the holders / landyards given to us at the event. The badge includes an nfc tag and a whitescreen with a QR code to the fallout home page and a code to my github profile on the back side. I will probably program the nfc tag to forward to the photo site so I can quickly give people access to it. This was also one of my first KiCad projects with PCBA components so it's pretty bare bones and simple. 

![Front side](./media/Front.png)

Front side with the NFC tag area, Fallout logo, soup (Fallout's mascot) and a QR code to the Fallout page.

![Back side](./media/Back.png)

Back side with the Hack Club flag and QR code to my GitHub

## The PCB files

I made this project in KiCad and got it manufactured by JLCPCB as a PCBA. When ordering keep in mind that the antenna might be listed as a part but it doesn't need to be placed so when it gives an error for the antenna not having a part mapped to it in the BOM thats normal. You can find the manufacturing files in [kicad/jlcpcb/production_files](./jlcpcb/production_files/). It includes the gerbers and the BOM.