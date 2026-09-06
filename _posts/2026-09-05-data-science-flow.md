---
layout: post
title:  "Data Science flow"
date:   2026-09-05 20:00:00 +0100
categories: jekyll update
---

# Data Science workflow

Data science workflow
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
•	Centrality measures: Mean, median, mode
•	Variability measures: std, variance, range
•	Explore feature-target relationships.
•	Create scatter plots, boxplots and heatmaps.
•	Identify anomalies or outliers.

# Step 3: Build model
•	Start with simple baseline models.
•	Increase complexity only when justified.
•	Train models.
•	Run experiments.

# Step 4: Evaluate model
Assess performance metrics.

•	Categorical (Classification)
•	Confusion matrix
•	Accuracy 
•	Precision 
•	Recall
•	F-score
•	Area under curve
•	Log loss
•	Continuous (Regression) 
•	Absolute error
•	Squared error
•	Measured square error
•	Root mean square error
•	Absolute error distribution
•	Residual sum of squares

# Step 5: Visualisation
The main plots
•	Table: Reading precise individual values.
•	Heatmap: Spotting patterns using colour intensity.
•	Scatter plot: Showing relationships between two variables.
•	Line plot: Tracking continuous data over time.
•	Slope graph: Showing relative changes between two points.
•	Vertical/Horizontal bar: Comparing categorical data quickly.
•	Histogram: show distribution of continuous numerical data in bins
•	Stacked Vertical/Horizontal bar: Showing part-to-whole relationships over time.
•	Waterfall: Showing a running total after additions/subtractions.

Tables 
Communicating to a mixed audience whose members will each look for their particular row of interest. If you need to communicate multiple different units of measure, this is also typically easier with a table than a graph
•	Tables are used when you want to put your data into an array. 
•	Tables allow you to list multiple variables in 2 dimensions. 
•	Add organisation levels to the table and avoid repeated heading text. Use bold to highlight particular columns like totals.

Graphs - scatter
•	Allow you to encode both x and y axis to see what relationship lies
•	You can have scatter plot with free spreads of dependant variable values
•	Dependant values restricted to whole numbers
•	Scatter plot with dependant tested in triplicate, observations averaged and error bars added. Lines of best fit for scatter plots 
•	 What relationship are you trying to show?
•	If you increase one, will the other increase steadily
•	A line of best fit shouldn’t go through abnormabilties if they can’t be explained in real world
•	Line of best fit tells the reader you have some predictive power
Graphs - line
•	Used to plot continuous data. Because the points are physically connected via the line, it implies a connection between the points that may not make sense for categorical data
•	Often, our continuous data is in some unit of time: days, months, quarters, or years
•	Slopegraphs can be useful when you have two time periods or points of comparison and want to quickly show relative increases and decreases or differences across various categories between the two data points
Graphs - bars
•	Bars are best for where information is organized into groups.
•	Note that, because of how our eyes compare the relative end points of the bars, it is important that bar charts always have a zero baseline
•	a common decision to make is whether to preserve the axis labels or eliminate the axis and instead label the data points directly. In making this decision, consider the level of specificity needed. If you want your audience to focus on big‐picture trends, think about preserving the axis but deemphasizing it by making it grey. If the specific numerical values are important, it may be better to label the data points directly. In this latter case, it’s usually best to omit the axis to avoid the inclusion of redundant information. 
•	Always consider how you want your audience to use the visual and construct it accordingly.

Horizontal bar chart - go‐to graph for categorical data
•	The horizontal bar chart is especially useful if your category names are long, as the text is written from left to right, as most audiences read, making your graph legible for your audience there isn’t a natural ordering in your categories that makes sense to leverage, think about what ordering of your data will make the most sense.
•	Because of the way we typically process information—starting at top left and making z’s with our eyes across the screen or page—the structure of the horizontal bar chart is such that our eyes hit the category names before the actual data
•	Bar charts: frequency or magnitude of a categorical value. Make sure the graph actually adds something.
•	Histograms: show frequency distribution
•	Graphs - waterfall
•	The waterfall chart can be used to pull apart the pieces of a stacked
•	bar chart to focus on one at a time, or to show a starting point,
•	increases and decreases, and the resulting ending point

Quality graph
•	Units
•	Axes and titles
•	Figure number and caption. Caption should fully explain data
•	Legend
•	Error bars

Choosing an effective visual – secondary y
•	Quality image
•	Labels and sub labels
•	Images in line 
•	Extra lines to help identification of data or areas of interest
•	Scale bar
•	Caption does not interpret the data – just states it
•	Colour blind compatible 
•	You can also use panels – multi panel figure with different plots
•	Clutter is your enemy
•	Every single element you add to your plot takes up cognitive load
•	Good design means audience doesn’t even notice it

The Gestalt Principles of Visual Perception
•	Step by step
•	Remove chart border
•	Remove gridlines
•	Remove data markers
•	Clean up axis labels – use three letters for month.
•	Label data directly
•	Leverage consistent colour – similarity – label same as data
•	White space
•	Alignment
•	Focus your audience’s attention	

