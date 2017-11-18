# Should Travelers Avoid Flying Airlines That Have Had Crashes in the Past? 
### _Guided by Guided by Prof. Michael Schermann_

_**For summary of the project, please watch this video -**_ https://drive.google.com/open?id=18RJjFMqIBDHCOmdey4SyDnrwhZ_XXabQ

_**Link to Tableau Public -**_  https://public.tableau.com/profile/ritu.pardasani#!/vizhome/Deceptive_Project_Ritu/Dashboard2?publish=yes

## Introduction 

Good visualizations have immense persuasive power which people often try to misuse. The **data can be easily misleading** with respect to the way it is represented. There are a lot of ways to tweaking the data without actually changing it. Axis manipulations, bad color maps, non-zero baselines, exploiting the “other” option, the misleading pie charts, bad usage of sized bubbles are some of the various ways in which visualizations can be depicted in our way. 

In this project, I will try to perform deception by excluding some data and dramatic representation of the depicted data. 

## Project Outline

This project consists of analysis of the safety of various airlines based on the accidents that have taken place in the past. It consists of fatal accidents that took place in two spans of 15 years i.e. 1985-1999 and 2000-2014. It also includes fatalities (number of deaths) of those accidents. The data is segregated on the basis of Airline.  

## Data and Data Source

### Raw data:

Each year there are several incidents happening with different airlines irrespective of whether they were fatal or non-fatal mishaps. The data consists of different airlines and the data of their mishaps over the span of 30 years. These 30 years are divided into 2 spans of 15 years – 1985 to 1999 and 2000 to 2014 ; on the basis of year in which they occurred. There are columns separating non-fatal and fatal mishaps along with the number of deaths in those fatal mishaps. 

<img width="699" alt="table 1" src="https://user-images.githubusercontent.com/32205588/32971053-5e8cf52e-cba0-11e7-97d0-8872650ef019.png">


### Cleaned data: 

I considered only the following measures for my analysis –

<img width="899" alt="table 2" src="https://user-images.githubusercontent.com/32205588/32971071-71101d5c-cba0-11e7-8f4e-b3fed87eef3b.png">

### Data Source:

https://github.com/fivethirtyeight/data/tree/master/airline-safety


## Argument

#### _Should Travelers Avoid Flying Airlines That Have Had Crashes in the Past?_

### _Why_ I chose this argument?

•	Firstly, People are becoming biased towards choosing an airline if it has faced mishaps in the past. Is it rational to do so? I feel, crashes are random events and can happen to any airline. Hence this kind of thinking could be changed or could be enhanced using the same data. I wanted to try doing both. 

•	Secondly, majority of the people have started to use air travel as the mode of transport. Usually, people compare comfort and pricing while choosing any airline. However, nowadays choices to choose from have extensively increased. Therefore, at this point people consider the reputation of the airline which usually is built by their safety in terms of accidents or mishaps. 

## Truthful Visualization 

<img width="872" alt="actual version" src="https://user-images.githubusercontent.com/32205588/32971139-ba61fbd8-cba0-11e7-9de9-3f5bf4ec7b61.png">


### Argument Model:

_**•	Claim:**_  Travelers should not avoid flying Airlines that have had crashes in the past as there is no consistency in crashes whatsoever. 

_**•	Warrant:**_ Academic studies, articles and News show that Crashes are random events which can occur to any airline anytime for any reason. 

_**•	Backing:**_ Kenya Airways and Gulf air, both were fatality free until 2000. Also, Japan Airlines, SWISS, Aviana, Iberia, Vietnam, South African etc. have had major crashes in the past but never faced fatalities again. 

### About the truthful version:

The claim of the data is trying to show that there are inconsistencies between the mishaps of different airlines between the two time periods. 

This visualization proves that we cannot predict if an airline with a high number of mishaps in a particular is unsafe and vice versa. 

### _Why_ is this the truthful version?

1.	The above visualization shows all the airlines and their fatalities of both the 15-year spans. No data is hidden.

2.	It can be seen that there are many inconsistencies like Kenya Airways had zero fatalities in the time period 1985-1999 and had a steep increase of almost 300 fatalities between the time period of 2000-2014. 

3.	There are lot of other airlines like Japan Airlines, SWISS Airways etc. that had high number of deaths in fatal accidents happened in the span of 1985-99. On the other hand, there were no fatalities (“zero”) for the same in the span of 2000-14. 

4.	Since, all the data is shown with a clear axis, the inconsistencies between the data can be clearly seen and can be concluded that the data doesn’t show any kind of trend whatsoever. Thus, this is the truthful version.

## Deceptive Visualization

<img width="681" alt="deceptive-version" src="https://user-images.githubusercontent.com/32205588/32971231-135bfb62-cba1-11e7-8ebc-0fde8d36d925.png">

### Argument Model:

