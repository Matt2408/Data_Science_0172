# Portfolio Data Science
Name: Matthew Turkenburg  <br />
Studentnumber: 17113148<br />
Course: Applied Data Science Minor<br />
Lecturers: Jeroen Vuurens, Gerda in 't Veld, Tony Andrioli, Ruud Vermeij, Brian de keijzer

## Project ActivPal

### Introduction
In this portfolio you can read about the journey of a Business IT & Management student following the minor Data Science. It was a hard but really fun minor that learned me alot of new aspects of IT. I would like to thank the lecturers for their time and effort that has been put into the students!



### Research project
### Task Definition
In this portfolio you can read all my individual work to the ActivePal project for the minor Data Science. Since I didn't have a background into programming my main focus was to do research work for the project. But since I had alot more fun in programming then I expected you can read more about my learning experience in Python aswell!

In project ActivePal we are trying to help Het Centraal Bureau voor de Statistiek (CBS) with their problem. Currently they experiencing issues with measuring if their target audience has moved for atleast 150 minutes a week while doing moderate physical activity's. At the moment they measure this by manually giving out health surveys but the results of this are not good enough. People seem to be bad at estimating how much time they have spend doing moderate physical activity's. 

To help CBS out, our group got formed and based on the problem, project domain and input from the productowner, the following research question is made:

> <b> How can Machine Learning be used to determine whether people did their 150 minutes of moderate activity in ActivPal accelerometer data of an entire week? </b>

To answer this questions we decided that we first had to answer the following two sub questions (in order).

><b>How can Machine Learning be used to predict the intensity of activities performed in a lab situation by a person, who is being monitored with Vyntus One and wearing ActivPal accelerometer?  <br /><br />
How can Machine Learning be used to predict the intensity of activities performed by a person wearing only the ActivPal accelerometer, based on the data gathered from Vyntus One and ActivPal accelerometer in the lab situation? </b>


More about the task definition can be read in the research plan. 

<details> <summary>Reseach plan</summary>
Personally I took the job on me to make sure that every member of the projectgroup had a clear understanding of the project. To do this I wanted to create the first iteration of the research plan. In this research plan members would be able to get a more knowledge of the given task by CBS, read the research questions and read what exactly we do for the work planning. Based on the research plan that I made people were able to make new iterations of the reseach questions and were able to read the exact task that CBS gave us.    

You can find my iteration of the research plan [here](/Evidence/Research%20Project/Research%20plan%20by%20Matt%20V1.pdf)

The research plan helped the group to understand the problem domain, discuss about the research questions and rethink our way of doing about the subject planning. 

---

</details>

### Planning
At the beginning of the project the group decided unanimously that we wanted to work in an agile way. Because of that we decided that we wanted to follow philosophy of Scrum, but didn't want to follow every rule exact, this means that there was some flexibility on our side. Within the group we decided that we wanted to have sprints of two weeks and ending the sprint with a retrospective. At every retrospective I (and my group members) gave my feedback based on the progress. 

More about the planning can be read down below in the sub paragraph: Research plan - planning (written by me).


<details> <summary>Jira</summary>
As a group everybody was responsible to keep track of the Jira board. I saw this task as really important because it's important that everybody has knowledge what you are doing, and what the current status is. It also gave the opportunity to people to take tasks that were sitting still.

Within the group we decided that Ali Safdari would be the Jira master. This means that he would take the lead assigning tasks, keeping track of the progress and the board. I tried to assist him  as much as I could by managing my own tasks, and keeping the status of my tasks up to date. Below you can read our sprint log of all the sprints that have been concluded. In the pictures you can clearly see that I have been attributing to the Jira board in a positive way throughout the project. 

The sprint log doesn't show a good example what exactly has been done by the invidiual persons, however it does show that I contributed to managing and helping the Jira planning.

