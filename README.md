[![Telegram](https://img.shields.io/badge/join-telegram-blue.svg?style=for-the-badge)](https://t.me/+W4rVVa0_VLEzYmI0)
 [![WhatsApp](https://img.shields.io/badge/join-whatsapp-green.svg?style=for-the-badge)](https://chat.whatsapp.com/FkNC7u83kuy2QRA5sqjBVg) 
 [![Donate](https://img.shields.io/badge/donate-$-brown.svg?style=for-the-badge)](http://paypal.me/mtpsilva)
 [![Say Thanks](https://img.shields.io/badge/Say%20Thanks-!-yellow.svg?style=for-the-badge)](https://saythanks.io/to/mtpsilva)
![](https://img.shields.io/github/last-commit/aeonSolutions/-openScienceResearch-12bit-LCD-1.69-TFT-Smart-DAQ-Device-with-unique-data-fingerprint?style=for-the-badge)
<a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/lbp3wclsex7ya7ravspl" alt="trackgit-views" />
</a>
![](https://views.whatilearened.today/views/github/aeonSolutions/-openScienceResearch-12bit-LCD-1.69-TFT-Smart-DAQ-Device-with-unique-data-fingerprint.svg)

[PCB-Prototyping-Catalogue](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue)  >>  [Smart DAQ](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Smart%20DAQ)  >> [16-bit Smart DAQs](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/Smart%20DAQ/16-bit/readme.md)  >>  16-bit Smart DAQ Device with unique data fingerprint and a 1.69" TFT LCD  45x55 ABS

<br>

# Revision "10-2023" of the 16-bit Smart DAQ Device with unique data fingerprint and a 1.69" TFT LCD 45x55 ABS
This is the repository for revision "10-2023" of the 16-bit Smart DAQ Device with a unique data fingerprint able to do experimental data upload to any data repository. This specific hardware electronics utilizes the ADC IC AD5693 from Analog Devices. More information about this ADC IC [here](https://www.analog.com/en/products/ad5693.html). 

<br>

**Status:** Fully working

<br>

**Known Issues** <br>
- PCB copper track optimizations
- components rearrangement for optimization of PCB track inductance 

<br>
<br>

<p align="center">
  <img height=300 src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/Design/smartAsphaltSample.jpeg" >
</p>

The photo above is one of the many specimens I purposely fabricated to research self-sensing properties of asphalt mixed with a known content of carbon fibers. This is a 10cm cylinder specimen and on the top is already setup my own design smart #DAQ (get it here on my GitHub ) with the ability to upload LIVE experimental data to a #dataverse.

In the photo above the smart DAQ is installed on an acrylic case and screwed with plastic screws to an acrylic base with the same cross-section area as the specimen to be tested. 
The acrylic base can be bought [here](https://s.click.aliexpress.com/e/_DEGsZaL). And the acrylic case [here](https://s.click.aliexpress.com/e/_Dmudkjt). 

<br>

## Dataverse API C library

This device uses my C++ library to expedite dataverse API integration on smart DAQ devices or elsewhere. Follow the link to its repository:

https://github.com/aeonSolutions/OpenScience-Dataverse-API-C-library

<p align="center">
<a href="https://github.com/aeonSolutions/OpenScience-Dataverse-API-C-library"> 
    <img src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/dataverse_r_project.png" width="30%">
</a> 
</p>

<br>
<br>

### Smart PCB Hardware Specifications
The hardware specifications for this 16-bit pcb with dimensions of 23.5x43.5mm can be found [here](https://github.com/aeonSolutions/openScience-Smart-DAQ-to-Upload-Live-Experimental-Data-to-a-Data-Repository/wiki/16‐bit-Smart-DAQ-Hardware-revision-"10‐2023").

<br>
<br>

 **In real life this smart DAQ is able to:**
- connect to all kinds of 3V to 5V Digital sensors;
- connect to all kinds of sensors compatible with the I2C protocol. (max 118 sensors simultaneously)
- measure voltage in the range of  [0;3.3V]
- measure electrical resistance [0; 10^6] Ohm 
- do temperature and humidity compensation on all measurements 
- has a voltage reference sensor for improved accuracy on ADC measurements  
- has a motion sensor to know if anyone moved a specimen during an experiment
- ability to show live experimental data on the 1.69-inch TFT IPS LCD  

<br>
<br>

## PCB circuit Schematic 
The PCB circuit schematic is available in PDF located in the folder "PCB Schematic"
<br>

## PCB design files
The PCB gerber files are located in the folder "gerber" and are ready to order online at any PCB fabrication store. (PCBWay, AllPCB, Eurocircuits, etc)
<br>
<br>

<p align="center">
    <img src="https://github.com/aeonSolutions/openScience-Smart-DAQ-to-Upload-Live-Experimental-Data-to-a-Data-Repository/raw/main/media/revision_10_2023_16bit.png" width="400px">
</p>


<br>
<br>

## Proof of Concept

To test and validate proposed smart DAQ PCB electronics and its firmware as a solution for LIVE experimental data measurements on any test specimen part of a experimental campaign, This PCB electronics is being used to measure a predefined set of variables/parameters to further study several asphalt mixtures with known carbon fiber weight content in the asphalt matrix. Below is a YouTube link to an unedited short video showing one of the experimental setups.

[![](https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/Design/youtube.png)](https://youtu.be/eOA1JPgop0k)


<br />
<br />
<br />

______________________________________________________________________________________________________________________________
### License
2022 Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International

https://creativecommons.org/licenses/by-nc-sa/4.0/

______________________________________________________________________________________________________________________________

<br />
<br />

### Be supportive of my dedication and work towards technology education and buy me a cup of coffee
Buy me a cup of coffee, a slice of pizza or a book to help me study, eat and think new PCB design files.

[<img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" data-canonical-src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="70" />](https://www.buymeacoffee.com/migueltomas)

<br />
<br />

### Make a donation on Paypal
Make a donation on paypal and get a TAX refund*.

[![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/paypal_small.png)](http://paypal.me/mtpsilva)


### Support all these open hardware projects and become a patreon  
Liked any of my PCB KiCad Designs? Help and Support my open work to all by becomming a LDAD Patreon.
In return I will give a free PCB design in KiCad to all patreon supporters. To learn more go to patreon.com. Link below.

[![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/patreon_small.png)](https://www.patreon.com/ldad)


