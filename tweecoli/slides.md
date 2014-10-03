#Bridging the Gap:
##Synthetic Biology to Electronics
###**Why do Logic in Cells?**
####*In situ* deployment of *In vitro* vs *In vivo* vs *In silico* sensors...lol



##The elephant in the room:
##Why are we doing this?
- Why do logic in cells when logic in electronics works great?
 - I get that cells can be factories, but why use them to do computation?
- Possible answer: Because cells can detect things EE can't 


##Cells for Sensing? 
That doesn't answer the question:
##Why do _**logic**_ in cells?


##Answer(?): Because discerning outputs of SynBio circuits is hard
- Outputs are hard to read! 
- Examples:
 - Microscopy
 - Giant purple thing in the wetlab (LASERS)
 - Visual indicators (is this blue or light blue...)


###What if:
- What if you had a large array of biosensors that you were using to answer one
  or even multiple questions?
- Example:
 - Is this water safe to drink?
 - Has the cancer metastasized?
 - Is the air quality unhealthy?
- What if this device was field worked _in situ_?


###Cellular logic becomes very useful because:
- Without logic at the cellular level, you must provide an electrochemical
  transducer for the output of each signal
 - Granted, this isn't a big deal if you have Sufi's device that contains 24
   nanowire sensors...which could be a cool concept on its own!



##Introducing:
#TweeColi
###Possible Headline:
####"A single-celled organism probably has a larger social media footprint than you"



##This Talk
- What is TweeColi?
- Where could it go?
- How will it get there?
- Summary of TweeColi-specific meetings



##What is TweeColi?
- Electronic feedback from the cellular level


##Possible aims:
- Bridges the gap between ECE and SynBio
- A process and procedures experiment
 - Use a "Biological Function Generator" [[1]](http://www.nature.com/nmeth/journal/v11/n4/full/nmeth.2884.html) in order to generate a "phenomenological, or 'black box'" model [[2]](http://www.nature.com/nchembio/journal/v10/n7/full/nchembio.1559.html#f3) 



##Where could TweeColi go?
- Cells could potentially tweet interesting things like:
	- "I'm hungry"
	- "I'm dead"
	- "Watch out! There's arsenic in this solution" 
	- "I found a strain of the flu virus I don't recognize. Did you get a flu shot? I recommend you stay home today" $\unicode{8592}$ More than 120 chars :-/


## Applications (Brainstorming!)
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



##The way forward
- Document Design Process
- Many interesting directions:
 - Traditional biological circuit design
 - Black Box Modeling [[1]](http://www.nature.com/nchembio/journal/v10/n7/full/nchembio.1559.html#f3) using a Biological Function Generator [[2]](http://www.nature.com/nmeth/journal/v11/n4/full/nmeth.2884.html)  
