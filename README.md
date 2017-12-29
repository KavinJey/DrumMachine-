# DrumMachine-
The pursuit of music

A drum machine is an electronic instrument that is made to imitate the sound of percussion, it is used to create beats on the fly and helps an artists quicken up their workflow. I was intrigued by drum machines when I first started trying to create music on my own. This lead to me wanting to create my own softward as well as build my own drum machine! 


In order to get started I developed a set number of tasks: 
- [x] Find neccessary hardware
- [x] Assemble neccessary hardware into a demo 
- [ ] Create software that will interact with this hardware in order to create music 


## Hardware
 The things I used for this project were: 
 - Trellis Silicon Elastometer Keypad 
 - 9 3mm Blue LEDs
 - Adafruit Trellis Monochrome Driver PCB 
 - Solder 
 - Soldering Iron 
 - 3D printer (for the enclosure) 
 
 After soldering the LEDs into the PCB board and connecting each of the wires to their respective ports, I had this: 
 
 ![PCB outside box]( /PC290005.JPG )
 ![In the box](/PC290006.JPG )
 ![Blue LEDs lit up]( /PC290004.JPG )
 
 You can test if it works by pulling up any music program that takes midi controllers and using hairless midi to control it. I had used hairless midi to control the vmpk keyboard for ubuntu and it worked out fine. 
 
 
 
 ## Software
 The plan is to build a interface that connects and uses midi data to map sounds to specific keys and then play them with each press. So you can choose your own sounds for each of the buttons. This is a WIP and will be completed soon. 

