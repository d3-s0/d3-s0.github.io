---
layout: post
title:  "Computers"
date:   2026-09-04 20:30:00 +0100
categories: jekyll update
---

Let’s break down the computer into its fundamental components:
•	Central Processing Unit (CPU) 
•	RAM (random access memory)
•	HDD magnetic patterns on a spinning disk or SSD electronic circuits
•	Motherboard
•	Graphical Processing Unit (GPU)
•	Case
•	Power supply unit (PSU)

# CPU
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
 

# RAM
RAM comes in sizes like 4gb, 8gb, 16gb, and 32gb, and it is essential for temporary data storage during active tasks.
PSU
The PSU converts electrical power from your home's AC outlet into direct current (DC) that your PC components require. Efficiency is important because it determines how much power is converted to DC.
Storage
For storage, Solid state drive (SSD) uses flash memory to store data even when  power is off. Unlike hard drives, SSDs have no moving parts, making them faster and more durable. Case sizes come in sizes corresponding to the motherboard form factors, such as  micro-ATX, ATX and E-ATX.
GPU
The GPU renders images and videos. It has many cores and dedicated memory for processing graphics, making it excellent at parallel processing. Popular GPU brands are NVIDIA, AMD and Intel.

# Mother board	
The motherboard is like the skeleton of the PC, connecting all the "thinking" units together. Motherboards comes in three different sizes: ITX, Micro ATX and ATX. There are two main motherboard brands based on CPU brand: AMD and Intel withs specific socket types. Case sizes come in sizes corresponding to the motherboard form factors, suchas micr-ATX, ATX and E-ATX.
 
# The OS
Okay we have the hardware ready. How does it go into becoming the software?
1.	PSU powers the motherboard: The Power Supply Unit sends a steady electrical current across the motherboard circuits.
2.	BIOS/UEFI wakes up: This electricity activates a permanent flash memory chip containing the computer's very first software instructions.
3.	BIOS searches for the OS: The BIOS software looks for data indicating where the Operating System is installed.
4.	Motherboard reads storage: The motherboard scans your permanent storage drives (HDD or SSD) to locate this data.
5.	Bootloader is located: The motherboard finds a specific sector on the drive containing a tiny software program called the Bootloader.
6.	Bootloader copies the OS: The Bootloader copies the heavy Operating System files from your slow permanent storage.
7.	Data loads into RAM: The Bootloader pastes these files directly into your high-speed, temporary Random Access Memory.
8.	CPU bypasses storage: The CPU uses the RAM as an immediate workspace because reading directly from an HDD or SSD is too slow.
9.	OS takes total control: The Operating System fully loads from RAM, activates, and launches your desktop user interface.
10.	CPU processes code: The CPU reads digital instructions from the RAM billions of times per second to run your desktop.
11.	GPU renders graphics: The CPU hands visual tasks to the Graphics Processing Unit to display images on your screen.
12.	System manages future apps: When you open a new app, the OS fetches it from the SSD, places it in RAM, and tells the CPU to execute it
Once computer loaded you might run script. This is what happens:
1.	Script loads into RAM: The OS locates your script file on the SSD/HDD and copies the text code into the RAM.
2.	Interpreter or Compiler activates: The OS launches a specific software tool (like the Python interpreter or a C++ compiler) to handle your script.
3.	Code is checked for syntax: This tool reads your script text to ensure there are no formatting mistakes or spelling errors.
4.	Text translates to Machine Code: The tool translates your high-level language (like print("Hello")) into binary machine code consisting entirely of 1s and 0s.
5.	Instructions enter CPU cache: The OS pushes these binary instructions from the RAM into the ultra-fast, internal cache memory of the CPU.
6.	CPU fetches the instruction: The CPU Control Unit grabs the first binary instruction from the cache.
7.	CPU decodes the binary: The CPU breaks down the 1s and 0s to identify exactly what operation needs to be performed (such as adding numbers or moving data).
8.	ALU executes the calculation: The Arithmetic Logic Unit (ALU) inside the CPU processes the mathematical calculation or logic operation.
9.	Registers store instant results: The CPU saves the immediate, tiny output of that calculation into its internal, hyper-fast storage slots called Registers.
10.	Results write back to RAM: The CPU sends the final calculated data back out to the RAM so the Operating System can use it.
11.	OS outputs the result: The OS takes that data from RAM and commands the GPU to display the text output on your screen, or commands the SSD to save a new file. 
 

 
# Internally in RAM (The Organization)
As the script runs, Python organises RAM into two main areas: 
•	The Heap: This is where the actual "objects" (numbers, strings, lists) live. If you create x = 10, an object for the number 10 is created here.
•	The Stack: This stores "pointers" or memory addresses—think of them as GPS coordinates—that tell the CPU exactly where in the Heap to find your data. 
A memory address is a unique numeric identifier for a specific location in your computer's RAM. 
Think of RAM as a massive apartment complex; the memory address is the specific room number where an object lives. 

 
