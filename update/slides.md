#3 Nov 2014


##TweeColi 2.0


![Napkin Design](WirelessBacteria_Napkin.jpeg)


##TweeColi 1.0
Jar


##TweeColi 2.0
RFID?


##Passive RFID System
![system](rfid_system.png)


##Passive RFID Signal
![signal](rfid_signal.jpg)



#17 Nov 2014


### CIDAR TweeColi vs TU Delft Electrace

| | TweeColi | Electrace |
| :--------- | -------------: | ----------------: |
| Sensing Mechanism | pH | Direct Electron Transport |
| Biological complexity | 1k basepairs | [>5k basepairs](http://parts.igem.org/Part:BBa_K1316012) |
| Electronic complexity | Higher | Lower |
| System complexity | ? | ? |


![DET](DET.jpg)


#Questions:
1. Have we determined if Biology is complex?
3. If not, we may be designing it wrong 
  - Are we using scientific experiments as engineering tests?
2. If so, are we designing it as such?


#The Process
- There are two processes classifications that we can consider for engineering bioelectronics:
 1. The Engineering Method
 2. Complex Systems Design
- How do we decide which to use?


## Does the system display *complexity*?
- [A system will be considered *complex* if it is **impossible** to predict all of its behaviors from the behaviors and relationships of its components](http://www.cvaieee.org/html/resp_citizen/Complex_Systems.pdf)


## What is a Complex System?
### Case study: Death Star


### Building Death Stars is a Bad Idea
- Operational and Programmatic difficulties 
  - [Defense Acquisitions University](http://www.dau.mil/pubscats/ATL%20Docs/Sep-Oct11/Ward.pdf) 


### Programmatic Assessment
- Cost
  - Overbudget
- Schedule
  - Multiple slips in critical path
  - "The Emperor is most displeased with your lack of progress" - [D.V.](http://www.starwars.com/video/vader-arrives-on-the-death-star)
- Performance


## Operational Assessment
- Poor combat performance
  - Main capability utilized only once
- Critical vulnerabilities
  - Effectively mitigated by half-trained Jedi
- Assessment: CAT 1A (Critically Flawed)


## Program Assessment: Death Star
- No Go
  - Overbudget
  - Behind Schedule
  - Blown up before Act II
  - Impossible to scale up production


### On-Time On-Budget Alternative
- Case Study: R2-D2


## Programmatic Assessment
- Simple requirements
  - No superfluous parts or unnecessary features
     - No language processor (beeps and squeaks)
     - No arms
     - No face
     - Small size 
- Simplistic design results in manageable cost/schedule


#Conclusion: 
##Build Artoos not Death Stars
###Bottom Line: Avoid _Complexity_


###Q: How do we know if our system is complex?
###A: Test it! 


##Test vs Experiment
- These are not the same!


##Experiment (Science)
- Accept/Reject a hypothesis. i.e. "Ask nature"
  - Recreate conditions under which an observation can be made
  - [Replicability is not Reproducibility](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.149.5692) nor is it indicative of reliability
- Acceptable: Results can only be duplicated in a controlled environment


##Test (Engineering)
- Does the design meet the requirements reliably?
  - Two phases: DT and OT


#Testing Phases
- Developmental Testing:
  - Does the system do what we think it should do in a controlled environment?
- Operational assessment: 
  - Does the design meet the requirements in the environment for which it was designed?


##TweeColi 1.0 DT
- Jar contains the most simple bioelectronics project our lab can build using the engineering method 
  - Based on a basic understanding of cellular behavior and chemistry, we have made a behavioral prediction
- If this works **reliably** then it may be acceptable to assume that our subsequent prototype can be designed using the Engineering Method
- If this doesn't work **reliably** then we may have to revisit our design methodology to either categorize our design domain as *complex* (avoid) or revisit our requirements


## How do we design systems if complexity cannot be avoided?
- Good question


## WARNING: Philosophical Overtones
- Reductionism is the basis for abstraction
- Reductionism is rendered FALSE in the face of [*emergent behaviors*](http://www.cvaieee.org/html/resp_citizen/Complex_Systems.pdf)
- What's an engineer or policy analyst to do?
 - Ex. GMO policy, gene drive research, climate change policy, etc


## Emphasize prediction and discovery first, then explanation
- Requires a scientist and an engineer
- Prediction: Design a system and a test with a boolean result (engineer)
- In case of failure, design an experiment for the discovery of emergent behaviors (scientist)
  - If emergent behaviors are found, explain them in terms of the properties of the system's components


### But what if our stuff doesn't work?
   1. Can we create a simpler genetic circuit?
   2. Should we just consider the system *complex*?
   3. Can we do something else?



# 16 Dec 2014


###Bottom Line Up Front
- Demo report
- One-Two punch
  - Tech Contribution
  - Epistemic Contribution


###Demo Report
- Current TweeColi capabilities
  - Detect distributed biological events
  - Report events
  - Collect and interpret events
  - Perform logic using events as inputs
  - Actuate a response mechanism based on logic operation


###Tech Future
| Project | Timeline |
| :-: | :-: |
| Practical applications for TweeColi | Days |
| Biological GSM network using OpenBTS | Weeks to Months |
| Biological monitoring using RFID | Years | 


###Epistemic Contribution
- SynBio's Existential Crisis
- Importance of semantics
- Philosophy of Science **with data**


###SynBio's Existential Crisis
- It's been 14 years since the repressilator and switchable regulatory network
- What defines success in synbio?
  - Acquired knowledge?
  - Making things?
  - Solving problems?
- Cause vs Control
- Science vs Technoscience [[Nordmann 2014]](http://ryanjsilva.com/papers/Nordmann2014.pdf) vs Engineering 


###Semantics Are Important!
- Different processes
- Different goals
- Different design considerations
- Different ways of managing complexity
- Let's formally choose to abide by one (Engineering)


###Philosophy of Science
- Examines epistemic values
- Data is derived from publications in the field
- Information flows one way 
  - Field of research $\unicode{8594}$ Philosophy of Science


###Philosophy of Science...
###...With Experimental Data
- Let's complete the loop
  - Leverage their analyses to an actual design and document findings
  - Perhaps implement a method for complex design automation?
- No one is doing this
- Use a purely engineering approach to build a cool thing
- At least two contributions:
  - Document results as an engineering paper 
  - Document and comment on epistemic contributions as a Philosophy of Science paper 


### Nature 
> As it develops along this and other paths, synthetic biology itself will demand more by way of new fundamental biological knowledge — quantitative, systematic, computational and biophysical. And conversely, one of the deepest lessons from these first ten years is that **biological knowledge will require synthetic approaches** if it is to become a mature and reasonably predictive science. 

Nature editorial, 2010, "Ten years of synergy," _Nature_ 463, 269-270


###How did we get so confused?
- The quote was not "What I can create, I do understand"
- The quote was "What I cannot create, I do not understand" - Richard Feynman


![Feynman](Feynman.jpg)


### Problems 
- The bar for reporting may not be conducive to engineering 
  - In what sense is a repressilator an "experiment"?
  - Trying to satisfy both criteria 
    - Mostly science, with a few engineering terms sprinkled in
- Let's justify our position and then _**own**_ it
  - Maybe that will help restore the levels of scrutiny to levels appropriate with what we're trying to do
    - ENGINEER biology 


### How does this play into my current direction?
- Test modularity by working at the extreme ends of the design (I/O)
- Document findings


### Possible applications of TweeColi
- Automation of distributed irrational design testing
  - Three labs build a device that claims to have function X
  - Run TweeColi
  - Interpret results at processing node 
###Engineering complex systems 
- How to design with complexity in mind
- Must decide which engineering design technique to eliminate
 - Modularity
 - Regularity
 - Hierarchy
 - Discipline
 - Abstraction
- Begin by analyzing how the system was initially designed
 - Case study: x86 architecture
 - Very tricky (and not without controversy) for Biology


### Philosophy of Science and SynBio
- Example articles
- Seem focused on balance of knowledge and power
- Leverage their analyses to an actual design and document findings
  - Perhaps implement a method for complex design automation
- Eliminate the need for modularity [Lewens 2013](http://ryanjsilva.com/papers/Lewens2013.pdf)


### Philosophy of Science and SynBio
### WITH DATA!
- No one is doing this
- Example: In meteorology, if the model incorrectly predicts a certain type of weather what do we do? 
  - Do we throw out the model? 
  - Search for a new model? 
  - Or do we accept, for the time being, that the current model is "good" but has finite resolution and reliability 
    - Cold vs 30 degF 
    - Bring an umbrella just in case vs two inches of precipitation at 11am tomorrow
  - Are we using the model to learn about the atmosphere?
  - Or are we using it to help us better live our lives?


### Semantics are Important!
- Let's try to stop semantical "hand waving" 
  - Systems Biology vs Synthetic Biology
  - Engineering vs Science vs Technoscience
  - Basic vs Applied Science
  - Cause vs Control
- Let's not confuse managing complexity with engineering!
  - It is possible to "properly" engineer a system that is not modular, hierarchical, etc
