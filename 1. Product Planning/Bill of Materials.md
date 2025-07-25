1. 1x Adafruit BNO-055: https://learn.adafruit.com/adafruit-bno055-absolute-orientation-sensor/overview
<img width="1024" height="788" alt="image" src="https://github.com/user-attachments/assets/a4cd592a-0b53-46ad-b18a-3cb61c00ac1a" />

Allows for 9 DOF orientation and acceleration vectoring with on board sensor fusion of a MEMS accelerometer, magnetometer, and gyroscope. Serves as an affordable all in one solution to real time orientation tracking. Will be very useful for odometry when integrated with on board camera and ML algorithm.

2. 2x OV9732 Camera Module with USB: https://www.amazon.com/Yosoo-Health-Gear-Interface-Support/dp/B0CYCFD4V5/ref=sr_1_11?crid=2W0BYTPXINX59&dib=eyJ2IjoiMSJ9.wQzHC-cuOzMf9uDiyl8yPS1JM0elW73aYjJxTQ3d3PcxyfhjqDWhNTkqkFv_gAShbArRg5p07EXX34TaW-AFz6QtvyYSUOZmjpZaxIaq8TNQFPySMa2pOIfAYCaSLipNm5cBkG67b_QsjHg66CBo-TnKDQLqNEQ3eA2Z2nWyzk2OikkcLq4o9iC9l38WveXcJzHc7tdPAwHr-1UTcsWBYYRVkLbc_5GBH7WhlQtsvxE.xW0yoomxcxXdX2y0bIH2HlwcCrlA2q0PJauGqwo9ywI&dib_tag=se&keywords=usb+camera+module&qid=1752436924&sprefix=usb+camera+module%2Caps%2C159&sr=8-11)
   <img width="679" height="539" alt="image" src="https://github.com/user-attachments/assets/83180f34-d0e4-4463-8330-a2e0c030ae56" />

  Will be used for visual odometry as well as object detection. USB output selected to interface with VIM4 sbc.

4. Khadas VIM3 SBC: https://www.khadas.com/vim3
<img width="1946" height="1946" alt="image" src="https://github.com/user-attachments/assets/715fce1c-001d-496b-83ca-41a2ead68322" />

  This project will use the Khadas Vim3 as it controller, as this provides enough processing power to run on board visual odometry, with two USB ports for the cameras, I2S protocol for the speaker, is a more compact solution then the raspberry pi with a carrier board, and is more affordable.

6. MAX98357A: https://www.adafruit.com/product/3006
<img width="600" height="484" alt="image" src="https://github.com/user-attachments/assets/d1bb7d3e-b441-498d-98a1-6cf1ea984911" />

  I2S Amplifier for audio output.

8. Fielect 2Pcs 0.5W 8 Ohm DIY Magnetic Speaker: https://www.amazon.com/Fielect-Magnet-Speaker-Internal-Diameter/dp/B0826YLV6C/ref=sr_1_9?crid=2YKFGVT59O28D&dib=eyJ2IjoiMSJ9._jwWRYyLqmJvC0y6iQ52vaLveazD_bEkyfA63dfBdQ4F1__woU0HbKyxgrIfZa8EOxisd5PxCxHjazSYKltAGnuNdHi4e1EvdfpcE2q4b47rFrt-NNpi8qj-Ts5RFQ6HburDLGfAcvhoxaKALlP6MAD_VpfmZKye8mciefVlUN8epfK9m1_vzIpCPg6B64HLuAstSXKWhSHyPA5DXVBBrnledgQTuUuoT2AvVjvPQhE.V2IwI9hfcjF6WbptXFC9rDyguYHIHtyu4yyiaWRDInw&dib_tag=se&keywords=small%2Bspeaker%2Bfor%2Barduino&qid=1752439047&sprefix=small%2Bspeaker%2Bfor%2Barduino%2Caps%2C160&sr=8-9&th=1
 <img width="1251" height="954" alt="image" src="https://github.com/user-attachments/assets/fa46eddf-9576-4aad-a681-2b82dd05b01c" />

  Two speakers that will be used in parallel with the same I2S amplifier. Placed next ot the ear allowing for the user to hear audible directions as they walk.
