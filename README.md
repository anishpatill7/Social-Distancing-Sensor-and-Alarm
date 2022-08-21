<h1 align="center">Social Distancing Sensor and Alarm</h1>
<h1 align="center">Semester IV Mini Project 2021</h1>

<h3 align="left">Introduction:</h3>
<h4 align="left"> A motion detector is an electrical device that utilizes a sensor to detect nearby motion. Such a device is often integrated as a component of a system that automatically performs a task or alerts a user of motion in an area. <br>
They form a vital component of security, automated lighting control, home control, energy efficiency, and other useful systems.<br>
Passive infrared (PIR) sensors are sensitive to a person's skin temperature through emitted black-body radiation at mid-infrared wavelengths, in contrast to background objects at room temperature. <br>
No energy is emitted from the sensor, thus the name passive infrared. This distinguishes it from the electric eye in which the crossing of a person or vehicle interrupts a visible or infrared beam. <br>
These devices can detect objects, people, or animals by picking up one’s temperature.<br></h4>

<h3 align="left">Components:</h3>
<h4 align="left"> 
1.Timer IC 555	<br>
2.CapacitorC1 10pF, 10uF <br>
3.ResistorR1   1kΩ, 22kΩ, 100kΩ <br>
4.LED <br>
5.Battery <br>
6.PIR Sensor <br>
7.Buzzer (PIEZO) <br>
8.Connecting Wires <br>
9.Multimeter <br></h4>

<h3 align="left">Block Diagram:</h3>

<h3 align="left">Working:</h3>
<h4 align="left">The IC 555 is used in the monostable mode with frequency dependent on the values of resistors R2, R3 and C2. The values of R2 = 100KΩ, R3 = 22KΩ and C2 = 10µF.
When the PIR Sensor detects any human body movement, its output pin becomes HIGH (Vcc) and when it does not detect any human body movement, its output pin becomes LOW (Ground). 
When anyone passes in front of the sensor, then the sensor provides high output voltage. In this condition, the NE555 Timer IC trigger (Pin 2) is connected to the ground and gets LOW (Ground) trigger pulse. So, the Timer IC Provides output voltage through (Pin 3), which goes to the PIR.
This happens only when the object is in the detection range of PIR sensor. We have connected a simple Buzzer and a led  to the output of the PIR sensor.
The different type of PIR lenses are used based on the range of detection, area and temperature. The infrared rays are scattered by the phenomenon called Fresnel effect.</h4>

<h3 align="left">Applications:</h3>
<h4 align="left"> PIR sensors can be used in high security areas like Bank vaults, Museum, Art galleries.
Motion detectors are the primary choice for security purposes in households, industries, and commercial establishments. 
They are also deployed to enhance the customer experience of gadgets, in the medicinal field for Bio-monitoring and Bio-chemical detection in patients.
Motion sensors can be used in the storage vaults to protect the valuable items.
They can also be used as an automatic door bell circuit that rings the bell when a person is detected.
This can be used as a defense application to detect objects in war fields.</h4>


<h3 align="left">Outcome:</h3>
<h4 align="left"> In conclusion, a dedicated motion detector on your network adds a valuable layer of security.
A Motion detector quickly and silently asks for aid and offers the user a better sense of security. 
Motion detector systems are a solution you can count on in any crisis.
A Motion detector guarantees the protection of both life and property.
While a number of technologies for motion detection exist, including ultrasonic and microwave radiation sensors, the PIR sensor is popular for its ease-of-setup and high performance.
In addition, PIR sensors are inexpensive and a valuable security solution.</h4>

<h4 align="center">Thank You!</h4> 
