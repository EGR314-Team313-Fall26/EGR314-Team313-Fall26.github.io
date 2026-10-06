# Component Selection

This page documents the components selected for the conduit inspection device and the reasoning behind each selection.

## Microcontroller

| Component | Image | Advantages | Disadvantages | Link |
|-----------|-------|------------|---------------|------|
|      ESP32-S3-WROOM-1-N4     |    ![ESP32](../images/esp321.webp)   |    *Has Antenna attached. *plenty of GPIO * 3.3V is low power requirement.        |      Must place carefully to not interfere with antenna.         |   [Link](https://www.digikey.com/en/products/detail/espressif-systems/ESP32-S3-WROOM-1-N4/16162639) Price : $5.21  |
|     PIC18F27Q10-I/SO      |       |      Familiarity from being used in previous class, Large community library, Low Cost.     |     Requires an antenna attachment for WI-FI communication .        |   [Link](https://www.digikey.com/en/products/detail/microchip-technology/PIC18F27Q10-I-SO/10064343) Price: $1.31  |
|     ESP32-S3-WROOM-1U-N4     |       |      Same specification as ESP32-S3-WROOM-1-N4      |      No Antenna attachment for WI-FI communication.         |   [Link](https://www.digikey.com/en/products/detail/espressif-systems/ESP32-S3-WROOM-1U-N4/16162640) Price: $5.21|

## Power Regulator

| Component | Image | Advantages | Disadvantages | Link |
|-----------|-------|------------|---------------|------|
|       LM2575D2T-3.3R4G    |   ![Lm2595](../images/lm25CL.webp)    |    Can take from 5v to 40V input, Regulated 3.3V output, High efficiency of buck regulator, familiar with through hole version.        |      Lower frequency of 52-Khz is outdated.         |   [Link](https://www.digikey.com/en/products/detail/onsemi/LM2575D2T-3-3R4G/1476688)  Price: $2.23 |
|   LM2595S-3.3        |   ![Component Image](../images/lmmodern.jpg)    |     Can take from 5v to 40V input,  High efficiency of buck regulator 15-Khz       |    Lower inventory will need to keep an eye on.           |  [Link](https://www.digikey.com/en/products/detail/umw/LM2595S-3-3/24889929) Price: $1.44   |
|    MIC4721YMM-TR       |   ![Component Image](../images/mic.jpg)    |    Low price, High frequency 3.3-Mhz,1.5ma current will take care of our sensors.        |        will have to calculate need inductor and capacitor for our required voltage, only 5.5V input.       |   [Link](https://www.digikey.com/en/products/detail/microchip-technology/MIC4721YMM-TR/1640308) Price: $0.88   |

## Motor Driver 

| Component | Image | Advantages | Disadvantages | Link |
|-----------|-------|------------|---------------|------|
|           |       |            |               |      |
|           |       |            |               |      |
|           |       |            |               |      |

## Distance Sensor 

| Component | Image | Advantages | Disadvantages | Link |
|-----------|-------|------------|---------------|------|
|           |       |            |               |      |
|           |       |            |               |      |
|           |       |            |               |      |

## Sensor #2

| Component | Image | Advantages | Disadvantages | Link |
|-----------|-------|------------|---------------|------|
|           |       |            |               |      |
|           |       |            |               |      |
|           |       |            |               |      |
