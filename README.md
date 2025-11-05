<img width="258" alt="image" src="https://github.com/user-attachments/assets/f155da63-79d0-42f8-b600-c99c956a502c" />

<Heartie></br>
User Manual


First Year Hardware Project</br>
School of ICT</br>
Metropolia University of Applied Sciences</br>
14.3.2025 </br>


			
  	  	  
 
Contents
1	Introduction	1</br>
Glossary	1</br>
2	Getting Started	2</br>
Hardware Assembly	2</br>
3	Using the Device	3</br>
3.1	How does Heartie work	3</br>
3.2	How to Interpret the Results	4</br>
4	Troubleshooting	6</br>
5	Additional information	6</br>
5.1	Contact Information	6</br>
5.2	Technical Specification	7</br>
5.3	Feedback form	7</br>
5.4	Self-Repairing	7</br>
5.5	Device Properties	7</br>

 
1	Introduction</br>

Welcome to the user manual of “Heartie” heart rate detector. This innovative device allows users to accurately measure pulse rate and heart rate variability. Whether you're a medical professional monitoring patient health, a fitness enthusiast tracking your performance, or a researcher collecting data, this device is designed to provide reliable results in real-time. This manual will guide you through the setup process, explain how to operate Heartie, and offer solutions for common issues you might encounter.</br>

Intended Users</br>

●	Medical Professionals</br>
●	Athletes & Fitness Enthusiasts</br>
●	General Users</br>

Glossary</br>

Parameter	Unit	Description</br>
SDNN	ms	Standard deviation of NN intervals</br>
SDRR	ms	Standard deviation of RR intervals</br>
SDANN	ms	Standard deviation of the average NN intervals for each 5 min segment of a 24 h HRV recording</br>
SDNN index	ms	Mean of the standard deviations of all the NN intervals for each 5 min segment of a 24 h HRV recording</br>
pNN50	%	Percentage of successive RR intervals that differ by more than 50 ms</br>
HR Max – HR Min	bpm	Average difference between the highest and lowest heart rates during each respiratory cycle</br>
RMSSD	ms	Root mean square of successive RR interval differences</br>
HRV triangular index		Integral of the density of the RR interval histogram divided by its height</br>
TINN	ms	Baseline width of the RR interval histogram</br>

2	Getting Started</br>

Hardware Assembly</br>
To get Raspberry Pi Pico and Pulse Sensor up and running, follow these steps:</br>
1.	Connect the sensor's wires properly: The red wire goes to the 3.3V power pin, the black wire to ground (GND), and the yellow wire to the signal pin on the Raspberry Pi Pico.</br>
2.	Secure the setup: Place the Raspberry Pi Pico on a breadboard to keep the connections stable and organized.</br>
3.	Establish the power source: Connect the Raspberry Pi Pico to computer via a USB cable. This will provide both power and allow data transfer.</br>

●	Powering On: Connect the Raspberry Pi Pico to the USB cable, which will automatically power on the device and start the pulse monitoring script.</br>
●	Place the finger on the sensor: Allow the optical detector to pick up your pulse.</br>
●	Monitor the data: Watch the OLED display for continuous updates.</br>
●	Powering Off: Disconnect the USB cable to turn off the device.</br>
●	Ensure stability: Place the device on a steady surface to avoid external interference.</br>

<img width="369" alt="image" src="https://github.com/user-attachments/assets/f1905e92-65dc-480c-b9a4-3a623d0d6da7" /></br>


3	Using the Device</br>

Your pulse and heart rate are two different ways to track your heart’s activity. Your heart rate is how many times your heart beats per minute. Your pulse rate is how many times per minute your arteries expand because of your heart beating. There’s usually no difference between your heart rate and your pulse rate (or the difference is very small). </br>

3.1	How does Heartie work</br>

Optical (photoplethysmography): Heartie uses infrared light to see the expansion of your arteries as your heart pumps blood through them. Heartie tracks your pulse rate, and some can also estimate the oxygen levels in your blood. It also measures and displays other metrics, like heart rate variability.</br>

 <img width="386" alt="image" src="https://github.com/user-attachments/assets/32c96148-35c8-43c0-8bb3-912647b68c54" />

 
  

