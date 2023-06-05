### PID Fan project by Klei and Grant

### Planning
[Time Management](https://docs.google.com/document/d/1oYSg2cFu_qaoOM3yz8rkRRCRVUBYdgV2tjKGM4pbZ4A/edit?usp=sharing)
[Planning Document]https://docs.google.com/document/d/10KXIkI71mnog2hYwAe9qdodhuHy_k5JTP9Cwo6pkJ9I/edit?usp=sharing

https://user-images.githubusercontent.com/112961430/231779757-706f8b02-47d8-4738-99ec-d17cc00045fa.mp4<figcaption> Planning Prototype </figcaption>

### Materials
[Materials Document](https://docs.google.com/document/d/1Y_SMDsQwYU3oLXD34Tc_6X-V50yahsYf0Q7-Y88PeXg/edit)

### Wiring 
![Wire](https://github.com/kstanfo00/PID-Fan/blob/master/media/Wire.PNG)


### Code 
[Code Repository](https://github.com/ggastin30/CPython/blob/master/Engineering%203%20Code/fanPID.py)

![e565465464667](https://github.com/kstanfo00/PID-Fan/assets/112961430/a57b6089-07ee-427d-adf7-bd7af59f61f6)<figcaption> This is a screenshot of our graph of the PID on Mu. The yellow line is the setpoint. The green line is the rpms. You can see that the green line adjusts to the setpoint very well. </figcaption>


### CAD
[Onshape Document](https://cvilleschools.onshape.com/documents/092e602ab51989e7e18e86b6/w/c6d02d2cdaf8048d25fb16c3/e/22746867da17f6038a13b326?renderMode=0&uiState=643e9ce2e89fcc7e947cc6ef)

### Pictures/Videos

![67897869678](https://github.com/kstanfo00/PID-Fan/blob/master/media/67897869678.PNG)<figcaption> top view of assembly. </figcaption>

![9890](https://github.com/kstanfo00/PID-Fan/blob/master/media/9890.PNG)<figcaption> front view of assembly. </figcaption>

![78690879](https://github.com/kstanfo00/PID-Fan/blob/master/media/78690879.PNG)<figcaption> left view of assembly. </figcaption>

![5467897](https://github.com/kstanfo00/PID-Fan/blob/master/media/5467897.PNG)<figcaption> back view of assembly. </figcaption>

![34675467](https://github.com/kstanfo00/PID-Fan/blob/master/media/34675467.PNG)<figcaption> right view of assembly. </figcaption>

![87909870](https://github.com/kstanfo00/PID-Fan/blob/master/media/87909870.PNG)<figcaption> bottom view of assembly. </figcaption>

![213443214](https://github.com/kstanfo00/PID-Fan/blob/master/media/213443214.PNG)<figcaption> inside view of assembly. </figcaption>

![45](https://github.com/kstanfo00/PID-Fan/blob/master/media/890.jpg)<figcaption> front view of fan. </figcaption>

![333](https://github.com/kstanfo00/PID-Fan/blob/master/media/5395D116-62D1-4190-96B7-4FBB44694980.jpeg)<figcaption> bottom view of fan. </figcaption>

![3334](https://github.com/kstanfo00/PID-Fan/blob/master/media/678989.jpg)<figcaption> right view of fan. </figcaption>

![33334](https://github.com/kstanfo00/PID-Fan/blob/master/media/870.jpg)<figcaption> back view of fan. </figcaption>

![232](https://github.com/kstanfo00/PID-Fan/blob/master/media/image0.jpeg)<figcaption> left view of fan. </figcaption>

![2322](https://github.com/kstanfo00/PID-Fan/blob/master/media/image1.jpeg)<figcaption> top view of fan. </figcaption>

### https://github.com/kstanfo00/PID-Fan/blob/master/media/Video.mov<figcaption> VIDEO OF FAN. </figcaption>

### Post Project Thoughts
This project was definetly the hardest one we've done, because of the time constraints. It was a pain on the coding side, because we spent 70% of the project on coding alone. The criteria stated that we needed a 6 volt battery to power the project, but we used a 15v plug to power it instead. This is because the fan required more voltage to hit it's RPM. One thing we would do differently next time is make more space for the wires in the fan box. This is because the wires would hit the fan a lot. 


### Good Stuff:
- The design turned out cleaner than we thought
- We used lab materials to save time
- It doesn't depend on batteries
- Documentation was superb

### Bad Stuff:
- Our LCD had problems starting up
- The wiring was subpar
- We had to re-lazer cut because we didn't account for height of photointerrupter
- It was hard to find the range of the motor, which made PID tuning harder. 
- We accidentally destroyed a 50 dollar metro board because we fed it 15 volts. Make sure to have someone review your wiring when you are working with more voltage than the board can handle. 



### Reflections
Klei: This project revealed how much good planning affects the project. If I could redo this project, I would plan out the design for a couple more days, just to give clarification. We did make a good prototype, but there were some things we missed in planning such as the placement of the photo interrupter and the trigger for it. I really learned how to use what was already created (or as Mr.H says "not reinventing the wheel") to make my design simple. I used standoffs in many places instead of wasting valuable time designing a whole new piece to be printed. Also, instead of using friction-fit connections like our last project, I made sure to use the already printed brackets which were very easy to assemble and were much more stable. In my next project, I need to remember to plan where the switch and the led power indicator should go so we don't have to recut pieces.

Grant: This project was a struggle for me, because of how much work I had to put in the code. The first hurdle for me was getting the reading of rpms from the fan. I had to really think about this before I did it and ended up using a bunch of while loops to make it read once, twice, and then take the difference in time and calculate per minute. We used a fan that was drawing power from a plug outlet (15 volts) which was dangerous and led to us frying a board. When you are making a motor control circuit, always make sure to review it with online diagrams. The other problem we had was getting the photo interrupter in the right spot because it couldn't be touching the trigger but had to have it go through it. We ended up offsetting it from the wall with nuts until it got in the right place. If I did this project again, I would definitely wire before assembly because we had many wires interfering or popping out of their place and confusing us.
