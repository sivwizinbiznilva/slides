###Introducing:
#TweeColi
###Possible Headline:
####"A single-celled organism probably has a larger social media footprint than you"



##What is TweeColi?
- Textual feedback from the cellular level
- The cell can literally provide a status update



##What is TweeColi right now?
- Two interfaces: 
	1. Arduino
		- Analog Read from a potentiometer
		- Triggers a tweet when the pot's resistance achieves a threshold
		- Uses a Temboo service (limited to 1000 calls per month)
	2. Raspberry Pi
		- Uses Twython module
		- Serial monitor used to trigger a tweet



##Where could TweeColi go?
- Cells could potentially tweet interesting things like:
	- "I'm hungry"
	- "I'm dead"
	- "Watch out! There's arsenic in this solution" 
	- "I found a strain of the flu virus I don't recognize. I also detected
	  a strain that I do recognize. Hopefully your flu vaccine works its
	  magic!" $\unicode{8592}$ More than 120 chars :-/



##How will it get there?
1. Successfully detect and interpret one cellular signal 
	- Cell: "pH-Based biosensor for detection of arsenic" in solution
	- Interface: Atlas Scientific pH sensor paired with RPi or Arduino
2. Successfully detect and interpret two cellular signals
3. Successfully detect and interpret interactions of >2 cellular signals using
   one output $\unicode{8592}$ is this even possible?



##What's the point?
- Human-readable feedback seems to be a bottleneck with biosensors