3.2	How to Interpret the Results</br>
Heartie displays your heart rate in beats per minute (BPM).</br>
●	Normal Resting Heart Rate: A normal resting heart rate for adults typically ranges from 50 - 70 BPM.</br>

<img width="376" alt="image" src="https://github.com/user-attachments/assets/7ce5cd1a-8290-4649-909d-5cf73dbb041c" /></br>

 
 
●	Heart Rate Zones: Heartie displays different heart rate zones: recovery/easy, aerobic/base, tempo, lactate threshold, anaerobic. Each zone indicates a different level of intensity.</br>

<img width="444" alt="image" src="https://github.com/user-attachments/assets/ff90801d-8e47-46b7-850c-9c74bdb00a3f" /></br>

 
●	Abnormal Readings: If you consistently observe readings outside the normal range, or experience any discomfort, consult your doctor.</br>

<img width="425" alt="image" src="https://github.com/user-attachments/assets/3feaec7b-1655-408d-85fb-66c01e0e960e" /></br>


  Additional Tips:</br>
●	Cleaning: Clean the device regularly with a soft cloth. </br>
●	Accuracy: The accuracy of the readings may vary depending on factors such as skin contact, body position, and movement.</br>
●	Storage: Store the device in a cool, dry place.</br>

  Safety Precautions</br>
●	Do not use the device while operating machinery or driving.</br>
●	Do not immerse the device in water.</br>
●	Avoid direct sunlight on the sensor. This can interfere with the readings</br>
●	Use in a stable environment. Avoid excessive hand movement for accurate readings.</br>
●	This device is not a medical device and should not be used to diagnose or treat medical conditions. Consult a healthcare professional for any health concerns.</br>

4	Troubleshooting</br>

1.	Inconsistent Readings: Keep your finger still on the sensor and ensure proper positioning.</br>
2.	No power or data transfer: Verify that the USB cable is properly connected to the Raspberry Pi Pico and the computer. Check for any loose wiring on the breadboard.</br>
3.	Signal pin issues: Ensure the yellow signal wire is correctly connected to the designated pin on the Raspberry Pi Pico.</br>

5	Additional information</br>

5.1	Contact Information</br>
Email address: customerservice.group1@metropolia.fi</br>
mobile: +358457410000</br>
visit at Karaportti 2, 02610 Espoo,Finland</br>

5.2	Technical Specification</br>
         Memory Capacity: 4GB,</br>
         Screen Resolution:128×64,
         Maximum Power: 15.3W USB-C Power Supply,</br>
         Wi-Fi Frequency: 2.4GHz Wi-Fi</br>
	 
5.3	Feedback form</br>
We are happy to hear your feedback:</br>
https://docs.google.com/forms/d/e/1FAIpQLScT6i8O6Pr-r1IqVbxTfe_lokrmwKqh5-csxHVobN3QdUATFQ/viewform?usp=dialog</br>

5.4	Self-Repairing</br>
1.    Choose platform: Install MicroPython.</br>
2.    Get the right libraries: Download the necessary libraries for pulse detection and OLED display management.</br>
3.    Upload the script: Using an IDE like Thonny, upload the pulse monitoring script to the Raspberry Pi Pico.</br>
4. Click “run current script”</br>

5.5	Device Properties</br>
Raspberry Pi 4 Model B(4GB version): 2.4 GHz and 5.0 GHz IEEE 802.11ac</br>
wireless, Bluetooth 5.0, BLE Gigabit Ethernet, 2 USB 3.0 ports, 2 USB 2.0</br>
ports, 2 × micro-HDMI® ports (up to 4kp60 supported), Micro-SD card slot.For detailed technical information visit: Raspberry Pi 4 Model B specifications.</br>

Raspberry Pi Pico W: Dimensions 15 cm × 10 cm × 5 cm, Weight: 350g,</br>
Wireless (802.11n), single-band (2.4 GHz), Bluetooth 5.2. For detailed technical information, please visit: Raspberry Pi Pico W datasheet</br>


---