How to direct audience attention
•	Pre-attentive attributes: size, colour, position can be used to 1) direct audience attention and 2) give a visual hierarchy of elements. attention process: stimulus -> eyes -> brain your brain does most the work.
•	brain has 3 memory types for visual: iconic, short-term and long term memory iconic is tune to a set of preattnetive attributes
•	short term: max 4 chunks of visual info at a time. we don’t want audience to work to get information out or we label various data points directly (reducing load). Generally we want to form larger chunks to meet the cap of only 4 things we can handle.
•	long term: aggregate of visual and verbal memory. combine visual and verbal memory to trigger formation of long term memory. If we show a picture of queen a flood of memories come in.
•	Using preattentive attributes to make it allow audience see the what we want them to see before they even know they’re seeig it.
•	orientation
•	shape
•	length
•	width
•	size
•	curvature
•	added marks
•	enclosure
•	hue
•	intensity
•	spatial position
•	motion

We have about 3-8 seconds with audience: use it to give clear visual hierarchy. Interpret the
data yourself. You should have a specific story. Then ask a question for discussion. Leverage
pre-attentive attributes. Go further and give text and focus. Note: if you highlight one aspect, the other aspects become harder to see.
•	1. Push everything to the background
•	2. Make explicit decision on what’s important.
•	3. Be strategi which and which markers, labels you include - "look here!"
•	4. Colour - make it grey then add a single colour to draw attention. use blue!
•	5. Focus your audience attention where you want them to pay it

Think like a designer
Form follows function. What we want our audience to do with the data? (function) affordances
•	The design makes it obvious how the product is to be used e.g knob looks like it’s for turning
•	Accessibility and aesthetics.
•	Not all data are equally important. Use your space and audience’s attention wisely by getting rid of noncritical data or components.
•	When detail isn’t needed, summarize. You should be familiar with the detail, but that doesn’t mean your audience needs to be.
•	Consider whether summarizing is appropriate.
•	Ask yourself: would eliminating this change anything? No? Take it out! Resist the temptation to keep things because they are cute or because you worked hard to create them; if they don’t support the message, they don’t serve the purpose of communication.
•	Push necessary, but non‐message‐impacting items to the background. Use your knowledge of preattentive attributes to deemphasize. Light grey works well for this.

What is the story?
Story Conflict
•	Then something happens—an event that throws things out of balance
•	“Subjective expectation meets cruel reality.”
•	The imbalance: Why is it necessary, what has changed?
•	The balance: What do you want to see happen?
•	What does my protagonist want in order to restore balance in his or her life? 
•	What is the core need? 
•	What is keeping my protagonist from achieving his or her desire? 
•	How would my protagonist decide to act in order to achieve his or her desire in the face of those antagonistic forces?
•	The solution: How will you bring about the changes?
•	Do I believe this? 
•	Is it neither an exaggeration nor a soft‐soaping of the struggle?
•	Is this an honest telling, though heaven may fall?
•	Further develop the situation or problem by covering relevant background.
•	Incorporate external context or comparison points.
•	Give examples that illustrate the issue.
•	Include data that demonstrates the problem.
•	Articulate what will happen if no action is taken or no change is made
•	Discuss potential options for addressing the problem.
•	Illustrate the benefits of your recommended solution.
•	Make it clear to your audience why they are in a unique position
•	to make a decision or drive action.
•	What motivates your audience? making money, beating the competition, gaining market share, saving a resource, eliminating excess, innovating, learning a skill, or something else

Story Resolution
•	End with a call to action: make it totally clear to your audience what you want them to do with the new understanding or knowledge that you’ve imparted to them
•	Types: tie it back to the beginning – recap problem,  resulting need for action
•	Narrative structure
•	The order in which the story is told
•	Ideal = powerful narrative + effective visuals
•	Understand the audience
•	Are they a busy audience who will appreciate if you lead with what you want from them? 
•	Or are they a new audience, with whom you need to establish credibility? 
•	Do they care about your process or just want the answer? 
•	Is it a collaborative process through which you need their input? 
•	Are you asking them to make a decision or take an action? 
•	How can you best convince them to act in the way you want them to? 
•	Narrative structure - Order of the story	 
•	Chronologically: take audience through same path we experienced it. Great if they care about process + building credibility.
•	Lead with ending: start with call to action – what audience needs to know or do. Then back up into support. Works if you already have credibility + they care about ”so what” + care less about process.

Repetition
•	Give a summary slide at the start with main points of story. Organise slides to be in that order. Repeat summary at the end with emphasis on actions.
•	Horizontal logic
•	Just the slide title and the story should make sense
•	Action titles not descriptive titles
•	Exec summary with title slide titles
•	Vertical logic
•	All information on a slide is self-reinforcing 
•	The words reinforce the visual, title and vice versa. No fat.
•	Reverse story boarding
•	Take final communication, flip through it, write main point
•	Fresh perspective
•	Give it to a friend with no context
•	What they pay attention to, what they think is important
•	Histograms: check distribution of a variable
•	Scatter plots: dependency between two variables
•	Maps: show distribution on a map
•	Heat pump: dependency between multiple variables
•	Time series plots: identify trends over time

 