<b>Jira sprint 1<br />
[![Sprint1.png](https://i.postimg.cc/256hF4rC/Sprint1.png)](/Evidence/Research%20Project/Jira%20bewijs/Sprint1.png)
Jira sprint 2<br />
[![Sprint2.png](https://i.postimg.cc/fytJJKcr/Sprint2.png)](https://postimg.cc/vxyQK5Sr)
Jira sprint 3<br />
[![Sprint3.png](https://i.postimg.cc/9FsnktLF/Sprint3.png)](https://postimg.cc/HV4zc5Gf)
Jira sprint 4<br />
[![Sprint4.png](https://i.postimg.cc/cC3dq4Gv/Sprint4.png)](https://postimg.cc/m1TvC4D4)
Jira sprint 5<br />
[![Sprint5.png](https://i.postimg.cc/dQZCQ2qy/Sprint5.png)](https://postimg.cc/Jtm0PBHr)
Jira sprint 6<br />
[![Sprint6.png](https://i.postimg.cc/dtM5JtKJ/Sprint6.png)](https://postimg.cc/CdNGN012)
</b>

---

</details>

<details> <summary>Research plan - Planning</summary>
In the research plan I wrote a section about our planning. This planning was used to help people understand our way of working. I made the first iteration of this section, later on in the project my contrubition helped Colin with the second and final iteration of this section for the final research plan.

You can find my iteration of planning (inside the research plan) [here](/Evidence/Research%20Project/Research%20plan%20by%20Matt%20V1.pdf)

---

</details>

<details> <summary>Daily stand-up/retrospective</summary>
<b>Daily standup </b><br />
To manage the project as good as we can, we kept daily standups every day since the beginning of the project in week 1. In the standup we would discuss our progress, what we have done, issues and what you are going to do next. In my opinion was this part of the project really important to keep track of our progress and help us to determine our next steps.

I couldnt really find great proof of those stand-ups except all the meetings in the teams environment. All teachers should have access to this environment to verify all our daily work. 

<b>Retrospective </b><br />
At the end of every sprint (every two weeks), the group would do a scrum retrospective. In this retrospective we would look back at the Jira board and discuss the sprint progress. What tasks are done, what should we focus next week and what are the issues that didn't get solved. Every retrospective was always with the whole team, this meant that it was also the moment that we were able to discuss issues within the team and to describe actionpoints for the upcoming sprint.

Examples of real actionpoints are:
- Being on time on the daily standup
- Being more active in meetings with CBS/teachers
- Giving more information at the standups

---

</details>


### Conclusions
In this chapter I will go over the final conclusions of the ActivePal project. I have seperated the conclusions into multiple sections that you can read below. 

<details> <summary>MET prediction model</summary>
With our projectgroup we made alot of MET predictions models. We tried various models to see which would give the best results for predicting the MET values. At the first glance the results of the models all looked very promissing. We really thought that we made amazing models until we validated our results with the test set. After the last run with the test set we came to the conclusions that our models were overfitting. You can read the reasons why I think that they are overfitting in the section Evaluation. 

--- 

</details>


<details> <summary>Activity Recognition model</summary>
To understand the end conclusion it's important to know how we got there. To do so I will briefly explain the work of Adnan Akbas, he personally programmed the activity recognition model alone, with the groups input. The results of his model can be found below: 



| |Cross Validation|
|------------|---------|
|Accuracy|0.82|
|Recall|0.84|
|Precision|0.82|

As you can read in the table, his activity recognition is able to get high final scores after the cross validation. After this model was finished we were able to combine both activity recognition model and the MET prediction model (intensity model) to write our final verdict on the research question.

--- 

</details>


<details> <summary>Research questions</summary>

> <b> How can Machine Learning be used to determine whether people did their 150 minutes of moderate activity in ActivPal accelerometer data of an entire week? </b>
By first doing an activity reconigzion prediction on your dataset you are able to predict what kind of activities were done. As seen in our activity recogniztion model it can accurately predict whenever somebody for example is running. Every activity has a standard MET value. By using a seperate model to determine the intensity of an activity (the MET value used in our case) you are able  to calculate if a person did their 150 minutes of moderate activity.  

However the accuracy depends on the dataset. If there isn't enough data as seen in our research, there is a big chance on overfitting. You can see my thoughs about this in the next chapter (Evaluation)

--- 

</details>

<details> <summary>Email to CBS with conclusions</summary>
Hieronder leest u de algemene conclusie die ik heb geschreven (namens de groep) die wij hebben gestuurd naar CBS. In deze conclusie leest CBS over de algemene resultaten die hebben wij gevonden. Deze conclusie is gestuurd naar de overige overdrachtsdocumenten zoals bijvoorbeeld de notebooks. 

</br>

Machine learning kan worden ingezet om te voorspellen of een persoon zijn zijn/haar 150 minuten of matige lichamelijke activiteit heeft uitgevoerd. Dit kan worden voorspelt doormiddel van een combinatie van twee verschillende modellen. Ten eerste zal een activiteiten herkenning model moeten worden uitgevoerd op de weekdata. Dit model voorspelt doormiddel van verschillende features welke activiteit door de persoon werd uitgevoerd. Binnen het project hebben wij ervoor gekozen om een random forest model te gebruiken om de activiteiten te voorspellen. Bij deze voorspelling is ervoor gekozen om de activiteiten springen en traplopen niet mee te nemen omdat hiervoor geen lab data aanwezig was (vyntus data) en om deze reden ook geen ground truth voor de MET values. 
Nadat de activiteit is voorspelt, komt er een tweede model in het gebruik. Doormiddel van een model dat per activiteit een MET waarde kan voorspelt, is het mogelijk om de intensiviteit van een activiteit te bereken. Voor het voorspellen van de MET waarde, is er gekozen voor twee verschillende modellen waar de resultaten vrij dicht bij elkaar liggen. Namelijk een random forest model en een XGBoost model. Voor het berekenen van de MET waarde, is ervoor gekozen om deze te bereken per minuut zoals aangegeven in de literatuur. 
Een combinatie van de activiteiten voorspelling en de MET waarde voorspelling maakt het mogelijk om te voorspellen of een persoon zijn/haar 150 minuten of matige lichamelijke activiteiten heeft uitgevoerd binnen de weekdata. Om dit zo goed mogelijk te illustreren hebben wij een applicatie gebouwd waarin de modellen daadwerkelijk worden toegepast op de weekdata. Een illustratie van de applicatie ziet u hieronder.  In dit voorbeeld is voor één van de gebruikers binnen de dataset een overzicht gemaakt van één dag d.m.v onze modellen. 

![Images](/Evidence/Applicatie%201%20week.png)

Met de modellen en de applicatie tonen wij aan op welke wijze machine learning kan worden ingezet om te voorspellen of personen hun 150 minuten van matige lichamelijke activiteiten heeft uitgevoerd. 

--- 

</details>

<details> <summary>Paper</summary>
In the paper you can read our scientific conclusion. My contribution to that is that I gave feedback on the first itertation and helped with the third and last iteration.
</details>


### Evaluation
<details> <summary>Evaluation</summary>
In this chapter you can read about the future directions for CBS. You can read those directions in short below or you can read it in the other project related documents that I have written.

---

<details> <summary>Clear target audience</summary>
In the beginning of the project, the group decided that we would examine the data. When we did this, we found out that the current target audience existed of respondents with the age 18 to 91. But the amount of data availible was very limited for such large audience. For that reason I like to advice CBS to in the further have a better understanding what audience you exactly want to measure. Because in our project we had to remove respondents since they wasn't enough data for that audiance or they were far of the standard deviation. 

---

</details>

<details> <summary>More data</summary>
One of the big issues in this project was the amount of data. Since our target audience was really big and included all ages. We had only very small amount of training data for the whole target audiance. This causes bias towards the most representing class. In the future we would love to see more data availible to solve this issue. 

This would also mean that there would be more data available for the MET calcuations.  

---

</details>

<details> <summary>Advice about further work to CBS email</summary>
One of the things I made was the handover email to CBS. In this email we written our conclusions and advice to CBS. I personally made this email and send this over to CBS.

You can read this in the following document: [Click here for the document](/Evidence/Research%20Project/Conclusions%20to%20CBS.pdf)<br />

---

</details>

<details> <summary>Discussion in paper</summary>
This chapter is all about the evaluation and further directions for CBS. With the project group we decided that I would write the discussion in the paper. This means that I talk about the weaknesses of our project and how CBS can work in the future with our work. 

<details> <summary>Paper discussion</summary>
The present study found out that, it’s not possible to identify if a respondent has reached their 150 minutes of the recommended moderate insane physical activity in a week by using the dataset supplied by CBS. Certain activities can’t be recognized, and this causes that not all MET values can be calculated for each activity.  

The results might suggest that it’s not possible to identify if a respond has done their weekly activities at all. However, based on the findings of similar studies, a more plausible explanation is that the dataset used in this research didn’t contain enough data for every activity to train a model to recognize this.  

In this study there are a few limitations that have hold back the results of this study. One of the biggest limitations is the amount of data used to make predictions. In total there were X subjects because the number of subjects was so small, the model couldn’t fit the data which caused it too overfit. For future research it should be recommended to increase the number of subjects or the size of the data for each activity. The second limitation is the calculation of speed. In this research the speed calculation did not get calibrated, since the results without calibration were a lot better and it was concluded that the activPAL accelerometer did not calibrate either. For that reason, the reasoning of activPAL got followed and the speed calculation didn’t get calibrated.  

</details>

---

</details>


</details>

## Domain knowledge
For every research you want to do, you would need to get a certain level of domain knowledge. I wanted to create such domain knowledge by researching similiair researches. But this wasn't enough, I also had to research documents delivered by our project owner (CBS) to fully understand in what domain we were working in. By combining the knowledge from the given documents and the found literature I was able to write down a subject field document, document my literature findings and document the terminology, jargon and definitions that I had found on the way. This document helped myself and my group members to understand the domain.
### Introduction of the subject field
Below you can read the subject field, based all the findings while working on the project.  The subject field was one of the first documents that I worked on. It was written when there wasn't a clear picture of the project. This document gave the opportunity to get more knowledge about the subject field to understand what we were working with. 
<details> <summary>More about the subject field</summary>
Statistics Netherlands (CBS) has the wish to see if their respondents are moving for at least 150 minutes per week in moderately intense physical activity.  

Currently, they are measuring by asking their respondent or health surveys. The issue with this is that people are not very good at estimating the time they spent on moving and sport. This of course causes that they don't have very reliable data to work with.  Therefor CBS has been looking into alternatives like the accelerometer in combination with machine learning to give better and more accurate results when measuring the intensity of certain activities. After doing extensive research CBS concluded that the ActivPal accelerometer would give the best results when looking into recognizing activities and the intensity of those activities, therefor CBS have chosen to do further research to find out how the combination of the ActivPal accelerometer in combination with machine learning can predict if respondents have done their moderate physical activity for 150 minutes per week.
Because of this the CBS started to collect lab tests and started to measure the movements of 41 correspondents in their regular workweek by using the Activepal Accelerator. The group of correspondents exist of the age 21 to 82 and varies between correspondents that are fit, and are not fit. 
 
It's our job to analyse, structure and build machine learning algorithms based on the collected data to see if we can determine if people adhere to (inter)national norm for physical activities and if we could measure the intensity of movement (without the heart rate information). CBS have chosen to use machine learning because they did pre research with the current dataset and came to the conclusion that machine learning would be the best fit to come to certain conclusions. 
To make sure that this project won’t research the wrong subjects or goes out of scope. The project group and CBS have set a clear scope in which research will be done. The following topics will be researched. 

-	How can Machine Learning be used to predict the intensity of activities performed in a lab situation by a person, who is being monitored with Vyntus One and wearing ActivPal accelerometer?  
-	How can Machine Learning be used to predict the intensity of activities performed by a person wearing only the ActivPal accelerometer, based on the data gathered from Vyntus One and ActivPal accelerometer in the lab situation?  
-	How can Machine Learning be used to determine whether people did their 150 minutes of moderate activity in ActivPal accelerometer data of an entire week?

---

</details>

### Literature research
In this part of the chapter you can find some of the literature findings that I have done while researching the project domain. I only wrote down the most important findings from the papers that we could use for the project domain or for writing the paper in the future. This documentation was really nice for writing the paper and understanding the subject field. Since it gives myself and the group the option to really quickly read the most important subjects from those scientific papers. 
<details> <summary>The accelerometer project findings lab research 1.0</summary>
This paper is focused on finding the most accurate classification based on machine learning used different kinds of accelerator sensors. But in my opinion the paper gives great insights about the following topics. 

<b>3.6 Estimating Intensity (energy expenditure)<br /></b>
While scanning this paper the first thing that really sticked out for me was chapter 3.6 Estimating Intensity (energy expenditure). This chapter explains what they have used to measure intensity. In the case of this paper they used Metabolic Equivalent or Task (MET), otherwise known as EE / MUMR. Where EE stands for Energy Expenditure and BUMR stands for the base metabolic rate per kg and time unit. Basically you can say EE is the number of calories burned during an activity. The best way to calculate MET is by using VO2, but other options are possible.

<b>3.2 Validation<br /></b>
Since this research paper is made by the CBS, and they are going to use the same correspondents as we do. We could look into the way they validated their project. In chapter 3.2 Validation, they explain how they build their test and training set and what values they used. In the case of this paper they used a training set of 60% based off their total dataset. 

<b>3.4 Metrics</b><br />
CSB tested their work on the following metrics: Accuracy, Precision, recall and F1 score. They don’t mention if they used any other metrics. 

<b>5.2 Scatterplots for specific respondents</b> <br />
CBS mentions in their paper that there have been a phenomenon that occurs for almost all respondents. What is happening is that the when a respondent is doing an activity and switches to a different activity. As example from standing to walking the heart rate goes down while the VO2 intake goes up. CBS states that this is very strange since they would expect the heart rate to go up as well. 

<b>Conclusions</b><br />
-All MAD intensity estimates seem to overestimate the intensity of jerky activities and do not record how much static force the body exerts on the environment.  
-ActivPAL registers the approximate intensity of cycling well, but is not accurate enough to distinguish between light and heavy cycling. ActivePAL also overestimates the intensity of low intensity activities.  

---

</details>
<details> <summary>Beweegonderzoek</summary>
Deze paper onderzoekt in hoeverre er een verband is tussen MET en acceleratie. Hierbij wordt gebruik gemaakt van dezelfde dataset die bij ons project wordt toegepast. In deze paper wordt beschreven welke stappen zijn gevolgd om de data uit te lezen , op te schonen en te kunnen worden geanalyseerd. Bij de analyse lag de focus voornamelijk op de MET value. 

Uit dit onderzoek bleek dat zitten een gemiddelde MET score had van 1.5 en staan een gemiddelde van 1.6. Fietsen zwaar en fietsen licht kwamen erg bij elkaar in de buurt met een MET value van 6 en van 5. 

Tijdens het onderzoek is naar voren gekomen dat sommige activepal bestande niet bestaan, ook zijn er verschillen te vinden tussen de verschillende vyntus metingen. 

De accelerators gaan niet altijd terug naar de nulwaarde van de accelerator waardoor het voor kan komen dat bij rustige activiteiten zoals zitten en staan, de waarde boven de 1 MET kan komen. 

Doordat het aantal testpersonen niet op grote schaal was uitgezet, zorgde dit ervoor dat de resultaten misschien wel accuraat waren, maar niet konden worden getest met de werkelijkheid.

---

</details>
<details> <summary>Measurement of Phy 2016</summary>
<b>Measurement</b><br />
In this paper it explains how physical activity get measured using accelerometers. The first topic being discussed is how acceleration is measured by using the following formula (acceleration = velocity/time). This acceleration is frequently expressed in the meters per square second or by using g-force. G-Force stands for 1 g = 9.8m/s (force of gravity).

<b>Epochs </b><br />
Epochs are specific time intervals for which counts are summed for data analyses. Epochs are not always the same but are depending on the amount of data and depend on the population (different epochs for children/eldery) .
In our project we are working with adults and elders. Because of this it’s recommend to use epochs of 60 seconds. (Copeland & Esliger, 2009; Freedson et al., 1998; Hendelmanet al., 2000; Miller, Strath, Swartz, & Cashin, 2010; Sasaki et al., 2011;Swartz et al., 2000);

<b>Intensity of movement (Figure 2.2)</b><br />
This paper uses a combination of counts and MET values to determine if an activity is moderate/low/high. They count the amount of data point in one minute and use cut-off points with different categories to see how intensive an activity is. 

---

</details>
<details> <summary>MET Calculations from On-Body Accelerometers</summary>
This paper tries to use on-body accelerometers to measure activity/met while doing activity’s. To do this they used approximations they measured and compare those to known MET scores. In the paper they describe there are other ways to measure this without accelerometers by using the heart rate or using VO2. Like I have mentioned in the other conclusions of the papers, they are using cut of points based on MET values to determine what kind of activity has been done (and how intense). 

---

</details>
<details> <summary>Physical activity recognition</summary>
This paper goes to the basics of physical activity. It explains how physical activity can be defined: As any voluntary body movement generated by the contraction of skeletal muscles resulting in energy expenditure. 
It also explains how to measure physical activity, to conclude this subject they use regular accelerometers, Piezoelectric accelerometers and capactive accelerometers. They also mention how you can estimate the energy expenditure using accelerometers. They mention that you can use MET and use features like length, weight, BMI and even body composition (fat and lean mass). 

---

</details>

### Explanation of Terminology, jargon and definitions
In this part you can read some of my documented terminology, jargon and definitions that I have found while working on the project. This document helped the group to understand a few topics that were discussed quite often inside our daily standsups and researching. The following list is my contribution to our jargon list. Personally I really liked making this list since it gave structure and was a fallback when I didn't understand a topic and wanted to research it later on. 
<details> <summary>Explanation of Terminology, jargon and definitions</summary>
<b>Accelerometer</b> - is a tool that measures proper acceleration. <br />
<b>ActivPAL accelerometer</b> – captures body posture and transition between these postures, stepping, and stepping speed (cadence).<br />
<b>Vyntus</b> – Document that contains the lab data of the Vyntus sensor, which measures the O2 uptake and the CO2 production.<br />
<b>Dataframe</b> - A table of data with rows and columns.<br />
<b>Data cleaning</b> - is the process of detecting and correcting (or removing) corrupt or inaccurate records from a record set, table, or database.<br />
<b>Resampling</b> – Changing the timeseries.<br />
<b>BMI (body mass index)</b> - is the value derived from the mass and height of a person.<br />
<b>Metabolic rate</b> – The rate of energy usage by the body.<br />
<b>MET</b> - The ratio of the work metabolic rate to the resting metabolic rate.<br />
<b>Correlation</b> – Measurement of the extent to which to variables are related.<br />
<b>Epoch</b> – a particular period of time.<br />
<b>Feature</b> – An individual measurable object / characteristic of something that being used.<br />
<b>Seed</b> – A random number generated by software based on a static number (the seed).<br />
<b>Precision</b> - The accuracy of the measurement of the results to be true.<br />
<b>Recall</b> – The ability of a model to find all relevant cases within the dataset.<br />
<b>Dice Face</b> – The face the accelerator is moved looking towards (north side, south side) expressed into the numbers 1-6 (up, down, left, right, etc).<br />
<b>Thresholding</b> - The knock off criteria based on a certain object/feeling/number<br />
<b>Lab data</b> – fully labelled data, which was received and processed in the lab. Plus, literature (on off cut values), the manufacturers' summary information, open-source software.<br />
<b>Raw data</b> – is unprocessed computer data.<br />
<b>Outliers</b> – A data point that differs significantly from other observations.<br />
<b>Research plan</b> – is a short document, which sets out the initial thoughts on a research project in a logical and concise manner. It contains the research question, the hypothesis, aims and objectives, research design.<br />
<b>Linear regression</b> - attempts to model the relationship between two variables by fitting a linear equation to observed data. One variable is an explanatory variable, and the other is a dependent variable. For example, a modeler might want to relate the weights of individuals to their heights using a linear regression model.<br />
<b>Decision tree model</b> - is a machine learning algorithm that partitions the data into subsets. The partitioning process starts with a binary split and continues until no further splits can be made. Various branches of variable length are formed.<br />
<b>Random forest model</b> - a supervised learning algorithm. The "forest" it builds, is an ensemble of decision trees, usually trained with the “bagging” method. The general idea of the bagging method is that a combination of learning models increases the overall result.<br />
<b>Peak-to-peak amplitude</b> – is the change between peak (highest amplitude value) and through (lowest amplitude value, which can be negative).<br />
<b>Acceleration</b> – The measurement of an object it’s velocity.<br />
<b>G-Force</b> – The gravitational force of the earth’s surface. One g is the same as 9.8m/s<br />
<b>Kcal (calorie)</b> – Kcal is a measurement of energy. Known from Latin, warmth.<br />
<b>Physical activity</b> – Any movement done by the construction of the skeletal muscles of the body.<br />
<b>Light-intensity Physical activity</b> – Activity’s with a MET value between 1.5 and 3. <br />
<b>Moderate-intensity Physical activity</b> - Activity’s with a MET value between 3 and 6.<br />
<b>Vygorous-intensity Physical activity</b> - Activity’s with a MET value above 6.<br />
<b>Vo2</b> – Oxygen consumption by breathing spicy. <br />

---

</details>

## Data preprocessing
One of the first steps into the project was to do examine the data to see what we were working with. I have done this by building an information table for myself and writing down what exactly the dataset included. For our project we received two files from CBS. One of the files contained the the lab data and one document contained the weekdata. You can read more about this in data explanation. 
<details> <summary>Data exploration</summary>

### Introduction
One of the big problems we had when working on the ActivePal project was understanding how G-force works with our dataset. I had the job to examine our dataset and see if I could come up with visualiations that would make the group understand G-force better at the different activities. An example can be read below where I had to find out why g-force would act different at certain corrospondents which caused outliers. 

![Images](/Evidence/G-force.png) </br>
In this picture you can see the g-force over time for every corrospondent in the group for the activity standing still. In the literature it's declared that whenever you stand still you have a g-force of 1.0G. So in this case we would expect the plot to show that. But instead the following two things can be found in the shown plot. 
- The accelerator is picking up movement at some of the corrospondents, you can see this by the fluxerating G-force.
- There are two clear outliers at -1.0G (exactly the opposite of the rest of the group)
- You can see that some of the corrospondents don't start at 1.0G but instead in the range of 1.0G to 1.3G.

### Early hypothesis
The small movements that are being picked up by the accelerator can be caused by corrospondents not standing completely still. They could be shuffling and/or doing other movements that being picked up. I think that the negative G-force can be explained by the accelerometer being upside down. If you put the accelerometer upside down this would change the axis and by doing this positive 1.0G would be come negative -1.0G. 

I discussed with the group and CBS how some of the corrospondents are starting at a different value then 1.G (range of 1.0 to 1.3G) but so far this can't be explained.

[Link to notebook](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/Analyse%20and%20document%20%7BX%2C%20Y%2C%20Z%7D%20data.ipynb)

---

</details>

<details> <summary>Data cleaning</summary>

The dataset that we received from CBS was given in cleaned state. For us this meant that we really couldn't do much. 

---

</details>

<details> <summary>Data preparation</summary>
Data preparation is a very broad aspect of machine learning. In this chapter I will show you what I have done to make sure that the data was ready to be used in an efficient way in the models. Below you can read about the subjects I worked on.



<details> <summary>Variance Tresholding</summary>
To make sure that there wasn't any low variance features being used in the models. I had chosen to use VarianceThreshold from SKlearn. You can find the code below. This function removes any low variance features that would be bad for the model.

````python
# Applying lecture lesson to data set - Variance treshold (70% best results)
sel = VarianceThreshold(threshold=(.7 * (1 - .7)))
x = sel.fit_transform(x)
````

---

</details>



<details> <summary>New features</summary>
One of the things I had read in papers were to test out if it would be benefitical to use the following two features: Standard deviation and mean. For that reason I had written the following code:

````python

                stdev_x =  statistics.stdev(activpal_segment['x']) if len(activpal_segment['pal_accX']) >= 2 else 0
                mean_x = activpal_segment['pal_accX'].mean()

````

---

</details>


<details> <summary>Filling empty values</summary>
After I wrote the code for the new features above (stdev/mean). I wanted to fill every nan value. I did that with the following code from the lecture:

````python
fill_na_columns = ['standard_deviation_x', 'mean_x', 'standard_deviation_y', 'mean_y','standard_deviation_z', 
                    'mean_z']

for column in fill_na_columns :
    features[column].fillna(0, inplace=True)
````

---

</details>

<details> <summary>RFE</summary>
To make sure that the model isn't going to be using redundant features I wanted to write code to use RFE on the dataframe. The following code applies RFE to the dataset and takes the best six features and uses that in the model. I been experimenting with this, so what I did was different configurations. The end result can be read below:

````python
rfe = RFE(estimator=DecisionTreeClassifier(), n_features_to_select=6)
model = DecisionTreeClassifier()
pipeline = Pipeline(steps=[('s',rfe),('m',model)])

cv = RepeatedStratifiedKFold(n_splits=10, n_repeats=3, random_state=1)
n_scores = cross_val_score(pipeline, x, y, scoring='accuracy', cv=cv, n_jobs=-1, error_score='raise')

# report performance
print('Accuracy: %.3f (%.3f)' % (mean(n_scores), std(n_scores)))
````

[Link to notebook] (https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/feature_selection_matt.ipynb)

---

</details>



<details> <summary>Syncretizing the main dataframe</summary>
Together with Colin, I have been working on merging all our dataframes into one notebook. By doing so everybody is able to include the same dataset in their models. Prior to this we had issues with validating the results since everybody had their own way of setting up their model dataframe. 

My contrubution to the collaboration with Colin was being the person that was writing the code. He was the one that was assisting me with the code itself and the thought process.

[Link to notebook](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/Creating%20main%20dataframe%20(containing%20all%20data).ipynb)


</details>

---

</details>


<details> <summary>Data visualization</summary>
Before we could make important decisions, like choosing a model, the features and other options. We needed to know what kind of data we were working with. For that reason I started to visualize our current data. The first thing I wanted to try was to see if there was a clear seperation between the different activity's. For that reason I made the following plot.  

![Images](/Evidence/datavisualization_standard_deviation_by_GROUP.png) </br>
This plot shows the different activity's that we want to use for our models. The first plot shows the X-axis, the second shows the y-axis and the third shows the z-axis. The color indicate the activity. From this plot you can tell that if you use the standard deviation, that you would be able to seperate the different activity's. For that reason we decided that we should include the standard deviation into our models. In the next picture you can see the same plot but instead of groups, you will be able to see every corrospondent against the full group.


![Images](/Evidence/datavisualization_standard_deviation_by_GROUP_VS_INDIVUAL.png) </br> 
With this plot I wanted to see if I could find clear outliers in our dataset. By plotting all corrospondents against the full population it would be come clear who of the corrospondents are far off the standard deviation. An example of this can be seen in the right bottom corner of the plot. 

Link to notebook: https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/all_steps_activity_data_analyse_Matt_v2.ipynb

![Images](/Evidence/G-force.png) </br>
In this visualization I wanted to show CBS some insights that I had found. The results were suprissing for CBS themself aswell and they were glad that we had found it. 


[Link to notebook:](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/Analyse%20and%20document%20%7BX%2C%20Y%2C%20Z%7D%20data.ipynb)

---

</details>


<details> <summary>Data explanation</summary>
One of the first steps in the project was to get known with the data. As a group we decided that everybody should focus the first few days of receiving the data at exploring the data in such a matter that you will understand what we had received. For that reason I decided to make a tabel with every data colomn that we received and write down what exactly we received. Below you can see the table that I had made.


![Images](/Evidence/Data%20explanation.png)


In the table you can see all the features that we received. And my personal interpretation of it from the beginning of the project. The activiteiten.csv has been used for all the models since we needed to label the activity's. The vyntus.csv has not been used since we didn't have a ground truth to fall back to. The activPal dataset was our main dataset that was being used for all the models. It was cleaned prior by CBS and we could dive into it straight away. 

---

</details>

## Predictive Analytics

<details> <summary>Selecting a model</summary>
Since my tasks in the project group wasn't focused on building a model, it caused that I started very late with building the first model. For that reason most of the models were already used. Instead of building no model, I still wanted to test my Python skills to see if I was able to fit atleast a model to show in the portfolio. Below you can read my journey!

### XGBoost
I had chosen to build the XGBoost model because it's very similar to our Random Forest model. The XGBoost model is an ensembled decision tree model that is known for their low variance and biased results. I came to the conclusion to use XGboost since it was well explained in the following paper: XGBoost Model for Chronic Kidney Disease Diagnosis. For this reason I wanted to try out the model to predict the MET value. 

APA: </br>
A. Ogunleye and Q. -G. Wang, "XGBoost Model for Chronic Kidney Disease Diagnosis," in IEEE/ACM Transactions on Computational Biology and Bioinformatics, vol. 17, no. 6, pp. 2131-2140, 1 Nov.-Dec. 2020, doi: 10.1109/TCBB.2019.2911071.


[XGBoost notebook](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/xgboost%20model%20MET%20and%20fietsen%20v2.ipynb)

---

</details>

<details> <summary>Configuring a model</summary>
For the configuring of the model I took a different approach then most of my group members. I wanted to build a heavy model that would generate multiple models and select the best configuration based on the model score. The following configurations are automaticly chosen by the model by iterating:

- RFE for feature selection
- The amount of trees
- A combination of the above. It will try out every combination and see what combination of trees/features work the best (in a single model) and tries all combinations.


Below you can see the code used to get the optimal amount of trees:

````python
def get_optimal_amount_trees(x, y, max_number_of_trees = 100):
    r2_score_list = {}
    
    train_X, valid_X, train_y, valid_y = train_test_split(x, y, test_size=0.2, random_state=0)

    for i in range(1, max_number_of_trees + 1, 1):
        xgb_r = xgb.XGBRegressor(objective ='reg:linear', n_estimators = i, random_state = 0, verbosity = 0)
        xgb_r.fit(train_X, train_y)
        pred = xgb_r.predict(valid_X)

        optimal_r2_score = r2_score(valid_y, pred)
        r2_score_list[i] = optimal_r2_score

    return  max(r2_score_list, key=r2_score_list.get)
````

Below you can read the code used to get the optimal model: 

````python
    for i in range(1, max_number_of_features + 1):
        print("iteration: ",i)
        rfe = RFE(estimator=XGBR, n_features_to_select=i, step=1)
        rfe = rfe.fit(X_train, y_train)
        temp_best_features = X_train.columns[rfe.support_]
        
        X = all_df[temp_best_features]
        y = all_df['mean_met']
        
        ## Training the new model with best features
        train_X, valid_X, train_y, valid_y = train_test_split(X, y, test_size=0.2, random_state=0)
        
        best_amount_trees = get_optimal_amount_trees(train_X, train_y, 200)
        
        xgb_r = xgb.XGBRegressor(objective ='reg:linear', n_estimators = best_amount_trees, random_state = 0, verbosity = 0)
        
        ## final model
        xgb_r.fit(train_X, train_y)
        pred = xgb_r.predict(valid_X)
        
        #score = r2_score(valid_y, pred)
        score = np.sqrt(MSE(valid_y, pred)) 

        
        print('features: ', temp_best_features, ' r2: ', r2_score(valid_y, pred), ' mse: ', score )

        #   if score > best_r2_score:
        if score < best_mse_score:
            best_r2_score  = r2_score(valid_y, pred)
            best_mse_score = score
            best_model     = xgb_r
            best_features  = temp_best_features
````

Funny sidenote: Since my configuration is being optimized by trying ALOT of combinations. It takes alot of power to find the best model.

---

</details>

<details> <summary>Training model</summary>
To prevent under/over fitting on the model I used the following methodes to prevent this: 

<details> <summary>Feature selection by RFE</summary>
I used RFE to choose the best features for the model. I have chosen for RFE since it looks at the best features that give the best results in your model. By doing this unnecessary features get removed that could impact the model in a negative matter.  

````python
rfe = RFE(estimator=DecisionTreeClassifier(), n_features_to_select=6)
model = DecisionTreeClassifier()
pipeline = Pipeline(steps=[('s',rfe),('m',model)])

cv = RepeatedStratifiedKFold(n_splits=10, n_repeats=3, random_state=1)
n_scores = cross_val_score(pipeline, x, y, scoring='accuracy', cv=cv, n_jobs=-1, error_score='raise')

# report performance
print('Accuracy: %.3f (%.3f)' % (mean(n_scores), std(n_scores)))
````

</details>


<details> <summary>Features for model complexity </summary>
I have created new features to make sure that the complexitiy of the model increased. By doing this I prevented underfitting. 

````python
                stdev_x =  statistics.stdev(activpal_segment['x']) if len(activpal_segment['pal_accX']) >= 2 else 0
                mean_x = activpal_segment['pal_accX'].mean()
````

</details>

<details> <summary>Outliers / data verification</summary>
One of the issues that can occur is under/overfitting by outerliers. To prevent this from happening I have been looking into the data to see if any outlier removal was necessary. Below you can the plots that I have used.

![Images](/Evidence/G-force.png) </br>
![Images](/Evidence/datavisualization_standard_deviation_by_GROUP_VS_INDIVUAL.png)</br>

</details>

---

</details>

<details> <summary>Evaluating a model</summary>
One of the things that I haven't done personally was validating the results with cross validation. This has been done by one of my groupmembers instead.



---

</details>

<details> <summary>Visualizing the outcome of a model</summary>
This part of the chapter shows the results of the XGboost prediction model. 

<details> <summary>Features used</summary>
In this chapter you can read the final features used in the model:

sum_mag_acc', 'weight_kg', 'length_cm', 'bmi', 'age_category',
       'meets_balance_guidelines', 'meets_activity_guidelines',
       'estimated_level', 'mean_speed

</details>

<details> <summary>Tabel with results</summary>

| Score measurement  | Score |
| ------------- | ------------- |
| Mean squared error  | 0.3509541156530997  |
| R2 score  | 0.7206589524175355  |

</details>

<details> <summary>Ground truth vs Prediction</summary>
This plot shows the Ground Truth against the prediction. By reading this plot you can see how accurate the model is against the ground truth.

![Images](/Evidence/Results.png)
</details>


---

</details>


## Communication
Within our project we decided that one member of the project team would take the roll of the communicater. The communicater roll had to do:

- Communicate with the teachers in behalf of other group members
- Communicate with the CBS in behalf of the other group members
- Planning of meetings with CBS/teachers

So whenever we would have questions, you would hand those over to the communicater and he would contact both parties to find the answers. As a group we decided that Colin would take the roll of the communicater for the first part of the project. In the second part of the project we decided that I would take this roll on me till the end of the project. I found out that I was mostly emailing questions, setting up meetings and making sure that CBS had no further questions to us.

<details> <summary>Emailing</summary>
Because I had the communication function within our group (at the second half of the project). I had to communicate with CBS quite often. The topics discussed were mostly about meetings, questions from us, questions from CBS and showing the progress of our project. I really liked this roll, since it gave me the opportunity to be more open and being 
organized. It also helped my group alot that somebody would make sure that CBS was up to date and that every meeting was planned for the upcoming sprint.  

Below you can find some examples of the communication I had with CBS. 

* [Link](/Evidence/Communicatie/Communication_proof_CBS.pdf)

---

</details>

### Presentations
<details> <summary>Presentations</summary>
At the beginning of every sprint, we would decide who would give the next upcoming presentations. I really liked giving the presentations (and my groupmembers definitly didn't), so for that reason you can see that I did a few of them. For every presentation we would come together to work on the content of the presentations. We would do this by explaining to each other what we did, and what we wanted to show the group. My contribution lays in the giving of the presentations and filling the presentations with content. Especially if I had to give them myself, I would verify the content and make sure that they were a certain quality.  


- Internal presentations that I gave
  - [Internal Presentation 2](/Evidence/Presentations/Internal%20Presentations%20%232.pdf)
  - [Internal Presentation 8](/Evidence/Presentations/Internal%20Presentation%20%238_Matt.pdf)
  - [Internal Presentation 13](https://teams.microsoft.com/l/file/D0BF429E-02A8-4673-A489-45D7E4397ED2?tenantId=a2586b9b-f867-4b3c-9363-5b435c5dbc45&fileType=pptx&objectUrl=https%3A%2F%2Fdehaagsehogeschool.sharepoint.com%2Fsites%2FAppliedDataScience_groups-ActivePal%2FGedeelde%20documenten%2FActivePal%2FPresentations%2FExternal%20Presentation%20%2313%20-%20Matthew.pptx&baseUrl=https%3A%2F%2Fdehaagsehogeschool.sharepoint.com%2Fsites%2FAppliedDataScience_groups-ActivePal&serviceName=teams&threadId=19:00f809aeb3ab456ca0c8557806c14993@thread.tacv2&groupId=c8e7435b-82a6-423f-a66a-96dac64e1ee2)
- External presentations that I gave
  - [External Presentation 3](/Evidence/Presentations/External%20Presentation%20%2313%20-%20Matthew.pptx)
  - [External Presentation 13](https://teams.microsoft.com/l/file/D0BF429E-02A8-4673-A489-45D7E4397ED2?tenantId=a2586b9b-f867-4b3c-9363-5b435c5dbc45&fileType=pptx&objectUrl=https%3A%2F%2Fdehaagsehogeschool.sharepoint.com%2Fsites%2FAppliedDataScience_groups-ActivePal%2FGedeelde%20documenten%2FActivePal%2FPresentations%2FExternal%20Presentation%20%2313%20-%20Matthew.pptx&baseUrl=https%3A%2F%2Fdehaagsehogeschool.sharepoint.com%2Fsites%2FAppliedDataScience_groups-ActivePal&serviceName=teams&threadId=19:00f809aeb3ab456ca0c8557806c14993@thread.tacv2&groupId=c8e7435b-82a6-423f-a66a-96dac64e1ee2)
  - [External Presentation 18](https://teams.microsoft.com/l/file/6D656C3E-70BE-495C-837B-347654AA1859?tenantId=a2586b9b-f867-4b3c-9363-5b435c5dbc45&fileType=pptx&objectUrl=https%3A%2F%2Fdehaagsehogeschool.sharepoint.com%2Fsites%2FAppliedDataScience_groups-ActivePal%2FGedeelde%20documenten%2FActivePal%2FPresentations%2FExternal%20Presentation%20%2318%20-%20.pptx&baseUrl=https%3A%2F%2Fdehaagsehogeschool.sharepoint.com%2Fsites%2FAppliedDataScience_groups-ActivePal&serviceName=teams&threadId=19:00f809aeb3ab456ca0c8557806c14993@thread.tacv2&groupId=c8e7435b-82a6-423f-a66a-96dac64e1ee2)  
    

---

</details>

### Paper
As a group we decided that everybody would work on the paper. To make this possible we used the same method as prior documents. First we would devide the paper into certain topics and devide those topics between the group members and everytime somebody would finish their first iteration of the subject then one of the group members would review their work and make a second iteration of the subject. By doing this everybody would be able to give their opinion about the subjects of the paper and you are able to write a very compact paper with the 
thoughts of five group members. 

For writing the paper I had the following tasks to finish. I excluded giving feedback in this, since I would go over every iteration to give feedback to the group.

- I build the first template of the paper. This was later iterated on by Mark and Adnan.
- I helped with the designing of the paper
- Writing the discussion V1
- Writing the discussion V2**
- I wrote introduction V3**
- I wrote study design V3**
- I wrote the abstract V1 in cooperation with the group
- I worked on the design V1 in cooperation, design V2
- I spend a lot of time reviewing and giving feedback

** = iteration based on feedback/comments from group members.
V = Version

---

## Reflection and evaluation
<details> <summary>Reflection on own contribution to the project</summary> 
<b>S</b>ituation:</br> Looking back at the ActivePal project, I really had a good time with the project group. We started off early and planned alot of things straight away from day one. Since the minor was the last step before I can graduate, I almost always gave my 100% since I really wanted to succeed. The project subject was challenging but that helped me to keep my head straight. I tried to contribute as much as possible to all tasks, especially the tasks that were signed in my name. The project group was fun and the longer we were working together, the better the results became. It took some time to get into the project, but it was a fun challenge. 
</br></br>
<b>T</b>ask:</br> One of the hardest tasks within this project was to stay motivated whenever it didn't go as planned. Since I didn't have a programming background, I had some trouble with Datacamp and with the programming. One of the tasks I remember perfectly was building the XGboost model for MET. It was very challenging but I worked very hard on it to show my team something I they didnt expect me to build. My contribution was mostly found by doing the research, thinking about our plan, making plots to show the new insights. I really enjoyed those tasks and they definitly contributed to the project.
</br>
</br>
<b>A</b>ction:</br>Whenever I had trouble with a task or couldn't go forward. I would take reach out on teams or talk about my issues in the daily standups. By communicating exactly what I was up to and the troubles I had. I could get helped easily.
</br></br>
<b>R</b>esult:</br>I am very glad with the results we made as a group. Together we all worked very hard. Not everybody was working on exactly the same speed but almost everybody contributed in such matter that we made progress. Looking back at myself I think I can still get better at taking up advice and really doing something with it. Sometimes I can be stubborn and try to fix it myself instead of asking help. Another lesson I like to take with me is trying more to make everybody feel more welcome even if they don't feel like that way or are very unmotivated. To come to a conclusion: I think I definitly showed the group what I am capable off and that I really wanted to succeed. My contribution definitly helped the project to come to the result we came.
</br></br>

<b>R</b>eflection:</br> I really think I did enough work. In future projects I should be on time more often since sometimes I could be 2-3 minutes late (which is really annoying but mostly caused by Corona). Other then that I think everything went quite well.


---

</details>


<details> <summary>Reflection on own learning objectives.</summary> 
<b>S</b>ituation:</br>At the beginning of the project I decided that I wanted to write down a few learning objectives that needed to be succeeded at the end of the Minor. By setting my own learning objectives, I had a clear view of the things I wanted to learn and it gave me a goal to reach. 
</br></br><b>T</b>ask:</br>The following learnings objectives were written when I first started with the minor. </br>
- I would love to learn the basics of python and be able to build a machine learning model on my own.</br>
- I would love to develop business skills since that's something I want to do in the future. For example I would like to become better in speaking English and I would love to experience giving presentations in English. </br> 
- I like to learn about artificial intelligence and how to use it. </br>
- I like to be more social while working on the project </br>
- I like to take the lead more often, or come up with good idea's instead of keeping them to myself.

</br><b>A</b>ction:</br> To make sure that I really progressed in the objectives I did the following. From the start of the project I stated that I wanted to give as many presentations as possible. This is something I been dealing with for a while and I really want to become better at it. In total I gave 7 presentations in English. So that was really cool but challenging. For learning Python I decided that I would do all objectives to reach 100% in Datacamp. To make sure that I was more social in the project, I would stay longer in the chats, even if we were done and it was just casual talk. For taking the lead I wanted to come forward more often. I think this is still work in progress, I think it's very hard for me to do so. 
</br></br><b>R</b>esult:</br> Looking back at those tasks, I really think I did a good job. I wasn't able to succeed them all. One of the tasks I wasn't able to succeed is about taking the lead more often. In the project I saw myself not taking the lead as much as I wanted to. But instead I did come forward way more often with my idea's and how they could be benefical to the project. However I didnt learn as much about Artificial Intelligence (AI) as I hoped, maybe this is caused by the minor being so much different then I expected. 
If I look at the first task, about learning Python. I definitly can say that I learned alot while working on the ActivePal project. Learning Python was really fun but challenging, I  really liked the freedom that we gotten and that we were able to learn Python in our own speed. Another point that I worked on really hard on was giving presentation in English. It's something I had never done before, so that a really fun experience. Last but not least, the objective about being more social. I feel like I definitly was more social while working on this Minor. Maybe this was caused by the Corona crisis that forced us to do it online.  Either way it gave me a great opportunity to make new friends.

<b>R</b>eflection:</br> I think I did a great job at trying to learn more about my learning objectives. I am glad that I tried to learn Python since it was challenging but very rewarding. In the future I might want to start earlier with really going after my objectives instead of later on in the project when we have more spare time.

---

</details>

<details> <summary>Evaluation on the group project as a whole</summary> 
<b>S</b>ituation:</br>At the beginning of the project our group had six group members. Including three software engineers, four of us had already finished everything except the minor and were ready to finish our school journey. This means that some of us were really motivated to work hard, get quick results and show that we were able to do research. 

</br><b>T</b>ask:</br>This means that in the beginning of the project it was clear that we all wanted to give 100% to get as far as possible as soon as possible. We gave everybody tasks and we started our journey. It started off really good in the first two weeks. Everybody was researching and the first results were good. But after the first three weeks it came forward that some of us were contributing every day, by coming to the meetings, working together and some of our project group didnt. Personally this didn't bother me to much, since we were still progressing fast and I think it project was going good. I started to learn programming in Python and enjoyed it. The first time getting in contact with the projectowner went really well and we went along good. I can say the same about the lectures. The lectures were really fun, engaging and I learned alot. The further we got into the project and the assignments the better we started to work together. Of course it didn't always go smooth so for that reason we started to meet in real life to see each other.  

</br><b>A</b>ction:</br> Whenever the project didn't go as smooth as planned, we would come together and discuss the issues. One of the problems we had would be that some group members were not motivated enough. Because of this the progress got slowed down. To make sure that we would still succeed we decided that we would meet more often and talk to each other multiple times a day. By having good communication we were able to change our work style and get better results. 
</br></br><b>R</b>esult:</br>I am really glad with the end results that we got. We started with six but ended with five. Dimitri was a nice guy to work with but Machine Learning just wasn't his thing. I think for the most part of the project I had alot of fun and was able to easily work together with most of the team. Alot of us really want to work hard and come forward with the best results possible but it was a hard journey. We didn't always exactly knew what was expected and since we were all new to Machine Learning it wasn't always easy. If I look back at the complete picture of the project. I am glad, very glad that I have choosen this Minor. 

<b>R</b>eflection:</br>Looking back at the project I had great fun and learned alot. I worked hard and wanted to succeed. In furtere project I could ask for help more often, and try to see more often where I can easily help somebody. 

---

</details>

## Datacamp
Within this Minor I have been doing Data Camp to learn more about Data Science. In this chapter you can find all the courses that I have finished while doing the Minor. 

![Images](/Evidence/Datacamp.png)

---

## Notebooks
<details> <summary>List of notebooks</summary>
Below you can find almost all notebooks that I have worked on. Of course over time some of them got deleted because they didn't get used. 

- [XGBoost fietsen](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/xgboost%20model%20MET%20and%20fietsen%20v2.ipynb)
- [XGBoost lopen](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/xgboost%20model%20MET%20and%20lopen%20v2.ipynb)
- [XGBoost rennen](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/xgboost%20model%20MET%20and%20rennen%20v2.ipynb)
- [XGBoost staan](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/xgboost%20model%20MET%20and%20staan%20v2.ipynb)
- [XGBoost zitten](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/xgboost%20model%20MET%20and%20zitten%20v2.ipynb)
- [Pearsons](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/pearson_correlation_matrix.ipynb)
- [Crossvalidation](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/Balancing.ipynb)
- [Balancing](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/Balancing.ipynb)
- [RFE](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/feature_selection_matt.ipynb)
- [Analyzing](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/Analyse%20and%20document%20%7BX%2C%20Y%2C%20Z%7D%20data.ipynb)
- [More plotting](https://datascience.hhs.nl:8888/user/17113148/notebooks/activepal/code/src/all_steps_activity_data_analyse_Matt_v2.ipynb)
- And more..
</details>

