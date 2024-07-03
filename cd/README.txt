*This is the Readme file for the project Home security alert system using IOT*

----INTRODUCTION----
In this project, a low-power consumption home security alarm system is developed by applying wireless sensor network (WSN),global system for mobile communication (GSM) technology using Arduino Software.

----REQUIREMENTS----
1.Software
    Arduino IDE
2.Hardware
    GSM Module
 	Arduino board
	Fire sensor
	MQ2 sensor
	PIR sensor
	LED lights
    Bread board
	Jumper Wires

----INSTALLATION----
First download and install the Arduino for Mac, Linux or Windows from the official website "https://www.arduino.cc/en/Main/Software".Windows users also need to install a driver.

----CONFIGURATION----
Step 1: Open the Arduino IDE and go to tools ,From the tools set the board of arduino to Arduino UNO.
Step 2: Now open the tools and set port to COM3 or COM4 so that the arduino UNO gets connencted.
Step 3: Include all the libraries required for GSM Module such as SoftwareSerial

----CONNECTIONS----
Make the connections (of all the sensors,GSM module,Arduino)as per the circuit diagram

----CODING----
Step 1:Open the sketch File and Copy the source code.
Step 2:Click on Verify which is at the top left corner ,it verifies the code and checks for the errors.Status and errors in the code are shown at the bottom in the text console.
Step 3:Once the verify button is clicked the text console shows the status with progress of compiling.
Step 4:Once the compiling is done without any errors then Done Compiling is shown in the status bar with the number of bytes of dynamic memory used for the global variables.
Step 5:Dumped the code into the Arduino UNO through the cable that is connected to the hardware setup so that is acts as the programming instructions to receiving and detecting the signals.
 
*Once the power is supplied to the GSM module and Arduino Board the Home security alert system starts working*
  