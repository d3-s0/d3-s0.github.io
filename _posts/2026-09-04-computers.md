---
layout: post
title:  "How do Computers work?"
date:   2026-09-04 20:30:00 +0100
categories: jekyll update
---

Let’s break down the computer into its fundamental components:
* [Central Processing Unit (CPU) ](#cpu)
* [RAM (random access memory)](#ram)
* [Mother board](#mother-board)
* [OS](#os)

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

# Motherboard	
The motherboard is like the skeleton of the PC, connecting all the "thinking" units together. Motherboards comes in three different sizes: ITX, Micro ATX and ATX. There are two main motherboard brands based on CPU brand: AMD and Intel withs specific socket types. Case sizes come in sizes corresponding to the motherboard form factors, suchas micr-ATX, ATX and E-ATX.
 
# OS
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


# Software


## Databases 
- A database is a self-describing collection of integrated records:
- Self-describing: contains metadata
- Integrated: contains relationships
- Records: contain attributes
- SQL databases are stored as specific files on your computer's hard drive or SSD. Linux: /usr/local/var/mysql/
- Main Types:
- Relational Databases (SQL): structured data (PostgreSQL, MySQL, SQLite)
- Non-relational Databases (NoSQL): unstructured data
- SQLAlchemy Components:
- Engine: database connections
- Session: manages conversations with database
- Metadata: stores table definitions
- Creating and Maintaining a Proper Database
- SQL basic queries
- SELECT
- Data modification
 
## Compiled languages
Translate a high-level programming language to machine language that a computer can understand can be done in two ways: compile or interpret. High level languages are portable, but the machine language is custom for that CPU. A program that works for Intel CPU won’t work on ARM CPU. On the other hand, as long as we have the interpreter or compiler we need we can run our language on any CPU.
A compiler – translates the high level into machine language of a computer. Once it’s been compiled the code can be run again and again without a need to compile. 
 
## Interpreted languages
An interpreter – analyses and executes the source code instruction by instruction as necessary. Interpreter and source are needed every time the program runs. 

