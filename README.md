# RUL_estimation_Induction_Motor
This repository contains the details of the project Remaining Useful Lifetime Estimation of Ball Bearing of Induction Motor.
Open sourced [PRONOSTIA Bearing dataset](https://paperswithcode.com/dataset/pronostia-bearing-dataset) is used to train the model. The features are extracted and selected using PCA and Fine-Gaussian SVM model is trained to predict the remaining useful lifetime of the ball bearings of the induction motor with 85.8% accuracy.
## Methodology
![image](https://github.com/user-attachments/assets/67e42972-4838-4fc7-b7c9-050eedf0abc2)

## The confusion matrix

![image](https://github.com/user-attachments/assets/d8f694a1-8513-4460-97df-5f92b091b5f5)

The model is also tested on the inhouse data acquired by us.The experimental setup to acquire the vibration signals from the bearings of the induction motor is shown below.This includes the rotating machine, the acceleration sensor and the storage device.
![image](https://github.com/user-attachments/assets/64cd8475-bce6-4ed7-85bf-ee5caa9edccb)
The accelerator is placed on the flat surface of the induction motor due to its rectangular shape to measure the vibration signals. The motor is run at 1400 rpm on no load. The code is written in Arduino IDE and is uploaded in the arduino board for interfacing. The vibration data is stored in excel sheet using PLX-DAQ.
### ADXL335 : It is a 3-axis acceleration measurement system.
![image](https://github.com/user-attachments/assets/99782eba-e4e8-4390-a9ce-166f0a05fc79)
Arduino Uno
![image](https://github.com/user-attachments/assets/bf88fec5-a6c3-467a-a2ca-14262707b339)

### Interfacing ADXL335 with Arduino UNO
![image](https://github.com/user-attachments/assets/1f878dd3-3a35-4f65-b49e-99c5f8269be9)





