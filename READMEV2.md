# Portfolio Data Science
Name: Matthew Turkenburg  <br />
Studentnumber: <br />
Course: Applied Data Science Minor<br />
Lecturers: Jeroen Vuurens, Gerda in 't Veld, Tony Andrioli, Ruud Vermeij, Brian de keijzer

## Project ActivPal

### Research project
<details> <summary>Task Definition</summary>

[More Examples](topics/research_project/task_definition.md)

</details>

<details> <summary>Evaluation</summary>

[More Examples](topics/research_project/evaluation.md)

</details>

<details> <summary>Conclusions</summary>

[More Examples](topics/research_project/conclusions.md)

</details>

<details> <summary>Planning</summary>

[More Examples](topics/research_project/planning.md)

</details>

## Domain knowledge
For every research you want to do, you would need to get a certain level of domain knowledge. I wanted to create such domain knowledge by researching similiair researches. You can find my findings below in the chapter literature research. But this wasn't enough, I also had to research documents delivered by our project owner (CBS) to fully understand in what domain we were working in. By combining the knowledge from the given documents and the found literature I was able to write down a subject field document, document my literature findings and document the terminology, jargon and definitions I have found on the way. This document helped myself and my group members to understand the domain.
### Introduction of the subject field
Below you can read the subject field, based all the findings while working on the project.
<details> <summary>More about the subject field</summary>

###Introduction of the subject field
Statistics Netherlands (CBS) has the wish to see if their respondents are moving for at least 150 minutes per week in moderately intense physical activity.  

Currently, they are measuring by asking their respondent or health surveys. The issue with this is that people are not very good at estimating the time they spent on moving and sport. This of course causes that they don't have very reliable data to work with.  Therefor CBS has been looking into alternatives like the accelerometer in combination with machine learning to give better and more accurate results when measuring the intensity of certain activities. After doing extensive research CBS concluded that the ActivPal accelerometer would give the best results when looking into recognizing activities and the intensity of those activities, therefor CBS have chosen to do further research to find out how the combination of the ActivPal accelerometer in combination with machine learning can predict if respondents have done their moderate physical activity for 150 minutes per week.
Because of this the CBS started to collect lab tests and started to measure the movements of 41 correspondents in their regular workweek by using the Activepal Accelerator. The group of correspondents exist of the age 21 to 82 and varies between correspondents that are fit, and are not fit. 
 
It's our job to analyse, structure and build machine learning algorithms based on the collected data to see if we can determine if people adhere to (inter)national norm for physical activities and if we could measure the intensity of movement (without the heart rate information). CBS have chosen to use machine learning because they did pre research with the current dataset and came to the conclusion that machine learning would be the best fit to come to certain conclusions. 
To make sure that this project won’t research the wrong subjects or goes out of scope. The project group and CBS have set a clear scope in which research will be done. The following topics will be researched. 

-	How can Machine Learning be used to predict the intensity of activities performed in a lab situation by a person, who is being monitored with Vyntus One and wearing ActivPal accelerometer?  
-	How can Machine Learning be used to predict the intensity of activities performed by a person wearing only the ActivPal accelerometer, based on the data gathered from Vyntus One and ActivPal accelerometer in the lab situation?  
-	How can Machine Learning be used to determine whether people did their 150 minutes of moderate activity in ActivPal accelerometer data of an entire week?


</details>

### Literature research
In this part of the chapter you can find some of the literature findings that I have done while researching the project domain. I only wrote down the most important findings from the papers that we could use for the project domain or for writing the paper in the future. All information found here has been used throughout out the project.
<details> <summary>The accelerometer project findings lab research 1.0</summary>



</details>
<details> <summary>Beweegonderzoek</summary>



</details>
<details> <summary>Measurement of Phy 2016</summary>



</details>
<details> <summary>MET Calculations from On-Body Accelerometers</summary>



</details>
<details> <summary>Physical activity recognition</summary>



</details>

### Explanation of Terminology, jargon and definitions
In this part you can read some of my documented terminology, jargon and definitions that I have found while working on the project.
<details> <summary>Explanation of Terminology, jargon and definitions</summary>

###Introduction
In this document you can find the explanation of the Terminology, jargon and definitions. This can be used to give more insight into the terms that have been used trough this project.

