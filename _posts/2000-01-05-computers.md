---
layout: post
title:  "computers"
date:   2000-01-05 20:30:00 +0100
categories: jekyll update
---

Data Science
1. [The problem](#step-1-problem)
2. [Explore](#step-2-explore)
3. [Build model](#step-3-build-model)
4. [Evaluate model](#step-4-evaluate-model)
5. [Visualisation](#step-5-visualisation)

Programming languages
* [Variables](#variables)
* [Operators](#Operators)
* [Control flow](#control-flow)
* [Functions](#functions)
* [Databases](#databases)

Theory
* [Statistics & Probability](#statistics)
* [Calculus](#calculus)
* [Optimisation](#optimisation)

Projects
1. [Project planning](#project-planning)
2. [Convincing stakeholders](#convincing-stakeholders)
3. [Running the project](#running-the-project)
4. [Finishing the project](#finishing-the-project)
5. [Presenting results of project](#presenting-the-results)

Computer hardware
* [Central Processing Unit (CPU)](#cpu)
* [RAM (random access memory)](#ram)
* [Mother board](#mother-board)
* [OS](#os)

 
# Programming languages
## Compiled languages
Translate a high-level programming language to machine language that a computer can understand can be done in two ways: compile or interpret. High level languages are portable, but the machine language is custom for that CPU. A program that works for Intel CPU won’t work on ARM CPU. On the other hand, as long as we have the interpreter or compiler we need we can run our language on any CPU.
A compiler – translates the high level into machine language of a computer. Once it’s been compiled the code can be run again and again without a need to compile. 
 
## Interpreted languages
An interpreter – analyses and executes the source code instruction by instruction as necessary. Interpreter and source are needed every time the program runs. 

Lots of people are scared of coding. At work people walk by my screen and are too scared to look at code. They imagine the old sci-fi picture of a nerdy kid looking at 1s and 0s. This is far from the truth. Coding is much like writing. 

Programs are just a sequence of instructions telling a computer what to do.
The problem with human language is that it’s ambiguous. We only understand each other because we share a lot of common knowledge and experience.  Even then we struggle with communication.  Computer scientists circumvented this problem by making special notations for everything that can be computed – called programming languages. Every structure in programming languages has a precise form (syntax) and precise meaning (semantics). These languages are called High level programming languages because they are designed for humans. Computers though can only understand machine language and eventually in binary. There are two ways for your code to get to binary machine code (0,1)

## Variables
Holds the data

### Constants
### Data types
- Types: int, floats, string, Boolean, char, null or none, 

Data structures
- Lists or arrays
- Dicts or maps
- Sets (unique values)

## Operators
- Arithmetic (=,+,-,)
- Comparison (<,>)
- Logical (and, or)

## Control flow
Conditional – if, else
- Aim: minimize the number of checks the computer performs:
- Place the most likely case first: Put the condition most likely to be true at the top of an if/elif chain so Python can skip subsequent checks immediately.
- Put "cheap" checks before "expensive" ones: Evaluate simple comparisons (e.g., x == 0) before complex ones like function calls or database lookups.
- Avoid deep nesting: Use the "Guard Clause" pattern—exit early from a function if a condition isn't met—to keep code flat and avoid redundant evaluations.


### Loops (for, while)
- Over a list of values
- Range()  builds a sequence of numbers
- List() makes it into a list
- Loops – efficient for loops
- To make loops efficient in Python, the best strategy is often to  avoid them entirely by using built-in functions or vectorization. If you must use them, you should minimize "overhead"—the extra work Python does to look up variables and function

List comprehensions are generally faster than traditional for loops with .append()because they are optimized at the C-level and use a specialized bytecode instruction (LIST_APPEND) to build the list in one go. 
- Python's built-in functions like sum(), max(), and min() are implemented in C and are significantly faster than writing a loop to do the same calculation manually


## Data structures
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



## Conditional and Loops
- Operators 
- Arithmetic (=,+,-,)
- Comparison (<,>)
- Logical (and, or)
- Conditionals (if, else)
- Loops (for, while)
- Limitations of code – adding
- Limitations of computer doing maths. Machine ints aren’t like th emathematical integers. There are infinite integers but ifnite range of ints. Ints are streod in fixed range of ints in the computer. Computer memory is composed of switches – on or off (1,0). A sequence of bits can represent more possibiolties. With two bits you can do 4 presenttaions. 00,01,1,0,11. Each extra bit doubles number of patterns. 2n values. The number of bits that a particular computer uses to represent an int depends on design of CPU. Computers now adays use 32 or 64 bits. For a 32 bit CPU, 232 possible values. These values centered at 0 to rppesent a range of pos + veg values so we diivde by 2. 231. Range of integers that a 32-bit int value is -231 to 231 -1 (-1 to account ofr representation of 0 in the top half of the range)
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


## Functions

## Objects
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

 


TODO:
- are compiled languages always faster than interpreted language
- Why are databases are so fast and pandas not as fast?




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




# Databases 
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







The modern age is the time of Big Data. Data science is processing the data into evidence-based conclusions using data. 

# Step 1: Problem
1.	What problem are you trying to solve? 
2.	Who is your audience?
3.	What do you need them to know/do?
4.	What background information is relevant or essential?
5.	What do we know about them?
6.	What would a successful outcome look like?
 

# Step 2: Explore 
Obtain access to all datasets. Ingest data into analysis environment. Review dataset structure. Verify data types. Understand variable definitions. Identify data quality issues. Visualise distributions. What data is relevant? 

Descriptive statistics: 
- Centrality measures: Mean, median, mode
- Variability measures: std, variance, range
- Explore feature-target relationships.
- Create scatter plots, boxplots and heatmaps.
- Identify anomalies or outliers.

# Step 3: Build model
- Start with simple baseline models.
- Increase complexity only when justified.
- Train models.
- Run experiments.

Machine learning is creating models that learn from data. ML is applying statistical or CS methods on data to:
Draw casual insights 
Predict future events
Understand patterns

Artificial Intelligence (AI) is a broad field which captures anything that does tasks requiring human intelligence. Machine Learning (ML): A subfield of AI, that makes models using training data. 

Deep Learning: A subfield of ML - uses multi-layered artificial neural networks for complex data understanding. AI is the effort to automate intellectual task normally performed by humans. Ada lovelace remarked how the analytical engine could be used for whatever we know


Alan turing introduced the turing test. He thought computers could emulate all aspects of human intelligence
Machine learning looks at the input data and answers, figures out what the rules/patterns should be
Machine learning vs statistics
Machine learning deals with big data – for which classical stat analysis such as Bayesian analysis would be impractical.
ML is driven by empirical findings and advanced software
ML has little mathematical theory
Machine learning	
Machine learning needs 3 things:
Input data points
Examples of expected outputs
Way to evaluate performance of model
Machine learning is learning useful representations of input data, that get us closer to expected output

Supervised 
Categorical (Classification Models) – predicts categories
Predicts discrete labels or classes (e.g., Spam vs. Not Spam).
Primary Models: Logistic Regression, Naïve Bayes.
Versatile Models: kNN, SVM, Decision Trees, Random Forest, Gradient Boosting, Neural Networks.
Continuous (Regression Models) – predicts numbers
Predicts numerical, real-valued outcomes (e.g., House Prices).
Primary Models: Linear Regression, SVM Regression (SVR).
Versatile Models: Decision Trees, Random Forest, kNN, Gradient Boosting, Neural Networks. 

Categorical (Classification Models)
Classification models are used when the goal is to predict a discrete labelor category. For example, determining if an email is "Spam" or "Not Spam". 
Primary Models (Strictly for Classification):
Logistic Regression: Despite its name, it is a classification tool. It calculates the probability (0 to 1) that an input belongs to a specific class.
Naïve Bayes: Based on Bayes' Theorem, it assumes all input features are independent. It is exceptionally fast and often used for text and sentiment analysis.
Versatile Models (Used for Classification):
k-Nearest Neighbors (kNN): Classifies a new data point based on the majority label of its "K" closest neighbors in the dataset.
Support Vector Machines (SVM): Finds the best boundary (hyperplane) that separates different classes with the widest possible margin.
Decision Trees: A flow-chart-like structure where each "node" represents a choice based on data features, leading to a final classification.
Random Forest: An "ensemble" method that builds many decision trees and combines their results (majority vote) to improve accuracy.
Gradient Boosting: Builds trees sequentially, where each new tree specifically tries to correct the errors made by previous ones.
Neural Networks: Complex layers of "neurons" that mimic the human brain to find patterns in massive datasets, like recognizing faces in images. 
2. Continuous (Regression Models)
Regression models predict a numerical value rather than a category. For example, predicting a house's price might be 450,000. 
Primary Models (Strictly for Regression):
Linear Regression: Fits a straight line through data points to find the relationship between inputs and a continuous numerical output.
SVM Regression (SVR): A version of SVM that finds a boundary containing as many data points as possible within a specific error range.
Versatile Models (Used for Regression):
Decision Trees & Random Forest: Instead of a class label, the "leaf" of the tree provides the average value of the data points in that group.
kNN: Predicts a value by taking the average (mean) of the values of the "K" nearest neighbors.
Gradient Boosting: Sequentially adds trees to minimize the overall prediction error of numerical values.
Neural Networks: Use their complex layers to map inputs to a specific, real-world numerical output, such as weather forecasting or stock trends. 
Supervised learning
Features – Qualitative data  – categorical data
Nominal data (no inherit order within data)
Nominal -> one hot encoding -> computer
If matches category make 1 otherwise make 0
Ordinal data (inherit order)
Give good/bad numbers for the order
Quantitative data
Numbers 
Supervised learning tasks
Classification – predict discrete classes
Regression – predict continuous values
Preparing the data
Column – features
Output label – target for feature vector
Feature vector – all features in one sample – one row
All data is feature matrix
Target vector
Each row is fed into model
Plot the features against target to see the data
We don’t want to feed our model all the data
Training dataset
Validation dataset
Testing dataset
Preparing data
We need to make target a number not a string
Can encode it
Then view the data
Split the data into train, val, test
Normalise data using scaler
Preparing the data


Scale the data so data is normalized to the data in that column
You may need to oversample your training data if the
You oversample when class counts are very different so the model does not “ignore” the minority class and become biased toward the majority class.
With imbalanced data, a classifier can get high overall accuracy by mostly predicting the majority class, while performing very poorly on the minority class

## Linear regression

kNN
Euclidean distance = length of point to neighbours
K = how many neighbours we use to judge  e.g. 3,5 
we find the 3 closest points and base of the majority of those


## Naïve Bayes
Naive Bayes is a machine learning classification algorithm that predicts the category of a data point using probability. It assumes that all features are independent of each other.
The main idea behind the Naive Bayes classifier is to use Bayes' Theorem to classify data based on the probabilities of different classes given the features of the data.
The algorithm is "naive" because it makes one huge assumption: all features are independent of each other
he foundation of Bayes theorem is conditional probability 
Logistic regression

It is a type of classification algorithm that predicts a discrete or categorical outcome.
Logistic regression model transforms the linear regression function continuous value output into categorical value output using a sigmoid function which maps any real-valued set of independent variables input into a value between 0 and 1
Logistic regression then applies the sigmoid function to zto convert it into a probability between 0 and 1 which can be used to predict the class.
Support Vector Machine (SVM)

Plot your data points.
Find the boundary that keeps the biggest distance from the closest points.
Use a "Kernel" to warp the space if a straight line won't cut it.
Gradient boosting
Gradient Boosting like a golf player trying to sink a hole-in-one.
The First Swing: You take a shot. It’s not great; the ball lands 50 yards away from the hole.
The Feedback: You don't start over. Instead, you look at the gap (the error) between the ball and the hole.
The Correction: You take a second, smaller swing specifically designed to cover that 50-yard gap.
Repeat: If you're still 5 yards off, your third swing is just a tiny tap to fix that specific mistake.
Gradient Boosting builds them one by one. Each new tree is specifically designed to correct the errors (called residuals) of the entire ensemble created so far. 
How the Algorithm Works (Step-by-Step)
Initialize the Model: Start with a simple "base" prediction, which is typically the mean of the target values for regression.
Calculate Residuals: Find the difference between the actual values and the current model's predictions.
Train a Weak Learner: Build a new decision tree that predicts these residuals instead of the original target.
Update Predictions: Add the new tree's predictions to the existing model, scaled by a learning rate (also known as "shrinkage") to prevent overfitting.
Repeat: Iterate through steps 2–4 for a set number of trees (e.g., 100 or 1,000). 
Gradient boosting
XGBoost fits prominently in the gradient boosting category of the ML world
handles non-linear patterns, interactions, and missing values natively
XGBoost, short for eXtreme Gradient Boosting, is a highly optimized implementation of gradient boosting machines in machine learning. It excels as an ensemble method that builds sequential decision trees to correct errors from prior trees, delivering top-tier performance on structured/tabular data
 
## Unsupervised 
The model analyzes unlabelled data to identify hidden patterns, structures, or groupings without human guidance
Clustering: Groups similar data points together.
Techniques: K-Means, Hierarchical Clustering, DBSCAN. 
Dimensionality Reduction: Simplifies large datasets by compressing features while retaining critical information.
Techniques: Principal Component Analysis (PCA), t-SNE.
Anomaly Detection: Identifies rare items or unusual observations that deviate from the norm.
Techniques: Isolation Forests, One-Class SVM
 
## Deep learning

Deep stands for successive layers of representation
Layered representation are learned via models called neural networks
Deep learning does input-target mapping via deep sequence of simple data transformations (layers)
Neural network is a bad name -> layered representations learning
A neural network architecture is the layered structure of interconnected artificial neurons (nodes) that process data, typically consisting of an input layer, one or more hidden layers, and an output layer, meaning is derived from pair-wise relationship between things (between words in a language)
Vectorisation
Everything is a vector – point in geometric space
Vectorisation: E.g. Cat and dog pics become dots floating in a giant room. 
The problem is they are all mixed up. We can’t separate them.
Target space
We want the dog dots on one side and cat dots on other side
Layers (the folding)
Each layer is like a hand that goes in and moves the space e.g. tug, stretch, fold
Weights are how hard to pull or where to fold (”Settings”)
Learning (The correction)
At first, it’s a bit retarded and gets it wrong -> we then tell it got it wrong via the Loss function
The adjustment (gradient descent): because it’s differentiable, we can see which fold got it wrong. We chang the weights by a bit to make fold better
Rinse and Repeat, until folds are perfect

Loss score to optimizer
The trick is using the loss score to adjust he weights that will lower the loss score 
The adjustment is the job of the optimizer which carries out the backpropagation algorithm
Deep learning vs Machine learning 
ML is used on small amounts of data while DL needs a lot of data
ML needs human to point out important features
DL needs powerful GPUs
DL is often a black box 
Deep learning workflow
Define the problem: What data is available? What are you trying to predict?
How to measure success?
Prepare validation process that you’ll use to evaluate the models. 
The four horsemen of architectures
Densely connected networks
Convolutional networks
Recurrent networks
Transformers
Limitations of deep learning
Anything that requires reasoning e.g. programming, scientific method
Deep learning is just a chain of simple, continuous geometric transformations 
What enabled deep learning?
Fast GPUs (NVIDIA)
Lots of internet data
Backpropagation
Keras and tensorflow
Deep learning benefits
Near human level image classification
Near human level speech transcription
Near human level hand writing transcription
Text to speech conversion
Digital assistants
Automonous driving 
Improved search results
Ability to answer natural language questions




# Step 4: Evaluate model
Assess performance metrics.

- Categorical (Classification)
- Confusion matrix
- Accuracy 
- Precision 
- Recall
- F-score
- Area under curve
- Log loss
- Continuous (Regression) 
- Absolute error
- Squared error
- Measured square error
- Root mean square error
- Absolute error distribution
- Residual sum of squares

# Step 5: Visualisation

The main plots
- Table: Reading precise individual values.
- Heatmap: Spotting patterns using colour intensity.
- Scatter plot: Showing relationships between two variables.
- Line plot: Tracking continuous data over time.
- Slope graph: Showing relative changes between two points.
- Vertical/Horizontal bar: Comparing categorical data quickly.
- Histogram: show distribution of continuous numerical data in bins
- Stacked Vertical/Horizontal bar: Showing part-to-whole relationships over time.
- Waterfall: Showing a running total after additions/subtractions.


## The main plots
* [Table](#tables)
* [Scatter graph]()
* [Line graph]()
* [Bar chart]()
* [Heatmap]()
* [Histogram]()

- Table: Reading precise individual values.
- Heatmap: Spotting patterns using colour intensity.
- Scatter plot: Showing relationships between two variables.
- Line plot: Tracking continuous data over time.
- Slope graph: Showing relative changes between two points.
- Vertical/Horizontal bar: Comparing categorical data quickly.
- Histogram: show distribution of continuous numerical data in bins
- Stacked Vertical/Horizontal bar: Showing part-to-whole relationships over time.
- Waterfall: Showing a running total after additions/subtractions.

## Tables 
Communicating to a mixed audience whose members will each look for their particular row of interest. If you need to communicate multiple different units of measure, this is also typically easier with a table than a graph
- Tables are used when you want to put your data into an array. 
- Tables allow you to list multiple variables in 2 dimensions. 
- Add organisation levels to the table and avoid repeated heading text. Use bold to highlight particular columns like totals.

## Graphs - scatter
- Allow you to encode both x and y axis to see what relationship lies
- You can have scatter plot with free spreads of dependant variable values
- Dependant values restricted to whole numbers
- Scatter plot with dependant tested in triplicate, observations averaged and error bars added. Lines of best fit for scatter plots 
-  What relationship are you trying to show?
- If you increase one, will the other increase steadily
- A line of best fit shouldn’t go through abnormabilties if they can’t be explained in real world
- Line of best fit tells the reader you have some predictive power

## Graphs - line
- Used to plot continuous data. Because the points are physically connected via the line, it implies a connection between the points that may not make sense for categorical data
- Often, our continuous data is in some unit of time: days, months, quarters, or years
- Slopegraphs can be useful when you have two time periods or points of comparison and want to quickly show relative increases and decreases or differences across various categories between the two data points
Graphs - bars
- Bars are best for where information is organized into groups.
- Note that, because of how our eyes compare the relative end points of the bars, it is important that bar charts always have a zero baseline
- a common decision to make is whether to preserve the axis labels or eliminate the axis and instead label the data points directly. In making this decision, consider the level of specificity needed. If you want your audience to focus on big‐picture trends, think about preserving the axis but deemphasizing it by making it grey. If the specific numerical values are important, it may be better to label the data points directly. In this latter case, it’s usually best to omit the axis to avoid the inclusion of redundant information. 
- Always consider how you want your audience to use the visual and construct it accordingly.

## Horizontal bar chart - go‐to graph for categorical data
- The horizontal bar chart is especially useful if your category names are long, as the text is written from left to right, as most audiences read, making your graph legible for your audience there isn’t a natural ordering in your categories that makes sense to leverage, think about what ordering of your data will make the most sense.
- Because of the way we typically process information—starting at top left and making z’s with our eyes across the screen or page—the structure of the horizontal bar chart is such that our eyes hit the category names before the actual data
- Bar charts: frequency or magnitude of a categorical value. Make sure the graph actually adds something.
- Histograms: show frequency distribution
- Graphs - waterfall
- The waterfall chart can be used to pull apart the pieces of a stacked
- bar chart to focus on one at a time, or to show a starting point,
- increases and decreases, and the resulting ending point

## Quality graph
- Units
- Axes and titles
- Figure number and caption. Caption should fully explain data
- Legend
- Error bars

Choosing an effective visual – secondary y
- Quality image
- Labels and sub labels
- Images in line 
- Extra lines to help identification of data or areas of interest
- Scale bar
- Caption does not interpret the data – just states it
- Colour blind compatible 
- You can also use panels – multi panel figure with different plots
- Clutter is your enemy
- Every single element you add to your plot takes up cognitive load
- Good design means audience doesn’t even notice it

## The Gestalt Principles of Visual Perception
- Step by step
- Remove chart border
- Remove gridlines
- Remove data markers
- Clean up axis labels – use three letters for month.
- Label data directly
- Leverage consistent colour – similarity – label same as data
- White space
- Alignment
- Focus your audience’s attention	

## How to direct audience attention
- Pre-attentive attributes: size, colour, position can be used to 1) direct audience attention and 2) give a visual hierarchy of elements. attention process: stimulus -> eyes -> brain your brain does most the work.
- brain has 3 memory types for visual: iconic, short-term and long term memory iconic is tune to a set of preattnetive attributes
- short term: max 4 chunks of visual info at a time. we don’t want audience to work to get information out or we label various data points directly (reducing load). Generally we want to form larger chunks to meet the cap of only 4 things we can handle.
- long term: aggregate of visual and verbal memory. combine visual and verbal memory to trigger formation of long term memory. If we show a picture of queen a flood of memories come in.
- Using preattentive attributes to make it allow audience see the what we want them to see before they even know they’re seeig it.
- orientation
- shape
- length
- width
- size
- curvature
- added marks
- enclosure
- hue
- intensity
- spatial position
- motion

We have about 3-8 seconds with audience: use it to give clear visual hierarchy. Interpret the
data yourself. You should have a specific story. Then ask a question for discussion. Leverage
pre-attentive attributes. Go further and give text and focus. Note: if you highlight one aspect, the other aspects become harder to see.
- 1. Push everything to the background
- 2. Make explicit decision on what’s important.
- 3. Be strategi which and which markers, labels you include - "look here!"
- 4. Colour - make it grey then add a single colour to draw attention. use blue!
- 5. Focus your audience attention where you want them to pay it

## Think like a designer
Form follows function. What we want our audience to do with the data? (function) affordances
- The design makes it obvious how the product is to be used e.g knob looks like it’s for turning
- Accessibility and aesthetics.
- Not all data are equally important. Use your space and audience’s attention wisely by getting rid of noncritical data or components.
- When detail isn’t needed, summarize. You should be familiar with the detail, but that doesn’t mean your audience needs to be.
- Consider whether summarizing is appropriate.
- Ask yourself: would eliminating this change anything? No? Take it out! Resist the temptation to keep things because they are cute or because you worked hard to create them; if they don’t support the message, they don’t serve the purpose of communication.
- Push necessary, but non‐message‐impacting items to the background. Use your knowledge of preattentive attributes to deemphasize. Light grey works well for this.

## What is the story?
- Then something happens—an event that throws things out of balance
- “Subjective expectation meets cruel reality.”
- The imbalance: Why is it necessary, what has changed?
- The balance: What do you want to see happen?
- What does my protagonist want in order to restore balance in his or her life? 
- What is the core need? 
- What is keeping my protagonist from achieving his or her desire? 
- How would my protagonist decide to act in order to achieve his or her desire in the face of those antagonistic forces?
- The solution: How will you bring about the changes?
- Do I believe this? 
- Is it neither an exaggeration nor a soft‐soaping of the struggle?
- Is this an honest telling, though heaven may fall?
- Further develop the situation or problem by covering relevant background.
- Incorporate external context or comparison points.
- Give examples that illustrate the issue.
- Include data that demonstrates the problem.
- Articulate what will happen if no action is taken or no change is made
- Discuss potential options for addressing the problem.
- Illustrate the benefits of your recommended solution.
- Make it clear to your audience why they are in a unique position
- to make a decision or drive action.
- What motivates your audience? making money, beating the competition, gaining market share, saving a resource, eliminating excess, innovating, learning a skill, or something else

## Story Resolution
- End with a call to action: make it totally clear to your audience what you want them to do with the new understanding or knowledge that you’ve imparted to them
- Types: tie it back to the beginning – recap problem,  resulting need for action
- Narrative structure
- The order in which the story is told
- Ideal = powerful narrative + effective visuals
- Understand the audience
- Are they a busy audience who will appreciate if you lead with what you want from them? 
- Or are they a new audience, with whom you need to establish credibility? 
- Do they care about your process or just want the answer? 
- Is it a collaborative process through which you need their input? 
- Are you asking them to make a decision or take an action? 
- How can you best convince them to act in the way you want them to? 
- Narrative structure - Order of the story	 
- Chronologically: take audience through same path we experienced it. Great if they care about process + building credibility.
- Lead with ending: start with call to action – what audience needs to know or do. Then back up into support. Works if you already have credibility + they care about ”so what” + care less about process.

## Repetition
- Give a summary slide at the start with main points of story. Organise slides to be in that order. Repeat summary at the end with emphasis on actions.
- Horizontal logic
- Just the slide title and the story should make sense
- Action titles not descriptive titles
- Exec summary with title slide titles
- Vertical logic
- All information on a slide is self-reinforcing 
- The words reinforce the visual, title and vice versa. No fat.
- Reverse story boarding
- Take final communication, flip through it, write main point
- Fresh perspective
- Give it to a friend with no context
- What they pay attention to, what they think is important
- Histograms: check distribution of a variable
- Scatter plots: dependency between two variables
- Maps: show distribution on a map
- Heat pump: dependency between multiple variables
- Time series plots: identify trends over time

 


# Statistics
- Descriptive Statistics: Summarizing data using measures of central tendency (mean, median, mode) and dispersion (variance, standard deviation, interquartile range).
- Probability Theory: Understanding sample spaces, conditional probability, and Bayes' Theorem for classification and updating beliefs with new data.
- Probability Distributions: Recognizing common distributions such as Binomial, Poisson, Normal (Gaussian), and Uniform.
- Inferential Statistics: Using sample data to make inferences about a larger population through confidence intervals and p-values.
- Hypothesis Testing: Conducting Z-tests, T-tests, and Chi-Square tests to validate assumptions and measure significance.
- Modeling & Inference: Working with linear regression, generalized linear models (GLMs), maximum likelihood estimation (MLE), and the Central Limit Theore


Collecting and analysing data. Statistics analyses the past to find insights. Probability predicts the future.

Statistics looks at the collection, analysing, interpreting, and presenting of past data. The two main types of statistics are:
- Descriptive statistics: summarise and describing the data. 
- Inferential statistics: sample data to make inferences about larger population.

Types of data
Numeric (quantitative) vs categorical(qualitative)
Numeric – continuous(measured) and discrete data
Categorical – unordered and ordered/ordinal (e.g. agree, disagree)
Numerical data – summary statistics

Descriptive Statistics
Descriptive statistics are used to organise and summarise data.
Measures of center: mean, median, mode.
Measures of spread: range, variance, standard deviation, interquartile range.
Visual summaries: histograms, scatter plots, and box plots

Measures of center
Mean is sensitive to extreme data so good for symmetrical 
Median is better for skewed data 
Left skewed means data is on the right

Inferential Statistics
Using sample data to make accurate predictions or decisions on a larger population.

# Probability
Probability measures how likely an event is to occur, ranging from 0 to 1.
Sample space: all possible outcomes.
Events: one or more outcomes from the sample space.
Basic rules: addition, multiplication, and complement laws.
Types of events: independent (no influence), mutually exclusive (cannot happen together).
Conditional probability and Bayes’ theorem for updating probabilities.
Counting and Combinatorics
Counting methods help calculate probabilities when many outcomes exist.
Permutations: arrangements where order matters.
Combinations: selections where order does not matter.
Types of Probability
Theoretical: Based on logical reasoning (e.g. a fair coin has 1⁄2 chance of heads).
Experimental (empirical): Based on data from experiments or past events.
Subjective: Based on opinion or belief (e.g. a fan says their team has an 80% chance to win).
Random Variables and Distributions
Random variables can be discrete or continuous.
Described using probability mass (pmf) or density (pdf) functions.
Common distributions: binomial, Poisson, uniform, exponential, and normal (Gaussian).
Key measures: mean, variance, and standard deviation.


# Linear algebra
Vectors: Ordered lists of numbers that represent both magnitude and direction. 
Matrices: Rectangular arrays of numbers used to store data or represent linear transformations. The transformation takes a vector and makes it into another vector.

- Data Structures: Representing tabular data, images, text, and neural network weights as scalars, vectors, matrices, and tensors.
- Matrix Operations: Performing addition, subtraction, transposition, dot products, and matrix multiplication.
- Linear Transformations & Systems: Solving linear equations using matrix inverses, determinants, and row reduction.
- Decompositions & Eigen-stuff: Applying eigenvalues, eigenvectors, Singular Value Decomposition (SVD), and Principal Component Analysis (PCA) for dimensionality reduction

# Calculus
- Differentiation: Calculating derivatives, partial derivatives, and applying the chain and product rules to understand how changes in input affect output.
- Multivariate Calculus: Using gradients, Jacobian matrices, and Hessian matrices to optimize multi-feature functions.
- Integration: Finding areas under curves (such as Probability Density Functions) and working with continuous probability distributions

###  Differential Calculus
Differential: rate of change: dy/dx Studies rates of change and slopes of curves through limits, derivatives, and applications like optimization and motion analysis. 
Models dynamic systems using derivatives, solving ordinary (ODEs) and partial (PDEs) equations for real-world phenomena.

###  Integral Calculus
Integral: accumulation of quantities ∫_a^bx^2  dx

# Optimisation
- Cost/Loss Functions: Defining mathematical functions that penalize model errors.
- Gradient Descent: Using derivatives to iteratively step toward the minimum of a cost function (learning rate, local vs. global minima).
- Convex vs. Non-Convex Functions: Identifying whether an optimization problem guarantees a single global solution



# Projects

You can have the most effective engineer but if he doesn’t have good soft skill’s they will not deliver what is necessary. Perhaps they are talented enough but more often than not they deliver something that is not quite what the stakeholder was looking for.
Let's break down a project into it's multiple parts:
1. [Project planning](#project-planning)
2. [Convincing stakeholders](#convincing-stakeholders)
3. [Running the project](#running-the-project)
4. [Finishing the project](#finishing-the-project)
5. [Presenting results of project](#presenting-the-results)


## Project Planning
Project planning is all about flushing out as much as you can before the project starts if possible. You want to clearly define the problem very precisely.
Identify all stakeholders and their roles. What is it they are after? Write a project spec and ppt. If it's software project you likely need to write a project specification document.

**Leadership**
Before beginnging a project you must prime your brain to think from an ownership mindset. When given an area, you must own it. Ownership mindset is crucial. I learnt this from my manager during reviewing my work but that shift to ownerhship mindset is so cruicial.

## Convincing stakeholders
Present your ppt to stakeholders to convince them of the project. 

*The goal of a talk. First, that there’s a common misconception that the goal of your talk is to tell your audience about what you did in your paper. This is incorrect, and should only be a second or third degree design criterion. The goal of your talk is to 1) get the audience really excited about the problem you worked on (they must appreciate it or they will not care about your solution otherwise!) 2) teach the audience something (ideally while giving them a taste of your insight/solution; don’t be afraid to spend time on other’s related work), and 3) entertain (they will start checking their Facebook otherwise). Ideally, by the end of the talk the people in your audience are thinking some mixture of “wow, I’m working in the wrong area”, “I have to read this paper”, and “This person has an impressive understanding of the whole area”.*

## Running the project
Identify your Stakeholders. Document why the project is being undertaken.
Document pipeline architecture and dependencies.  
Document failed experiments. Preserve rejected approaches. 
Save findings for future projects. Report successes. 
Report failures. Tailor communication to audience.

## Finishing the project
Have all the objectives set been met?

## Presenting the results
You should have notes as you go but it's worth putting time in to polish and organise what you are going to present.

