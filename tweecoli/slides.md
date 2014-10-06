#Bridging the Gap:
##Synthetic Biology $\leftrightarrow$ Electronics
_Ryan Silva_



##Why is this relevant to us?
### Biology is good at stuff
- Adapting
- Surviving
- Sensing
- Producing
- Hiding
- Self-Powered!
- $\mu$m and nm Scale


### Digital Electronics\* are good at stuff
##### \* ex. Microcontroller, DSP, GPU, FPGA, ASIC, etc
- [Reliability](http://nepp.nasa.gov/workshops/etw2013/talks/Wed_June12_2013/0900_Hillman_Reliability%20of%20Digital%20Electronics.pdf)
- Parallelism
- Flexibility
- Cost
- [Development Time](http://www.eecg.toronto.edu/~jayar/pubs/kuon/kuontcad06.pdf)
- Modularity


### Digital Electronics are **not** good at stuff
- Adapting
- Surviving
- Sensing
- Producing
- Hiding
- Producing Power


### What if?
- Difficult things for biology may be easier for EE
- Difficult things for EE may be easier for biology

- What if we could have it all??

- Microcontroller vs FPGA vs ASIC
	- vs Bioelectronics?
		- Biological H/W acceleration?



## Interfacing Biology and Electronics
### What does this mean?
- Initial goal: To use biology as a sensor
- Requirements
	- Transducers
		- Convert biological phenomena to EE ([lots](http://stacks.iop.org/Nano/22/405501) [of](http://www.sciencedirect.com/science/article/pii/0250687483850835) [research](http://dx.doi.org/10.1016%2F0956-5663%2893%2980024-J))
		- Convert EE to biological phenomena?
			- [Light](http://www.taborlab.rice.edu/)
			- [Shear Stress](http://2010.igem.org/Team:MIT_mammalian_Mechanosensation)
			- [Temperature](http://jb.asm.org/content/185/22/6609.full)
	- Does the application warrant it?
		- Could the job be done just using EE or just using biology?


## Interfacing Biology and Electronics
### What are the benefits?
- Biology may be able to outperform EE:
	- Conserving and generating power 
	- Sensing biological phenomena 
- EE may be able to outperform biology:
	- Development time and overhead
	- Flexibility
	- Modularity
	- Readablility of results
		- Giant purple thing in wetlab vs LCD screen
		- Visual indicators (blue or light blue?) vs
		  $\unicode{128516}$/$\unicode{9785}$ 


## Interfacing Biology and Electronics
### Bottom Line
- Can we outsource from biology to EE?
	- Computation
	- Decision-Making
	- Anything else EE is good at
- Maybe we can create a reliable and interpretable EE signal from biology?
	- Computational flexibility!


##What do we do now?
#### Designing a Modular Electronic Reader
0. Integrate systems known to work
	- Biological Sensor + pH Sensor + Microcontroller
1. Generalize the architecture
	- Put other sensors "in front" of arsenic sensor?
2. Exploit possible applications


##Introducing:
#TweeColi
###Possible Headline:
####"A single-celled organism probably has a larger social media footprint than you"


## Why should Grandma Care?
#####Other than the trash-talking headline
###What if:
- What if you had a large array of biosensors that could answer one
  or even multiple questions?
- Example:
 - Is this water safe to drink?
 - Has the cancer metastasized?
 - Is the air quality unhealthy?
- What if this device worked _in situ_?


### [Medical Diagnostics in Austere Environs](http://www.oxcaht.org/)
- Problem = Limited Resources
	- Power
	- Accessibility
	- Harsh conditions
- Bioelectronics
	- Low power
	- [Small, disposable, survivable sensors](http://arsenicbiosensor.org/index.html)
	- Ubiquitous computing platform
		- Mobile phone!



##This Talk
- What is TweeColi?
- Where could it go?
- How will it get there?
- Summary of TweeColi-specific meetings



##What is TweeColi?
- Electronic feedback from the cellular level
- A cute experiment but...


##Possible aims:
- First brick in the bridge between ECE and SynBio
- A process and procedures experiment



##TweeColi 1.0
Input Signal $\rightarrow$ Flask

Flask $\rightarrow$ pH Probe

pH Probe $\rightarrow$ Embedded Device

Embedded Device $\rightarrow$ Output Signal


##Where could TweeColi go?
- Cells could potentially tweet interesting things like:
	- "I'm hungry"
	- "I'm dead"
	- "Watch out! There's arsenic in this solution" 
	- "I found a strain of the flu virus I don't recognize. Did you get a flu shot? I recommend you stay home today" $\unicode{8592}$ More than 120 chars :-/


##Where Could TweeColi 1.0 go?
#####Other than tweeting...
####Wireless transmitting bacteria!
- Experimentation timesaver
- Microfluidic control?
```
wait(2000);
	setValve(14,HIGH);
	setValve(2,LOW);
wait(1000);
	setValve(14,LOW); 
wait(Tweecoli())
	setValve(14,HIGH);
```



##How will it get there?
 - Big picture
 - Where was it two weeks ago?
 - Where is it now?
 - Where will it be two weeks from now?


##Big Picture
1. Successfully detect one real world event from a single cellular signal 
2. Successfully detect two real world events from a single cellular signal 
3. Successfully detect >2 real world events from a single cellular signal or
   multiple cellular signals $\unicode{8592}$ is this even possible?


###Where was TweeColi two weeks ago?
####Components
- Two interfaces: 
	1. Arduino
		- Potentiometer
	2. Raspberry Pi
- No plasmids


###Where was TweeColi two weeks ago?
####Capabilities 
- Two interfaces: 
	1. Arduino
		- Triggers a tweet when the pot's resistance achieves a threshold
	2. Raspberry Pi
		- Trigger a tweet from a python module


###Where is TweeColi right now?
####New Components
- Atlas Scientific EZO pH Circuit
- Atlas Scientific pH Probe
- PCB Breakout
- 3-D Printed Wetware
- Calibration chemicals
- pH UP and DOWN solutions
- RGB and DOxy Sensors
- Plasmids for ureABC


###Where is TweeColi right now?
####New Capabilities
- Continuously read pH via Raspberry Pi
- Lab Safety Training
- Clearer direction


###Where will TweeColi be in two weeks?
####New Components
- Wetlab
 - Flasks
 - Stir Plate
 - Stir Bars
- Probe Reconditioning Kit


###Where will TweeColi be in two weeks?
####New Capabilities
- Trigger tweet when pH reaches a threshold 
- Biological circuit ready to test?


##TweeColi 2.0?
Input Signal $\rightarrow$ $\mu$F Chip 

$\mu$F Chip $\rightarrow$ IBM Si nWire 

IBM Si nWire $\rightarrow$ Embedded Device (Mobile Phone?)

Embedded Device $\rightarrow$ Output Signal




##TweeColi Meetings
- **24 September**: pH Probe Specifics
- **1 October**: Experimental Setup


###24 Sept: pH Probe Specifics
####Attendees: Traci, Swapnil, Ryan
- Discreet vs Continuous pH readings
 - Problem: The probe will get dirty and it's not autoclavable 
 - Solution: Use a physical barrier (0.2$\mu$m mesh) or soak in 10% HCl Solution


###1 October: Experimental Setup
####Attendees: Traci, Swapnil, Ryan
- Identified genetic parts for our circuit
- Outcome: List of items we need to order
 - Stir Plate (no heater)
 - 6 Flasks
 - Small stir bars 




## Short Term Plan
#### **Goals** for this semester. 
1. Obtain pH sensor $\unicode{10004}$
2. Integrate sensor with embedded platform $\unicode{10004}$
2. Culture biosensor in lab
3. Characterize biosensor*
4. Characterize pH sensor*
4. Integrate biosensor and pH sensor*

#####*The order in which we do these is totally debatable


##Possible Parallel Product:
- Document Design Process
	- Many interesting directions:
		- Traditional biological circuit design
		- Black Box Modeling [[1]](http://www.nature.com/nchembio/journal/v10/n7/full/nchembio.1559.html#f3) using a Biological Function Generator [[2]](http://www.nature.com/nmeth/journal/v11/n4/full/nmeth.2884.html)  
