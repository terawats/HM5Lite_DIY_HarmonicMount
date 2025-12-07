# HM5Lite DIY Harmonic Mount

## Introduction
  HM5 Lite is a DIY telescope tracker mount with a harmonic drive (gear). The mount weighs just 2.5 kg and supports a maximum payload capacity of 4–5 kg.
By leveraging the harmonic drive, which is strong enough to operate without the need for an additional counterweight, it offers several advantages.
It's convenient to carry and easy and quick to set up in a short time without weight balancing required.
  Software on this project are custom form [OnStepX](https://github.com/hjd1964/OnStepX) release v10.24c to support to keep telescope position on EEPROM.
EEPROM's used on this project are AT24C32 on "DS3231 AT24C32 I2C RTC module". 

## 💰 Cost and Usage
This project aims to minimize the material cost to under $180 USD.
It's affordable and easy to build (DIY) yourself. The target usage is for telescopes with a focal length not over 250 mm.
It's suitable for wide-angle photography such as the Milky Way and comets, and it's also good for deep-sky objects (DSOs).

## 🔭 Performance
With this configuration, we can achieve an RMS guiding error of 1.0" to 1.8" (arcseconds).
This is good enough for a telescope setup with a pixel scale of 3.0"–5.0"/pixel.

Examples:
RedCat51 + ASI2600MC Pro is 3.1"/pixel.
Samyang 135mm + ASI2600MC Pro is 5.7"/pixel. (Note: Changed "123mm" to the more common "135mm" focal length.)

Under these conditions, the guide error is not over 1/2 the pixel scale.

# Demo of performance

![IMG_5768](https://github.com/user-attachments/assets/5086d991-5d6e-4771-a238-5d1ff4d20d77)

### See Demo Video on YouTube by click below image
[![Watch the demo](https://github.com/user-attachments/assets/c0d167c0-5748-4e73-ae14-297063ce853b)](https://www.youtube.com/watch?v=0rcDmX7sShg)

### Auto guide test condition with platload 3kg
![IMG_6452](https://github.com/user-attachments/assets/b0fbee6d-b916-4b44-94bc-184e2d0f621f)

### See Auto Guide test result on YouTube by click below image
[![Watch the demo](https://github.com/user-attachments/assets/c301a99c-8308-4b72-b60d-4d220bc1f44c)](https://youtu.be/mmUjZQFmkEI)

# Lists of component and Estimated cost
Below is a lists of component and estimated cost. Mosly cost are form Taobao.com and Aliexpress.com
|             Items                   |                       Pictues                                                                |         Desc              |   Q'ty  |     cost   |
|-------------------------------------|----------------------------------------------------------------------------------------------|---------------------------|---------|------------|
| 1. Harmonic gear                    | ![IMG_6670](https://github.com/user-attachments/assets/650a5979-fadd-41b0-99b7-fb0081a71aba) | miniF11-100               |    x2   |    37 usd  |
| 2. Steping Motor                    | ![IMG_6671](https://github.com/user-attachments/assets/fbbb1bed-3e33-40be-830e-96f82b3b88a4) | NEMA17 42x60mm            |    x2   |     5 usd  |
| 3. Close loop servo driver          | ![IMG_5725](https://github.com/user-attachments/assets/1ab487b2-b90f-441f-8fd2-39d4aafa5768) | SERVO42(step tick)        |    x2   |     8 usd  |
| 4. NEMA17 Motor L-bracket           | ![IMG_6672](https://github.com/user-attachments/assets/5467030c-5b30-44cd-9316-dc360a1182a2) | 42mm L-Bracket            |    x2   |     1 usd  |
| 5. Latitude Adjusment wedge         | ![IMG_6673](https://github.com/user-attachments/assets/8abb0fe4-b92a-4d00-9fe4-22572a20a633) | 15kg load capacity        |    x1   |    23 usd  |
| 6. Dovetail clamp                   | ![IMG_6674](https://github.com/user-attachments/assets/ac69de41-5f3c-4fe1-a2ae-5800b45e8bd1) | Clamp for telescope       |    x1   |     6 usd  |
| 7. Wemos D1 mini ESP32              | ![IMG_6676](https://github.com/user-attachments/assets/edf3fe17-cdd3-44c3-aa31-ceecd7e8b5e6) | OnStepX MCU               |    x1   |   3.5 usd  |
| 8. Wemos D1 mini Buzzer shield      | ![IMG_6678](https://github.com/user-attachments/assets/1875b9e4-f91c-4bcc-914c-057b40e59f02) | OnStepX Buzzer            |    x1   |     1 usd  |
| 9. Wemos D1 mini Power shield       | ![IMG_6679](https://github.com/user-attachments/assets/49ba054b-deea-4a3e-b941-b1c8b24a579a) | for ESP32 power           |    x1   |     1 usd  |
| 10. DS3231 AT24C32 I2C RTC module   | ![IMG_6682](https://github.com/user-attachments/assets/ad1bbdbd-d2e6-45f2-a200-b89986fcdd77) | for OnStep RTC            |    x1   |     2 usd  |
| 11. Female USB Type-C socket        | ![IMG_6680](https://github.com/user-attachments/assets/10a76d7c-955a-4f16-b587-6c8859f78479) | for connect to PC         |    x1   |     1 usd  |
| 12. Female 2.5mm DC socket          | ![IMG_6681](https://github.com/user-attachments/assets/0b4290a5-3511-4cb1-8903-44b6e073125c) | for 12V power supply      |    x1   |     1 usd  |
| 13. 3D print parts for OnStepX      | ![OnStep](https://github.com/user-attachments/assets/4198ae02-3f72-4c2f-8411-2645bce3b446)   | file: Box_OnStepX.stl     |    -    |     5 usd  |
| 14. 3D print parts for RA cable     | ![DecCable](https://github.com/user-attachments/assets/de54ae45-1e17-4ad4-8e98-58c59e56e242) | file: Box_RA_Cable_v2.stl |    -    |     3 usd  |
| 15. Cable management tube           | ![IMG_flex](https://github.com/user-attachments/assets/9d1cef47-0003-42fe-997d-44064d8c1b9c) | for RA wiring banagement  |    -    |     1 usd  |
| 16. Screw, Nute, washer             | ![ImgScrew](https://github.com/user-attachments/assets/2f8f6fed-008d-4e8f-a73d-f9f246d29454) | for assembly              |    -    |     8 usd  |
|              Total estimation cost: |                                                                                              |                           |         |   158 usd  |

# Schemetic daiagram

![schemetic](https://github.com/user-attachments/assets/7d0326ef-a8b8-4a6b-bf32-ccd8439c4b2e)

# Assembly guide
Coming soon...


### Custom OnStepX for HM5Lite 
Custom OnStepX version v10.24c for HM5Lite [download link](https://github.com/terawats/HM5Lite_DIY_HarmonicMount/releases)
(plaese download file name "Custom_OnStepX_for_HM5Lite.zip" )
