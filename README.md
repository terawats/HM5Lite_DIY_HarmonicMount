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

# Assembly photo gallery
![IMG_5305](https://github.com/user-attachments/assets/cf66d1df-9a24-4490-a37f-5105a52c8664)
![IMG_5304](https://github.com/user-attachments/assets/dea4a42f-bb5d-4622-8863-1b0d270f2275)
![IMG_5306](https://github.com/user-attachments/assets/d6858f2d-9e0f-4a9f-b283-5fad669c032e)
![IMG_5331](https://github.com/user-attachments/assets/c5394548-464f-4523-aa6c-7f3c71de75e8)
![IMG_5332](https://github.com/user-attachments/assets/aed6f023-2b80-4bfb-bb2c-9b96b49616fd)
![IMG_5318](https://github.com/user-attachments/assets/8db817a9-dc9e-4558-8cca-94e55a6e43cc)
![IMG_5665](https://github.com/user-attachments/assets/e66f340f-2363-4277-b031-9b4f3b7eabc2)
![IMG_5682](https://github.com/user-attachments/assets/a4a1c260-79a1-499f-8627-07059ca28f66)
![IMG_5333](https://github.com/user-attachments/assets/86ca395a-5204-402f-a698-e1b253e41807)
![IMG_5714](https://github.com/user-attachments/assets/945b3583-8bb5-4b20-97dc-aacd8f2ea378)
![IMG_5736](https://github.com/user-attachments/assets/eb04dc37-9273-46f0-b09d-21a6d7584e4a)
![IMG_5753](https://github.com/user-attachments/assets/d7e7f3a3-cd73-4062-8f71-a5440733182c)
![IMG_5754](https://github.com/user-attachments/assets/b5ed8a3d-5fbd-464a-aac8-ef18c7cc71cc)
![IMG_5755](https://github.com/user-attachments/assets/2f6c315a-faa5-4b45-91ee-d7939e9ad1bd)
![IMG_5756](https://github.com/user-attachments/assets/29809fec-7602-43f1-ae8e-abd066f1cd5b)
![IMG_5757](https://github.com/user-attachments/assets/a9eecd0d-d91b-44b3-b7ae-44a5726ab18b)
![IMG_5759](https://github.com/user-attachments/assets/d6568071-89af-4ceb-9e0d-f7738f517d14)
![IMG_5760](https://github.com/user-attachments/assets/783dccc8-6a7b-47bb-af94-24fe6c320b12)
![IMG_5761](https://github.com/user-attachments/assets/7293c582-844d-4177-88d6-5280838e04e2)
![IMG_5761](https://github.com/user-attachments/assets/56c0f681-4620-472d-b1bc-339e6e6153ec)
![IMG_5763](https://github.com/user-attachments/assets/6dae1850-a766-437a-84d2-abaca364c8b4)
![IMG_5768](https://github.com/user-attachments/assets/61ff3aaa-48dd-4b6e-8517-41a7b4ebd2d6)
![IMG_6452](https://github.com/user-attachments/assets/c4a4cb58-8781-48a4-a1f9-6911e7ce4d78)

### Custom OnStepX for HM5Lite 
Custom OnStepX version v10.24c and config for HM5Lite [download link](https://github.com/terawats/HM5Lite_DIY_HarmonicMount/releases)
Plaese download file name "Custom_OnStepX_for_HM5Lite.zip"
