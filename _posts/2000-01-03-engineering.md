---
layout: post
title:  "engineering"
date:   2000-01-03 20:30:00 +0100
categories: jekyll update
---



* [engineering design process](#engineering-design-process)
* [power & energy technology](#power-technology)
* [transport & aerospace technology](#transport-technology)
* [materials science & construction](#materials-and-construction)
* [smart home & consumer technologies](#technologies-in-the-home)
* [sound, optics & vision systems](#sound-and-vision)
* [communications & network infrastructure](#communications-technology)
* [computer systems & hardware architecture](#computer-technology)
* [programming languages & software engineering](#programming-languages)

# Engineering

This post is inspired by the "How technology works" book. Most of the information is from that book. I highly recommend buying the book

## Engineering design process

Engineers follow a different process to the scientific inquiry called the engineers design process. 
1. Define problem
2. Background research
3. Determine design specs and constraints
4. Design statement: Brainstorm ideas, evaluate solutions, chose solution
5. Design and Make Prototype
6. Test and Evaluate prototype 
7. Iterate to find best solution


## Power technology
### Water supply
1. water intake: 
2. coagulation
3. flocculation
4. sedimentation
5. filtration
6. chlorination
7. storage

### Oil refineries
1. crude oil 
2. oil enters column
3. distilation
4. vapour rises
5. tray colllection

### Generators
- AC generators
- DC generators

### Motors
- Electric motors

### Power stations
1. Fuel supply: Coal is crushed and fed into a large furnace to be burned. 
2. Furnace: Water running through tubes in the boiler is heated to an over 500C at very high pressure. Waste gasses pass through an electrostatic precipitator and desulphurisation plant to clean.
3. Turbine: the high pressure steam turns the fan blades of steam turbines with great force and speed. This rotational motion is transmitted to the generator by driveshaft.
4. Generator: generator's rotor spins thousands of times each minute, producing an alternating current (AC), typically with a voltage of 25,000V. 
5. Electricity supply: voltage of electricity is greatly increased by a step-up transformer. This improves efficiency as the electricity is transmitted away via power lines.
6. Cooling tower: steam is cooled in the condenser then sprayed into cooling towers, where most of the water cools and is piped back for re-use. 

<img src="/imgs/science/power_stat.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Electricity supply
1. Power station: a generator located in a power station converts kinetic energy into electrical energy. This produced AC electricity - 25,000V
2. Grid substation: A grid substation uses step up transformer to increase voltage to 400,000V. The higher the voltage the less energy lost as heat from resistance.
3. High voltage pylon lines: steel-reinforced aluminum pylons made with glass/ceramic insulators to stop electricity traveling to the ground.
4. Direct supply to industry: some factories want high voltage!
5. Distribution substation: a step down transformer used to bring voltage down -> industrial and commercial customers.
6. Domestic supply: a network of distribution lines supplies electricity to houses. pole mounted transformers locally bring the voltage down to the home's fusebox.

<img src="/imgs/science/elec_grid.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Nuclear power
1. Uranium fuel rods: Hundreds of metal rods grouped into bundles contain small pellets of uranium fuel. They are lowered into reactor core.
2. Chain reaction: Unstable uranium nuclei break down, releasing heat and emitting neutrons. These collide with further nuclei, creating a chain reaction that provides a huge amounts of energy.
3. Control rods: control rods modify the speed of chain reaction. When lowered in among the fuel rods they absorb the free neutrons to slow down the reaction.
4. Creating steam: heated by the reactor core, the water flows into a heat exchanger, giving up its energy to a second closed system of piping that carries cold water. The cold water is turned into hot steam, under high pressure.
5. Turning the turbine: housed in a turbine hall, the turbine's fan blades are turned by the high-pressure steam from the heat exchanger. 
6. Power supply: the electricity generator is driven by the turbine's drive shaft. A transformer increases the voltage so it can be carried away.

<img src="/imgs/science/nuclear.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Wind power
1. Turbine blades: mounted on a freely turning axis, the propeller like blades catches the air and spin round. As they move they turn a central drive shaft. The angle or pitch of turbine blades can eb altered to adjust their speed. 
2. Gearbox: converts low speed rotation into high speed rotation to turn generator.
3. Generator: takes mechanical energy from driveshaft and turns into electrical energy.
4. Electric current: produced by generator taken by a cable
5. Increasing voltage: step up transformer used to get high voltage to be passed to the power grid.

Micro-generation
small scale renewable energy systems use free standing or roof mounted roof wind turbines.

### Water and geothermal power
1. Cold water pumped
2. Hot water returns
3. Heat exchanger
4. Power generation

### Solar energy and bio-energy
1. Solar energy: sunlight comprises tiny energy packets called photons. When photons hit a solar panel, made of dozens of PV cells, they transfer energy to electrons that then flow via conductors through an external circuit as an electrical current.
2. Converting current (DC->DC): An inverter converts electricity from the panel DC into AC, which is then usable by the home.
3. Distributing power: the electricity is sent from the main panel around the home. The panel can accept electricity from the local grid when the solar panels do not meet demand.
4. Measuring power: a smart meter keeps track of energy generation and electricity use in both directions.
5. Connecting to the grid: Any excess electricity produced by the solar panels is sent to the power grid and credited to householder.

<img src="/imgs/science/pv.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Batteries
batteries are a portable store of chemical energy that can converted into electrical energy. Primary (single use) and secondary(rechargeable). 

1. chemical reactions: when a battery is connected to an electric circuit, a chemical reaction makes the metal atoms lose electrons. These are attracted to and gained by a chemical paste called electrolyte.
2. electrons gather: free electrons are drawn towards an anode, creating an imbalance with a deficit of electrons at the anode and an excess at the anode. The electrons freed by the chemical reaction move towards the anode inside the battery but cannot get any further until an eternal circuit is connected.
3. migrating electrons: the external circuit connecting the anode and cathode provide a path along which the electrons can flow, producing an electric current. Along the way, this current can be used to power an electrical device.
4. incoming electrons: the electrons re-enter the battery via the cathode. The flow continues until the store of chemicals is exhausted.

Recharging:
when a battery is plugged into a charger, a current is passed through in the opposite direction that was discharging. This moves electrons back to where they started, recharging the battery.

Lithium ion batteries
- large number of electrons in reactive metal lithium
- lithium has a low weight but high energy density -> good power to weight ratio for batteries  that can withstand hundreds of discharge and recharge cycles. 

<img src="/imgs/science/batt.png" alt="Universe" style="width: 100%; height: auto; display: block">

## Transport technology

### How a car works
A car is a collection of systems that generates power in and engine and transmit it to the wheels. Other systems allow the driver to control the car by turning the wheels to change direction and by applying brake force to either slow down or stop.

1. engine: internal combustion engine - starting the engine ignites the fuel and releases energy. This moves pistons, which turns the engine's crankshaft. A flywheel attached to the crankshaft smooths out the power provided by the pistons
2. clutch: The driver must disconnect the clutch then releases clutch, allowing the engine to turn the wheel.
3. gearbox: piston engines work most efficiently at relatively high speeds, so gears are necessary to reduce this to a slower rotational speed needed for car's wheels. Each gear gives a different range of speeds. First gear is normally selected to get car moving.
4. driveshaft: a long driveshaft connects gearbox to rear wheels. In front wheel car, engine sits on top of the front wheels and turns them via short driveshaft, differential and half shafts.
5. steering: rack and pinion - turning car's steering wheel rotates a pinion - small round gear. it's teeth engage the teeth on a flat bar called a rack. 
5. braking: disc brakes - a disc is fixed to each wheel, when the wheel spins, so does the disc. When braking applied, hydraulic fluid forces brake pads, mounted on calipers to push against the disc to slow wheel down.

<img src="/imgs/science/car.png" alt="Universe" style="width: 100%; height: auto; display: block">

#### Internal combustion engines
a heated fuel-air mixture (petrol and air). 
1. intake
2. compression
3. power - spark plug
4. exhaust

### Electric and hybrid cars
electric motors connected to a rechargeable battery.
<img src="/imgs/science/electric_car.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Radar
high frequency radio waves are sent out then reflected back.
<img src="/imgs/science/radar.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Speed cameras
high frequency radio waves are sent out then reflected back.

### Trains
- electric trains, use overhead cables or third rail
<img src="/imgs/science/train.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Sailboats
<img src="/imgs/science/sailboats.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Submarines
<img src="/imgs/science/submarines.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Jet engines and rockets
<img src="/imgs/science/jet_engine.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Aeroplanes
<img src="/imgs/science/air_plane.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Helicopters
<img src="/imgs/science/helicopter.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Drones
<img src="/imgs/science/drones.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Space probes
<img src="/imgs/science/space_probes.png" alt="Universe" style="width: 100%; height: auto; display: block">

## Materials and construction

### Plastics
<img src="/imgs/science/plastic.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Composites
<img src="/imgs/science/composites.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Bridges
<img src="/imgs/science/bridges.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Tunnels
<img src="/imgs/science/tunnels.png" alt="Universe" style="width: 100%; height: auto; display: block">


## Technologies in the home
### Utilities in the home
Utilities include power, heating, water and communications services supplied to homes. They are usually provided by external companies, although some properties may have an independent water supply or heating source.

**Central heating**
water is heated often using an oil or gas fired boiler, and then circulated in a closed system of pipes and radiators to warm rooms. Thermostats monitor temperature to ensure the desired heat level is maintained.

**Electricity supply**
Electricity is metered and distributed around a home by a consumer unit.
<img src="/imgs/science/home_util.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Heating

1. Gas and air: Air is drawn in by the fan as gas is supplied from the gas pipe to the burner. A pilot light burns, ready 

<img src="/imgs/science/home_boil.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Microwave ovens
<img src="/imgs/science/home_micro.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Refrigeration 
<img src="/imgs/science/home_refridge.png" alt="Universe" style="width: 100%; height: auto; display: block">


### Washing machine
<img src="/imgs/science/home_wash.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Digital home
<img src="/imgs/science/home_digi.png" alt="Universe" style="width: 100%; height: auto; display: block">


## Sound and vision

### Waves
<img src="/imgs/science/sound_waves.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Microphones and loudspeakers
<img src="/imgs/science/sound_speak.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Digital sound


### Digital cameras
<img src="/imgs/science/sound_camera.png" alt="Universe" style="width: 100%; height: auto; display: block">

## Communications technology
### radio signals
<img src="/imgs/science/comm_radio.png" alt="Universe" style="width: 100%; height: auto; display: block">


### radios
<img src="/imgs/science/comm_radio2.png" alt="Universe" style="width: 100%; height: auto; display: block">

### telephones
<img src="/imgs/science/comms_tele.png" alt="Universe" style="width: 100%; height: auto; display: block">


### television broadcasting 
<img src="/imgs/science/comms_tele3.png" alt="Universe" style="width: 100%; height: auto; display: block">

### televisions

### satellites
### satellite navigation
<img src="/imgs/science/comms_tele4.png" alt="Universe" style="width: 100%; height: auto; display: block">

### internet
<img src="/imgs/science/comms_internet.png" alt="Universe" style="width: 100%; height: auto; display: block">

### world wide web
<img src="/imgs/science/comms_www.png" alt="Universe" style="width: 100%; height: auto; display: block">

### email
<img src="/imgs/science/comms_email.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Wifi
<img src="/imgs/science/comms_wifi.png" alt="Universe" style="width: 100%; height: auto; display: block">

### mobile devices
<img src="/imgs/science/comms_phone.png" alt="Universe" style="width: 100%; height: auto; display: block">

### smart phones
<img src="/imgs/science/comms_phone2.png" alt="Universe" style="width: 100%; height: auto; display: block">



## Computer technology
### digital world
<img src="/imgs/science/comp_comp.png" alt="Universe" style="width: 100%; height: auto; display: block">

### digital electronics
<img src="/imgs/science/comp_transis.png" alt="Universe" style="width: 100%; height: auto; display: block">

### computer hardware
<img src="/imgs/science/comp_comp2.png" alt="Universe" style="width: 100%; height: auto; display: block">

### how computers work
At the heart of every computer is an integrated circuit called a CPU. It communicates with the computer's main memory, input devices, and output devices. 


#### CPU
The CPU is the brain of the computer, responsible for general-purpose computing. It contains billions of transistors, which act as tiny switches representing binary data (1 and 0). The CPU performs tasks in multiple steps: 
1.	fetching - control unit receives instruction from memory
2.	decoding - control interprets the instruction
3.	execution - ALU performs calculation
4.	repeating 1-3
The CPU's speed, measured in gigahertz (GHz) indicates how many instructions the CPU can perform in a second.  More cores mean you can do multiple tasks at once. 
 
Sand to transistor
But what is this transistor?
A transistor is a three-terminal semiconductor device with the collector, base, and emitter. By applying a small current to the base, a larger current flows between collector and emitter. This switching represents binary states. In a modern CPU, binary logic is primarily formed using MOSFETs (Metal-Oxide-Semiconductor Field-Effect Transistors)
Transistors act as microscopic, high-speed switches that represent binary states (1 for "on" and 0 for "off"). By combining several transistors, engineers create Logic Gates, which perform basic mathematical and logical operations. NOT Gate: Inverts the signal (1 becomes 0). AND Gate: Outputs 1 only if both inputs are 1. OR Gate: Outputs 1 if at least one input is 1. NAND/NOR Gates: These "universal" gates are particularly efficient to build with MOSFETs and can be used to construct any other type of logic. 
How do you make a transistor? Sand.
The most common form of sand is silicon dioxide (SiO₂), found in quartz.
Silicon is the second most abundant element in Earth’s crust, and sand provides a cheap, plentiful raw source. Raw sand can’t be directly used for chips. It first goes through chemical reduction processes (like the carbothermic reduction in a furnace) to make metallurgical-grade silicon (~98–99% pure). That silicon is purified further via the Siemens process into extremely pure polysilicon (99% pure, or “9N” purity). This step is critical — impurities at parts per billion can make chips fail. Using the Czochralski process or float-zone refining, the pure polysilicon is grown into large, single-crystal silicon ingots. These ingots are sliced into thin wafers — the starting substrate for chips. On the wafer, layers of materials are deposited, patterned, and etched using processes like photolithography, doping, oxidation, and etching.
Billions of transistors are created on each wafer. 
 

#### RAM
RAM comes in sizes like 4gb, 8gb, 16gb, and 32gb, and it is essential for temporary data storage during active tasks.
PSU
The PSU converts electrical power from your home's AC outlet into direct current (DC) that your PC components require. Efficiency is important because it determines how much power is converted to DC.
Storage
For storage, Solid state drive (SSD) uses flash memory to store data even when  power is off. Unlike hard drives, SSDs have no moving parts, making them faster and more durable. Case sizes come in sizes corresponding to the motherboard form factors, such as  micro-ATX, ATX and E-ATX.
GPU
The GPU renders images and videos. It has many cores and dedicated memory for processing graphics, making it excellent at parallel processing. Popular GPU brands are NVIDIA, AMD and Intel.

#### Motherboard	
The motherboard is like the skeleton of the PC, connecting all the "thinking" units together. Motherboards comes in three different sizes: ITX, Micro ATX and ATX. There are two main motherboard brands based on CPU brand: AMD and Intel withs specific socket types. Case sizes come in sizes corresponding to the motherboard form factors, suchas micr-ATX, ATX and E-ATX.
 


## Programming languages

- Programs are just a sequence of instructions telling a computer what to do. 
- The problem with human language is that it’s ambiguous. 
- We only understand each other because we share a lot of common knowledge and experience. Even then we struggle with communication. 
- Computers require clear instructions on what to do. 
- Computer scientists circumvented this problem by making special notations for everything that can be computed – called programming languages. 
- Every structure in programming languages has a precise form (syntax) and precise meaning (semantics). 
- These languages are called High level programming languages because they are designed for humans. 
- Computers though can only understand machine language and eventually in binary.
<img src="/imgs/science/python.PNG" alt="Migration" style="width: 100%; height: auto; display: block">

### Variables
Holds the data

#### Data types
- Types: int, floats, string, Boolean, char, null or none, 
- Data structures
- Lists or arrays
- Dicts or maps
- Sets (unique values)

### Operators
- Arithmetic (=,+,-,)
- Comparison (<,>)
- Logical (and, or)

### Control flow
Conditional – if, else
- Aim: minimize the number of checks the computer performs:
- Place the most likely case first: Put the condition most likely to be true at the top of an if/elif chain so Python can skip subsequent checks immediately.
- Put "cheap" checks before "expensive" ones: Evaluate simple comparisons (e.g., x == 0) before complex ones like function calls or database lookups.
- Avoid deep nesting: Use the "Guard Clause" pattern—exit early from a function if a condition isn't met—to keep code flat and avoid redundant evaluations.

#### Loops (for, while)
- Over a list of values
- Range()  builds a sequence of numbers
- List() makes it into a list
- Loops – efficient for loops
- To make loops efficient in Python, the best strategy is often to  avoid them entirely by using built-in functions or vectorization. If you must use them, you should minimize "overhead"—the extra work Python does to look up variables and function

List comprehensions are generally faster than traditional for loops with .append()because they are optimized at the C-level and use a specialized bytecode instruction (LIST_APPEND) to build the list in one go. 
- Python's built-in functions like sum(), max(), and min() are implemented in C and are significantly faster than writing a loop to do the same calculation manually


### Data structures
- Lists or arrays
- Dicts or maps
- Sets (unique values)
- Data structures - lists
- Encryption : the process of encoding information for the purpose of keeping it secret or transmitted it privately is called encrypton. 
- To decrypt a. messge- party receiving the message needs o have a key so encoding can be reversed.  Keys can be public or private. 
- Public systems – encryption keys are public – anyone can send a messge using key but only the other part will have decryption key to decipher it. 
- Files – text files can be iterated through lines wih a for flop  using read, readline, readlines
- Simple version of program or program component and try to gradually add features until it meets spec 
- Mini cycles through the dev process as prototype is incrementally expanded into final program
- Data structures - Dictionaries
- Editing Dictionaries
- Replacing a value

Data tables library 
- Using replace on one column
- df['colname'] = df['colname'].replace('X': 'Y', 'A': 'B')
- Using loc with a condition
- df.loc[df['colname'] == 'X', 'colname'] = 'Y'
- Dictionaries (non-sequential collections)
- Key value pairs 
- Mappings
- Other programming langues call it hashes or associate arrays

### Conditional and Loops
- Operators 
- Arithmetic (=,+,-,)
- Comparison (<,>)
- Logical (and, or)
- Conditionals (if, else)
- Loops (for, while)
- Limitations of code – adding
- Limitations of computer doing maths. Machine ints aren’t like th emathematical integers. There are infinite integers but infite range of ints. Ints are streod in fixed range of ints in the computer. Computer memory is composed of switches – on or off (1,0). A sequence of bits can represent more possibiolties. With two bits you can do 4 presenttaions. 00,01,1,0,11. Each extra bit doubles number of patterns. 2n values. The number of bits that a particular computer uses to represent an int depends on design of CPU. Computers now adays use 32 or 64 bits. For a 32 bit CPU, 232 possible values. These values centered at 0 to rppesent a range of pos + veg values so we diivde by 2. 231. Range of integers that a 32-bit int value is -231 to 231 -1 (-1 to account ofr representation of 0 in the top half of the range)
- What is largest number a 32-bit computer can store?
- 231-1 = 2147483647
- Can do up to 12 factorial, but after the representation “overflows” and results are garbage.  
- You end up losing the last digts.
- This allows huge or tiny numbers, but precision is limited. Only fractions made from powers of 2 (like 1/2, 1/4, 3/8) are exact; 1/10, 1/3, etc., are approximations.

- Example:
Try entering this in Python:
- It returns False due to small rounding errors in binary representation.
- Using a float allows us to represent a much larger range of values than a 32-bit int, but the amount o precision is still fixed. In fact, a computer stores floating point numbers a s pair of fixed-length (binary) integers. Only faractions hat involve powers of 2 can be represtnted exactly. Other fractions produce infinte repeating manissa. Close approximations. 
- Python has. Agood soluton – python auomatically converts to repsentation using more bits. Python breaks it to down to smaller units that the hardware is able to handle. Very good features of python.
Classes
- A class is a blueprint for creating objects. Used to define new types e.g. Boolean, list.
- E.g. list_ex = [1,2,3]
- List_ex.append() etc 
- Class Name:
- def method_name(self):
- name = Name()
- name.method_name()
- Constructors
- Function that gets called when object is initialized
- Class Name:
- def __init__(self, x):
- self.x = x access attributes/variables
- def method_name(self):
- name = Name(7)


### Functions

### Objects
- OO approach – see complex system as a series of simpler objects. 
- Objects contain data + operations (do stuff). Objects can refer to other objects. 
- What is an Object?
- An object is an instance of a class and consists of:
- State  the properties or data of the object (e.g., instance
- variables like `self.data`).
- Behavior  the methods (functions) the object can perform.
- Identity  each object has a unique identity (memory address),
- even if its contents are the same as another object.
- The `__init__` Method
- When creating an object, the `__init__` method initializes instance
- attributes, which are specific data attached to each object.

-	Essence of design is describing a system in terms of magica black boxes and htei interfaces. Other components are users or clients of the services
-	Black box just has to make sure the service is faithfully delivered. Separation of concern is what makes deisgn of comple sysems possible.
-	Magic behind objects lies in class definition. Once a suitable class definition has been written we can ignore how the class works. Just rely onexternal interface – the methods. 
-	We don’t need to know all the way to the bottom to use the class. 
-	Most computer programs are built using OO approach – see complex system as a series of simpler objects.  Objects contain data + operations (do stuff). Objects can refer to other objects.
-	Create a new instance a class – constructor. object_anme = Class_name(param)
-	To perform an operation on the object we send the object a message. Object.(method). Every object is an instance of some class. It is the class that determines what method an object will have. 
-	We have to avoid aliasing where two variables refer to the same object. Use a clone instead. Methods that change the state of an object are called mutatrors
-	Object oriented design
-	Essence of design is describing a system in terms of magica black boxes and htei interfaces. Other components are users or clients of the services
-	Black box just has to make sure the service is faithfully delivered. Separation of concern is what makes design of compile systems possible.
-	Magic behind objects lies in class definition. Once a suitable class definition has been written we can ignore how the class works. Just rely onexternal interface – the methods. 
-	We don’t need to know all the way to the bottom to use the class 
-	Encapsulation
-	Polymorphism

 


### Compiled languages
Translate a high-level programming language to machine language that a computer can understand can be done in two ways: compile or interpret. High level languages are portable, but the machine language is custom for that CPU. A program that works for Intel CPU won’t work on ARM CPU. On the other hand, as long as we have the interpreter or compiler we need we can run our language on any CPU.
A compiler – translates the high level into machine language of a computer. Once it’s been compiled the code can be run again and again without a need to compile. 
 
### Interpreted languages
An interpreter – analyses and executes the source code instruction by instruction as necessary. Interpreter and source are needed every time the program runs. 

Lots of people are scared of coding. At work people walk by my screen and are too scared to look at code. They imagine the old sci-fi picture of a nerdy kid looking at 1s and 0s. This is far from the truth. Coding is much like writing. 



