# FINDING THE DISTANCE USING ULTRASONIC SENSOR

# INTRODUCTION
The rearview camera in the car helps us to see the area behind the car when we are backing up.it often provides more visibility behind the car than the view we get by turning our head.but often some cars does not have rearview camera and even some of the rearview cameras stops working due to the accidents, enviromental and different landscape of the india. The rearview cameras may not be affordable for everyone to replace it quite often. In this case the distance finder helps the driver to know the distance between the car and the object. The distance finder calcultes the distance using the ultrasonic sensor and displays it on the lcd which is placed near the driver. to avoid more accidents two or three ultrasonic sensors can be used.

An ultrasonic sensor that is able to measure the distance from the ground of selected points of a motor vehicle. The sensor is based on the measurement of the time of flight of an ultrasonic pulse, which is reflected by the ground. A constrained optimization technique is employed to obtain reflected pulses that are easily detectable by means of a threshold comparator. Such a technique, which takes thefrequency response of the ultrasonic transducers into account,allows a sub-wavelength detection to be obtained. Experimentaltests, performed with a 40 kHz piezoelectric-transducer basedsensor, showed a standard uncertainty of 1 mm at rest or at lowspeeds; the sensor still works at speeds of up to 30 m/s, althoughat higher uncertainty. The sensor is composed of only low costcomponents, thus being apt for first car equipment in many cases,and is able to self-adapt to different conditions in order to give thebest results.

# FEATURES 
* Indicates distance
* Avoids accidents during parking
* Ensures car and human safety
* Doesn't require driver to check the distance manually

## HIGH LEVEL REQUIREMENTS
* Alarm system to make driver more conscious.
* Light indication to know accurate distance.
* To avoid accidents by maintaining distance.

## LOW LEVEL REQUIREMENTS
* To avoid accidents by maintaing distance.

# COMPONENTS

# Ultrasonic Sensor

An ultrasonic sensor is an instrument that measures the distance to an object using ultrasonic sound waves. An ultrasonic sensor uses a transducer to send and receive ultrasonic pulses that relay back information about an object's proximity.Ultrasonic Module HC-SR04 works on the principle of SONAR and RADAR system.HC-SR-04 module has an ultrasonic transmitter, receiver, and control circuit on a single board.The module has only 4 pins, Vcc, Gnd, Trig, and Echo.

![Micro bit lesson — Using the Ultrasonic Module « osoyoo com - Google Chrome 23-Apr-2022 18_46_14](https://user-images.githubusercontent.com/101447824/164896383-a700ed2c-561a-4959-bf2a-c72ab5e0d7f2.png)


# AVR Microcontroller(ATMEGA328)

ATmega328 is an Advanced Virtual RISC (AVR) microcontroller. It supports 8-bit data processing. ATmega-328 has 32KB internal flash memory.

ATmega328 has 1KB Electrically Erasable Programmable Read-Only Memory (EEPROM). This property shows if the electric supply supplied to the micro-controller is removed, even then it can store the data and can provide results after providing it with the electric supply. Moreover, ATmega-328 has 2KB Static Random Access Memory (SRAM). Other characteristics will be explained later. ATmega 328 has several different features which make it the most popular device in today’s market. These features consist of advanced RISC architecture, good performance, low power consumption, real timer counter having separate oscillator, 6 PWM pins, programmable Serial USART, programming lock for software security, throughput up to 20 MIPS etc. Further details about ATmega 328 will be given later in this section.

![Micro bit lesson — Using the Ultrasonic Module « osoyoo com - Google Chrome 23-Apr-2022 18_47_31](https://user-images.githubusercontent.com/101447824/164896402-5be4ba5b-dafd-4a24-b940-529d8c967be3.png)


# LCD Display

LCD (Liquid Crystal Display) is a type of flat panel display which uses liquid crystals in its primary form of operation. LEDs have a large and varying set of use cases for consumers and businesses, as they can be commonly found in smartphones, televisions, computer monitors and instrument panels.

![Micro bit lesson — Using the Ultrasonic Module « osoyoo com - Google Chrome 23-Apr-2022 18_48_35](https://user-images.githubusercontent.com/101447824/164896412-55495cd6-8cc3-43a5-9267-6c5562eb0509.png)

## BLOCK DIAGRAM

![PICUUUU - PowerPoint 22-Apr-2022 17_51_34](https://user-images.githubusercontent.com/101447824/164715449-33ade9a4-aa5e-49d4-883f-8e2be7838785.png)

## CIRCUIT DIAGRAM
![Distance Measurement by Ultrasonic Sensor and AVR Microcontroller_ Project - Google Chrome 22-Apr-2022 18_15_41](https://user-images.githubusercontent.com/101447824/164720023-a1f81ae5-6da9-44d4-a441-aa87a7681a68.png)

## CIRCUIT CONNECTION
![SimulIDE-0 4 15-SR9  -  proj1 simu 22-Apr-2022 18_50_32](https://user-images.githubusercontent.com/101447824/164729573-b0458d59-b821-4117-9e66-d9f22983b924.png)


# HIGH LEVEL TEST PLAN

| **Test ID** | **Description**                                              | **Actual Output** | **Expected Output** |   
|-------------|--------------------------------------------------------------|--------------------|-----------------|
|  HL01      | Turn ON the Buzzer when the object is too close |   Not Implemented | Turn ON buzzer |
|  HL02      | Turn ON the led when the object is too close |  Not Implemented |Turn ON led  |
|  HL03      | Display the distance on LCD | Not Implemented | Displays Distance |

# LOW LEVEL TEST PLAN
| **Test ID** | **Description**                                              | **Actual Output** | **Expected Output** |   
|-------------|--------------------------------------------------------------|--------------------|-----------------|
|  LL01     | Display the distance on LCD | Displays Distance | Displays Distance |


## TIMING DIAGRAM
![Distance Measurement by Ultrasonic Sensor and AVR Microcontroller_ Project - Google Chrome 22-Apr-2022 18_16_09](https://user-images.githubusercontent.com/101447824/164720030-dba6bf1e-f35c-49fd-a449-beae5ba4f897.png)

# FUTURE SCOPE
This is a very economic technology and can be used in several other fields as well, few are listed as below:

* Can be used as parking assistance systems in vehicles withhigh power ultrasonic transmitter.
* Can be used as burglar alarm with suitable additional software for homes and offices.
* Can be a used in liquid level measurement.
* Can be used to find breakdowns in wires or threads

# CONCLUSION
The importance of the project is calculating accurate distance from any obstacle that we want to measure. The device can be used in many different fields and categories like distance calculation in construction field, robots, car sensor to avoid obstacles and many other applications. The building process of the device was based on using as much as possible from the courses taken in the university, like Micro Processor, Basic Electronics Engineering, Multimedia and systems and Electronics Devices and also practical work in the laboratories.
