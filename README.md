# CapstoneProject_EliasJayQuinn

&nbsp;

## Table of Contents
* [Planning](#Planning)
* [Schedule](#Schedule)
* [Week Summary](#Week_Summary)

## Planning  

### Materials 

#### Bought

 - Synchronous Motor - 38$
 - Voltage regulator x3 - 3$ 
 - One-way voltage diode x3 - 5$
 - Rechargeable 5V Battery - 10-20$

#### From the Lab

 - 3D printed parts 
 - Pico+circuitry
 - PVC piping
 - Wood

### Requirements 

#### Essential

- Generate energy starting at wind speeds of 5 mph
- Average 10 Watts of energy production per hour
- Constant stream of power to an outlet  
- Firm base that does not require groundwork 
- Fits within 100 cubic feet
- Built with cheap, sustainable materials

#### Non-Essential

- Easily collapsible/can be transported easily
- Able to mount on rooftops to better use wind and not take up space
- Aesthetically pleasing design - Won’t look incredibly out of place in the park


## Schedule

### Weeks 1 - 4

Planning and Research - We will brainstorm possible designs, find our customer, and establish goals. Research needed materials and decide on our method to create each design part. Research wind speeds and park locations.

### Weeks 4 - 8 

Prototyping - We will create a quick, scaled-down version of the project to serve as a proof of concept. Possibly make multiple prototypes.

Initial Development - Begin CAD design of the parts we will 3-D print or laser cut. Create pseudo code and order the needed parts.

### Weeks 10 - 16 

Assembly - Assemble the wind turbine at CHS and do initial testing to ensure everything works.

### Weeks 16 - 20

Testing - Test at CHS and make any changes to the code or design we need. Collect data on energy production. Optimization.

### Weeks 20 - 22

Iterate - Place wind turbine in Greenleaf Park and collect data. Create a presentation for the UVA link lab.

## Week_Summary 

### Week 1 - Oct 29 - Nov 4 - 

This week we researched and ordered our charge controller. This device will assist with the circuitry by allowing us to monitor and control the voltage being produced by the system. 

[Charge Controller](https://www.amazon.com/Renogy-Wanderer-Amp-12V-24V/dp/B07NPDWZJ7?th=1)

We also communicated with our mentor, Zack Landsman, and got one of his mass-produced small-scale wind turbine. We assembled this wind turbine and once the charge controller arrives will begin to produce energy and finalize our circuitry which we will implement after creating our large-scale turbine. 

<img src="Images/WIN_20231108_09_21_16_Pro.jpg" width="400" height="300" />

We realized that connecting the turbine blades to the motor would be more challenging than we thought. We have a couple of options from Zack, and Jay is also working on one in OnShape. Once we settle on a blade design, we can make a decision that will best match our design.

Next week when the charge controller comes we will use the miniature turbine to work on the circuitry. Until it comes, we will work on designing the wind turbine blades and attachment.  

### Week 4 - November 27 - December 1st - 

This week we 3D-designed an alternative wind turbine blade design to the one given to us by Zack. We used a Savonius design which will hopefully be more effective than the current Darreius design. Next week we are planning on printing the alternative design and then testing the power output at identical wind speeds. We also tested the power output of our current DC motor at different rpm using the INA260 Arduino module and a multimeter.
The results are as follows - 
|RPM  |Voltage|Current|Resistance|Power Output|
|-----|-------|-------|----------|------------|
|68.97|.33    |.015   |220       |.000495     |
|150  |.64    |.0029  |220       |.00186      |
|261  |1.24   |.00563 |220       |.00699      |

Here is the CAD for the alternative design - 

<img src="Images/1.PNG" width="400" height="300" />

<img src="Images/2.PNG" width="400" height="300" />

### Week 5 - December 4th - December 8th

This week we finalized our design for the prototype blade system and submitted it to be 3d printed. This included designing a motor mount, which for this first version we used the same mount as was on the blades Zach gave us. One problem we ran it to was the 3d printers only having an 8in x 8in bed. Since our design was larger than that area, we would have to either downsize it or print it in multiple pieces and bolt them together. We chose to just downsize it to reduce print time, and because this was just a simple first prototype and our goal is to test the blade design rather than completely maximize the power generated. After talking with Zach today he said he is going to bring in a fan for us on Monday that we can use to test the blades.

We used the INA260 Arduino module to test voltage, current, and power outputs from our current motor. Using a drill we were able to test the max production values for the current dc motor. Next week we will use the module and a fan to test Zach's design as well as our own at constant wind speeds. This testing will help us make decisions going forward on blade design. Next week in addition to testing we will start researching and planning our base design.   

Final Re-sized CAD design: 

<img src="https://github.com/ezell38/CapstoneProject_EliasJayQuinn/blob/880b19cef6553e5d3af76dc2e8be2389367e9cdc/Images/topV3.PNG" width="400" />

<img src="https://github.com/ezell38/CapstoneProject_EliasJayQuinn/blob/880b19cef6553e5d3af76dc2e8be2389367e9cdc/Images/bottomV3.PNG" width="400" />

Max Values for Motor from Zach - 

|Voltage   |Current  |Power Output|
|----------|---------|------------|
|1252.50 mV|481.25 mA|630.00 mW   |
|1107.50 mV|473.75 mA|520.00 mW   |
|1513.75 mV|396.25 mA|560.00 mW   |

### Week 6 - December 11th - December 15th

This week we 3-D printed our top and bottom part but when mirroring the bottom piece off of the top we failed to reverse it, leading to the parts not fitting. This is a valuable lesson going forward: parts should always be put into an assembly before being printed. Once the parts were correctly printed, we constructed our prototype. We used dowel rods and the flimsy plastic sheets in the back of the classroom, each cut to 4 inches in height, to combine the top and bottom and create the wings. We then used a hot glue gun to secure it all in place. It is incredibly sturdy and I think the method with two dowel rods as additional support will be helpful in our next, more finalized design. 

<img src="Images/project1.jpg" width="400" height="300" />

<img src="Images/project2.jpg" width="400" height="300" />

<img src="Images/project3.jpg" width="400" height="300" />

<img src="Images/project4.jpg" width="400" height="300" />

In the upcoming weeks, we will test our design vs Zach's to determine which design is more efficient.

### Week 7/8 - January 22 - January 25 

These past two weeks we received the charge controller which allowed us to start producing and exporting energy through multiple ports and measuring the voltage/current more efficiently. 




