---
layout: post
title:  "computers"
date:   2001-02-05 00:32:00 +0000
categories: jekyll update
---

# Programming
Programs are just a sequence of instructions telling a computer what to do. The problem with human language is that it’s ambiguous. We only understand each other because we share a lot of common knowledge and experience. Even then we struggle with communication. Computers require clear instructions on what to do. Computer scientists circumvented this problem by making special notations for everything that can be computed – called programming languages. Every structure in programming languages has a precise form (syntax) and precise meaning (semantics). These languages are called High level programming languages because they are designed for humans.  Computers though can only understand machine language and eventually in binary.

### Basics - variable, types, operators
Variables= Holds the data
Data types
- Types: int, floats, string, Boolean, char, null or none, 
- Data structures
- Lists or arrays
- Dicts or maps
- Sets (unique values)

Operators
- Arithmetic (=,+,-,)
- Comparison (<,>)
- Logical (and, or)

### Control - if, for, while

#### Conditional – if
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

### Data storage - lists, dicts, 
- Lists or arrays
- Dicts or maps
- Sets (unique values)
- Data structures - lists
- Encryption : the process of encoding information for the purpose of keeping it secret or transmitted it privately is called encrypton. 
- To decrypt a. message- party receiving the message needs o have a key so encoding can be reversed.  Keys can be public or private. 
- Public systems – encryption keys are public – anyone can send a messge using key but only the other part will have decryption key to decipher it. 
- Files – text files can be iterated through lines wih a for flop  using read, readline, readlines
- Simple version of program or program component and try to gradually add features until it meets spec 
- Mini cycles through the dev process as prototype is incrementally expanded into final program
- Data structures - Dictionaries
- Editing Dictionaries
- Replacing a value

### Functions

Lets you repeat instructions - reusable instructions

### OOP

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




 


# Git

# How computers work

#### CPU
At the heart of every computer is an integrated circuit called a CPU. It communicates with the computer's main memory, input devices, and output devices. 

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
 


