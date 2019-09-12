# Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller

_IDEA:_



Today’s car wipers are manual systems that work on the principle of manual switching. So here we propose an automatic wiper system that automatically switches ON on detecting rain and stops when rain stops. Our project brings forward this system to automate the wiper system having no need for manual intervention. For this purpose we use rain sensor along with microcontroller to drive the wiper motor. Our system uses rain sensor to detect rain, this signal is then processed by microcontroller to take the desired action. The rain sensor works on the principle of using water for completing its circuit, so when rain falls on it it’s circuit gets completed and sends out a signal to the microcontroller. The microcontroller now processes this data and controls the motor.This system is equally useful for Aircrafts and a smaller version of this can be used  by motor bikers in their helmets so that they can drive easily in rains.





## Pin Configuration of 8051 Microcontroller


The AT89C51 is a low-power, high-performance CMOS 8-bit microcomputer with 4K bytes of Flash programmable and erasable read only memory.  The on-chip Flash allows the program memory to be reprogrammed in-system or by a conventional non volatile memory programmer. By combining a versatile 8-bit CPU with Flash on a monolithic chip, the Atmel AT89C51 is a powerful microcomputer which provides a highly-flexible and cost-effective solution to many embedded control applications.



![Pin Configuration of 8051 Microcontroller](https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/Pin%20Configuration%20of%208051%20Microcontroller.jpg)






## Flowchart
![Flowchart](https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/Flowchart.png)


The rain sensor module is an easy tool for rain detection. It can be used as a switch when raindrop falls through the raining board and also for measuring rainfall intensity. The module features, a rain board and the control board that is separate for more convenience, power indicator LED and an adjustable sensitivity through a potentiometer. Raindrop sensor is a board coated with nickel in the form of lines. It works on the principal of ohms law. When there is no rain drop on board. Resistance is high so we gets high voltage according to V=IR. When rain drop present it reduces the resistance because water is conductor of electricity and presence of water connects nickel lines in parallel so reduced resistance and reduced voltage drop across it





## Simulation of the design in PROTEUS software
![Simulation of the design in PROTEUS software](https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/Proteus%20Simulation%20Design.png)





## PCB Layout Design on EAGLE PCB Design Software
![PCB Layout Design on EAGLE PCB Design Software](https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/PCB%20Layout%20on%20Eagle.jpg)





## Etched PCB 
![Etched PCB](https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/Etched%20PCB.jpg)





## Model 
![Model](https://github.com/Abhishek0697/Rain-Sensing-Automatic-Car-Wiper-using-AT89C51-Microcontroller/blob/master/docs/Model.jpg)


We have implemented a model that senses rains and automatically switches on the wiper and adjusts its speed according to the intensity of the rain. As the intensity of the rain increases, the speed of the wiper increases to a certain level. According to our observations, the wiper takes 2.2 seconds when a drop of water falls on the sensor, while it takes only 1.4 seconds when the sensor is submerged in a glass of water. We learned how to interface servo motor with AT89C51 Microcontroller and also the rain sensor module interfacing with AT89C51 Microcontroller.


Further modifications in the circuit will lead to controlling the speed of the wiper to a more accurate sense. Currently the wiper moves at two different speeds. By modifying the code we can have different speed for different amount of rain. Also we can use this automated car wiper along with other automated features to make a Smart Car.