Accelerometer - is a tool that measures proper acceleration. <br />
ActivPAL accelerometer – captures body posture and transition between these postures, stepping, and stepping speed (cadence).<br />
Vyntus – Document that contains the lab data of the Vyntus sensor, which measures the O2 uptake and the CO2 production.<br />
Dataframe - A table of data with rows and columns.<br />
Data cleaning - is the process of detecting and correcting (or removing) corrupt or inaccurate records from a record set, table, or database.<br />
Resampling – Changing the timeseries.<br />
BMI (body mass index) - is the value derived from the mass and height of a person.<br />
Metabolic rate – The rate of energy usage by the body.<br />
MET - The ratio of the work metabolic rate to the resting metabolic rate.<br />
Correlation – Measurement of the extent to which to variables are related.<br />
Epoch – a particular period of time.<br />
Feature – An individual measurable object / characteristic of something that being used.<br />
Seed – A random number generated by software based on a static number (the seed).<br />
Precision - The accuracy of the measurement of the results to be true.<br />
Recall – The ability of a model to find all relevant cases within the dataset.<br />
Dice Face – The face the accelerator is moved looking towards (north side, south side) expressed into the numbers 1-6 (up, down, left, right, etc).<br />
Thresholding - The knock off criteria based on a certain object/feeling/number<br />
Lab data – fully labelled data, which was received and processed in the lab. Plus, literature (on off cut values), the manufacturers' summary information, open-source software.<br />
Raw data – is unprocessed computer data.<br />
Outliers – A data point that differs significantly from other observations.<br />
Research plan – is a short document, which sets out the initial thoughts on a research project in a logical and concise manner. It contains the research question, the hypothesis, aims and objectives, research design.<br />
Linear regression - attempts to model the relationship between two variables by fitting a linear equation to observed data. One variable is an explanatory variable, and the other is a dependent variable. For example, a modeler might want to relate the weights of individuals to their heights using a linear regression model.<br />
Decision tree model - is a machine learning algorithm that partitions the data into subsets. The partitioning process starts with a binary split and continues until no further splits can be made. Various branches of variable length are formed.<br />
Random forest model - a supervised learning algorithm. The "forest" it builds, is an ensemble of decision trees, usually trained with the “bagging” method. The general idea of the bagging method is that a combination of learning models increases the overall result.<br />
Peak-to-peak amplitude – is the change between peak (highest amplitude value) and through (lowest amplitude value, which can be negative).<br />
Acceleration – The measurement of an object it’s velocity.<br />
G-Force – The gravitational force of the earth’s surface. One g is the same as 9.8m/s<br />
Kcal (calorie) – Kcal is a measurement of energy. Known from Latin, warmth.<br />
Physical activity – Any movement done by the construction of the skeletal muscles of the body.<br />
Light-intensity Physical activity – Activity’s with a MET value between 1.5 and 3. <br />
Moderate-intensity Physical activity - Activity’s with a MET value between 3 and 6.<br />
Vygorous-intensity Physical activity - Activity’s with a MET value above 6.<br />
Vo2 – Oxygen consumption by breathing spicy. <br />

</details>

### Data preprocessing
<details> <summary>Data exploration</summary>

[More Examples](topics/data_preprocessing/data_exploration.md)

</details>

<details> <summary>Data cleaning</summary>

[More Examples](topics/data_preprocessing/data_cleaning.md)

</details>

<details> <summary>Data preparation</summary>

[More Examples](topics/data_preprocessing/data_preparation.md)

</details>

<details> <summary>Data visualization</summary>

[More Examples](topics/data_preprocessing/data_visualization.md)

</details>


### Predictive Analytics

<details> <summary>selecting a model</summary>

[More Examples](topics/data_preprocessing/selecting_a_model.md)

</details>

<details> <summary>training model</summary>

[More Examples](topics/data_preprocessing/training_model.md)

</details>

<details> <summary>evaluating a model</summary>

[More Examples](topics/data_preprocessing/evaluating_a_model.md)

</details>

<details> <summary>Visualizing the outcome of a model</summary>

[More Examples](topics/data_preprocessing/visualizing_the_outcome_of_a_model.md)

</details>

<details> <summary>configuring a model</summary>

[More Examples](topics/data_preprocessing/configuring_a_model.md)

</details>

### communication

<details> <summary>presentation</summary>

[More Examples](topics/data_preprocessing/presentation.md)

</details>

<details> <summary>writing paper</summary>

[More Examples](topics/data_preprocessing/writing_paper.md)

</details>

## Datacamp


![Images]()

|Course|Statement of Accomplishment|
 |------|---------------------------|
 | Introduction to python |[proof]()|
 | Python Data Science Toolbox (Part 1) |[proof]()|
 | Intermediate Python |[proof]()|
 | Python Data Science Toolbox (Part 2) |[proof]()|
 | Pandas Foundations |[proof]()|
 | Introduction to Data Visualization in Python |[proof]() |
 | Manipulating Dataframes with pandas |[proof]()|
 | Data Types for Data Science in Python |[proof]()|
 | Cleaning data in Python |[proof]()|
 | Preprocessing for Machine Learning in Python |[proof]()|




 
<details> 
<summary>Summary proof </summary>

![Images]()

</details>

