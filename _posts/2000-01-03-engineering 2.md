---
layout: post
title:  "engineering: computers"
date:   2000-01-03 00:32:00 +0100
categories: jekyll update
---

* [computer systems](#computer-technology)
* [programming languages](#programming-languages)

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