_**•	Claim:**_  Travelers should avoid flying Airlines that have had crashes in the past as there is consistency in crashes. 

_**•	Warrant:**_ Malaysia Airlines faced two incidents one by one in the same year (2014). The incidents don’t appear to be related, but that isn’t preventing people from insisting that they’ll never fly Malaysia Airlines again.

_**•	Backing:**_ Academic studies have found that high-profile crashes can shift passenger demand away from the airlines involved in the disasters.


### About the deceptive version:

This visualization supports the above mentioned claim. Since, the visualization shows that the airlines that have had crashes in the first span (1985-99) also have had crashes in (2000-14). Hence, a predictive pattern of mishaps in the airlines can be seen. We can easily state that if an airline has more number of mishaps in a particular time period it’ll continue to be like that and it is safe to say that the particular airline is unsafe and vice versa. 

### _Why_ is this visualization deceptive?

1.	First and foremost, this visualization doesn’t show the whole data. It only shows selected data.

2.	It only shows the consistencies in the mishaps & fatalities, hiding the inconsistencies.

3.	All the airlines which have had fatal accidents in both the time spans are shown. Number of deaths in those fatal accidents are also shown. 

4.	To show this data dramatically, usage of red cross is done. Since, red is always linked with danger and so is the cross sign. 

5.	Overall, this visualization clearly conveys that the airlines have a pattern and shouldn’t be used if they have had accidents in the past. 

## _Why_ are the two versions rebuttal to each other?

•	Both show strong reasons on the chart to support their particular arguments. 

•	Both are using the same data source, the way of depicting the data is changing the whole argument. 

•	Both the versions have their backups and warrants. 

## How did I implement the class concepts?

### 1.	Argument Model:

Having an argument is the most important part of the whole checklist. Everything is or can be resolved accordingly. After choosing my data and cleaning it, I came up with my claims, warrants for those claims and backing for the same. This is how I came up with my main argument. 

I have mentioned this model separately with the details above with my two versions of visualization. 

### 2.	Audience:

Audience is the second most important thing, as only after considering some important factors of the audience we can move ahead and make the visualization pervasive. 

The audience for airline safety could a lot of different sets of people like the airline companies themselves, insurance companies, government, FBI and other such organizations and most importantly prospective travelers. 

As my argument itself is focused on travelers, I have chosen prospective travelers/flyers as my audience for both of my charts. 

Now, addressing some important factors related to the audience:

  _**•	Needs:**_ The flyers are the ones who are affected the most due these crashes and hence prospective flyers need to know that is it safe to fly through a particular airline or not. This need only decides whether the flyer will choose that particular airline or not. 
  
  _**•	Wants:**_ Wants are the way they would want to see this data. My visualizations (both the true and deceptive version) are made in a way which is understandable by everyone (also those who are not skilled in reading charts).
  
  _**•	Fears:**_
  
        ♣	Is the airline safe?
        
        ♣	Will it again face an incident? 
        
        ♣	How many incidents has it faced already? 
        
        ♣	Were all of those incidents fatal accidents? 
        
        ♣	How many fatalities happened in those incidents? 
        
        ♣	Is there a pattern?
        
        ♣	Can the crashes be predicted?

All of the above mentioned questions are the fears of prospective flyers. My visualizations answer all the questions mentioned above. 

### 3.	Metrics + Action Options:

I have taken number of deaths (fatalities) for both the spans (1985-99 and 2000-14) to show the inconsistencies and consistencies both. 

The goal was to prove that:

   ♣	The crashes are inconsistent for the true version.
   
   ♣	The crashes are consistent for the deceptive version. 
  
I also tried using other metrics like just the number of incidents occurred in both the spans and number of fatal accidents occurred in both the spans. I also tried prove consistency by showing zero consistencies (showing airlines that have had zero accidents in both the spans). However, all of these metrics were not promisingly sufficing my goal. 

**Actions invoked:**

   ♣	_**True version –**_ The prospective flyers will not avoid airlines that have had crashes. People will stop worrying so much and select airlines on some other parameters considering that mostly all airlines are safe. 
   
   ♣	_**Deceptive version –**_ The prospective flyers will not fly through the airlines shown in the chart. Considering so many fatalities, people will consider these airlines as unsafe and hence won’t travel using these. 


### 4.	Situational Framework: 

In this situation, I have to perform deception. There are 2 types of deception:

_**♣	Chart level deception:**_  When the user interprets the wrong data, i.e. the data is visualized in such a way that the user ends interpreting the data wrongly even if the underlying data is correct.

_**♣	Message level deception:**_ When the visualization is misrepresented and the user is forced to conclude incorrectly even when the interpretation of the data by the user is correct. 

The deception type I have used is ‘message level’ as I have misrepresented the data by excluding some of the airline names. 


### 5.	Data Validation:

My visualizations and their explanations along with warrants and backing are validating the data that I used. The data is complete, not changed and no assumptions have been made about the topic. The data depicted by the charts is the real data from the data set about airline safety. Lastly, as there is only one data set, there was no integration problem. 

### 6.	Aesthetics: 

♣	The best way to represent this data and covey the message was to show the data using scatter plot. 

♣	I have used different symbols for both the charts on purpose. The red cross sign is used deliberately to give a negative “danger” effect. 

♣	The titles of the chart pretty much explain the chart’s purpose. 

♣	The name of the axis is clearly mentioned as the comparison is between two different time spans. 


## Intermediate versions and Failed Visualizations

As this was a deceptive project, I tried a lot of techniques (mostly various idioms) to convey my claims. In this process I came across a lot if intermediate versions and failed visualizations. 


                                                      *1*
                                                      
<img width="532" alt="1" src="https://user-images.githubusercontent.com/32205588/32971546-8f817f90-cba2-11e7-9765-bab6ce379ba4.png">


This visualization shows the airlines with zero mishaps with zero fatalities in both the time periods. Due to the value being zero they were difficult to plot on any of the carts, hence I used a table to depict the airline names and the number of fatalities which are all zero. This chart succeeded in showing the consistency but fails to prove the argument and support the claim. Hence I didnt use it. 


							*2*
                                                      
 <img width="630" alt="2" src="https://user-images.githubusercontent.com/32205588/32971640-fa06442c-cba2-11e7-8ad0-4deb39e4d381.png">
 
 This visualization just shows the incidents (fatal or non fatal both) that took place in both the time spans (1985-99 and 2000-14). The trend line shows that there is pattern. However, the argument cannot be explicitly supported by this chart. While this chart helped me get a direction, as a slight pattern could be seen. 
 
 
 															
							*3*
																											
<img width="898" alt="3" src="https://user-images.githubusercontent.com/32205588/32971778-ad18fa50-cba3-11e7-9ad3-88498234955f.png">

I tried to convey the same message using a bar chart, so that an easy comparison of the fatalities can be seen with two bars. However, this chart looked very complex and didn't convey the message strongly. Secondly, scrolling makes people loose the question that they are looking for. Hence I didn't use this type of a chart. 


							*4*
																											
<img width="896" alt="4" src="https://user-images.githubusercontent.com/32205588/32971856-15e5a3f8-cba4-11e7-95ca-5ef02f2cdee9.png">

This visualization shows a comparison of fatal accidents and the number of deaths due to those fatal accidents. I chose to show this way because there were airlines who had less number of fatalities but had more fatal accidents and vice versa. I was trying to see a trend and hence I tried this. This chart doesn't really show anything and is difficult to comprehend, hence was not used. 


							*5*
																											
<img width="592" alt="5" src="https://user-images.githubusercontent.com/32205588/32971966-a80f60b6-cba4-11e7-8e7c-554a0745c73f.png">

I decided to change the parameter to fatal accidents of both the time spans to see the trend. This chart also didn't show any kind of comparison, contrast or trend. Hence, was not used. 


							*6*
																											
<img width="686" alt="6" src="https://user-images.githubusercontent.com/32205588/32972021-e8e1140e-cba4-11e7-9b9e-eb313756c695.png">

I tried to make separate visualizations for both the time spans. This chart shows accidents and fatalities for 1985 to 1999.


							*7*

<img width="692" alt="7" src="https://user-images.githubusercontent.com/32205588/32972074-38dcd47a-cba5-11e7-9675-e150fa92d9de.png">

This chart shows the accidents and fatalities for 2000 to 2014. 


							*8*
																											
<img width="1058" alt="8" src="https://user-images.githubusercontent.com/32205588/32972104-5bc4c592-cba5-11e7-8717-d31e38d0e6cb.png">

This combined chart was also made to see any comparisons, contrasts or trends between the two. This was comparitively easy to read, but was difficult to analyze. Hence was rejected. 

## Take aways from this project

With visualization being used extensively, considering its high persuasive power, deceptive visualization has found its way into the main stream industries where we are often conned into interpreting wrong information.

♣	Firstly, this project helped me develop a complete sense of building and analyzing a visualization, where not only visuals but the interpretation matters.

♣	Secondly, there is always a way to tweak and misrepresent data and to analyze the data and the visualization for any deception. 

♣	Lastly, the same visualization can either be truthful or deceptive, depending upon the claim. Hence, 
the claim plays a very important role in designing any visualization 

## Refrences

https://fivethirtyeight.com/tag/airline-safety/

https://github.com/fivethirtyeight/data/tree/master/airline-safety

https://www.thedailybeast.com/why-are-asias-planes-crashing-all-over

http://www.nydailynews.com/news/world/obama-pilot-unsafe-airlines-won-fly-article-1.2215362

https://www.cnbc.com/2014/12/30/despite-fatal-airline-crash-statistics-flying-is-still-safe.html





