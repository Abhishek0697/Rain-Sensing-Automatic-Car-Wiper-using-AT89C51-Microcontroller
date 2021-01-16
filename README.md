# Rain Sensing Automatic Car Wiper using AT89C51 Microcontroller


### Read our paper on [arXiv](https://arxiv.org/pdf/2101.01670.pdf)


_IDEA:_

Today’s car wipers are manual systems that work on the principle of manual switching. So here we propose an automatic wiper system that automatically switches ON on detecting rain and stops when rain stops. Our project brings forward this system to automate the wiper system having no need for manual intervention. For this purpose we use rain sensor along with microcontroller to drive the wiper motor. Our system uses rain sensor to detect rain, this signal is then processed by microcontroller to take the desired action. The rain sensor works on the principle of using water for completing its circuit, so when rain falls on it it’s circuit gets completed and sends out a signal to the microcontroller. The microcontroller now processes this data and controls the motor.This system is equally useful for Aircrafts and a smaller version of this can be used  by motor bikers in their helmets so that they can drive easily in rains.


## Simulation of the design in PROTEUS software
![Simulation of the design in PROTEUS software](https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/Proteus%20Simulation%20Design.png)



## PCB Layout Design on EAGLE PCB Design Software
<img src="https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/PCB%20Layout%20on%20Eagle.jpg" alt="drawing" width="300"/>

## Etched PCB 

<img src="https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/EtchedPCB.jpg" alt="drawing" width="300"/>


## Model 
![Model](https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/Model.jpg)


We have implemented a model that senses rains and automatically switches on the wiper and adjusts its speed according to the intensity of the rain. As the intensity of the rain increases, the speed of the wiper increases to a certain level. According to our observations, the wiper takes 2.2 seconds when a drop of water falls on the sensor, while it takes only 1.4 seconds when the sensor is submerged in a glass of water. We learned how to interface servo motor with AT89C51 Microcontroller and also the rain sensor module interfacing with AT89C51 Microcontroller.


Further modifications in the circuit will lead to controlling the speed of the wiper to a more accurate sense. Currently the wiper moves at two different speeds. By modifying the code we can have different speed for different amount of rain. Also we can use this automated car wiper along with other automated features to make a Smart Car.
