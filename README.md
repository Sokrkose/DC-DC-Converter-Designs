# DC-DC-Converter-Designs

Here there are 2 DC-DC Converters that I designed and tested during the 2nd year of my participation in the Formula Student Team, Aristotle University Racing Team Electric - ARISTURTLE.

### 600V Input, 24V Output, 25A max current DC-DC

This is the DC-DC Converter that powers the entire Low Votage System of the car. It takes a high voltage input from the Battery Pack and gives 24V for the supply of the LV System. It consists of 2 Commercial of the shelf (COTS) DC-DCs and I designed some precharge and discharge circutry for the input and output capacitors of the topology.

![photo](Screenshots/Screenshot_16.png)
![photo](Screenshots/Screenshot_17.png)

### 600V Input, 12V Output, 200mA max current DC-DC

This is the DC-DC Converter that powers the led indicator of the Battery Pack that shows if the voltage of the Battery Pack (in the side of the vehicle) is more than 60V. It takes as input up to 600V and it gives as output a stable 12V Voltage Level. This is a Test PCB and not the final one, since the final PCB is integrated in the Fusebox PCB which is in a different repository.

![photo](Screenshots/Screenshot_18.png)
![photo](Screenshots/Screenshot_19.png)
