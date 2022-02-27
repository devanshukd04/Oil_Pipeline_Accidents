# Oil_Pipeline_Accidents

![image](https://github.com/Atharva-D/git-mlsc/blob/main/pipeline_incidents.png)

## Inspiration
**Pipelines** carrying oil and gas in the United States are not adequately regulated, inspected, or enforced. The three types of pipelines: natural gas transmission lines, which transport natural gas from production areas to processing plants and municipal distribution areas, liquids (including oil), and natural gas distribution lines, which transport gas from plants to customers, all have a troubled history of spills, contamination, injuries, and deaths.<br/>
Millions of miles of pipelines in the US have resulted in the following: 
1. more than 5,500 total incidents
2. almost 600 injuries
3. more than 125 fatalities
4. more than 800 fires
5. almost 300 explosions
6. more than $4 billion in damages
7. almost 30,000 people who had to be evacuated<br/>

The United States must halt the fossil fuel epidemic and transition as soon as possible to clean energy sources that do not leak, spill, or explode, therefore protecting our clean air, clean water, communities, and wildlands.<br/>
There is a need to bring this issue into limelight by addressing it publicly and making everyone visualize the troubled history.


## What it does
**Opalution** is a solution provided for the prevention of oil pipeline accidents in the United States, based on analysis and visualization of the Oil Pipeline Accidents dataset. The dataset includes a record for each oil pipeline leak or spill reported to the Pipeline and Hazardous Materials Safety Administration since 2010. It aims to bring the facts into limelight through graphical representations of the accidents, costs, cause of accidents, fatalities, etc. The pipeline monitoring system is given as a solution which will alert them whenever leakage is detected.



## How we built it
Python is used exclusively as a programming language for data analysis and visualization. For a visual representation, NumPy, pandas, matplotlib, seaborn, and Plotly libraries were utilized. We used Chart-Studio's API to deploy the visualization on a Web application, which will be great for a better experience and explanation. We even created a simulation that will notify the user of the leaking. The model's components include an Arduino Uno, an MQ series sensor, a buzzer, and an LCD for displaying the alert message.


## Challenges we ran into
In terms of dimension, the dataset used was quite complex (2795 rows, 48 columns). Because of the NaN values, unreported numbers, and so on, data pre-processing proved difficult. The Chart-Studio API was used to deliver the interactive visualizations created with Plotly to the web.


## Accomplishments that we're proud of
We attempted to create a data science-based project aimed at analyzing oil leaks leading to accidents. We are happy that we created a simulation model that alerts administrators about the leakage, attempting to tackle a massive problem. Corrosion is the second leading cause of pipeline accidents, and we have provided a method to address it. On average, a company incurs an economic loss of around $1 million, and this initiative may assist in overcoming the same. The initiative will primarily aid the United States in making pipeline-accident prevention choices.


## What we learned
We learned about various libraries such as NumPy, Pandas, Matplotlib, Seaborn, Plotly, etc. available in python for visualization and analysis. The Chart-studio's API for deploying the interactive graphs on the website. We also learned about using Tinkercad for giving simulating solution for gas/liquid detection.



## What's next for Opalution
As we analyzed the dataset we came to a conclusion that the major two reason of this leakage is equipment failure and corrosion, and to over come that we are planning to use a ultrasonic testing which check for the width of the pipe and which help the user to know about the probability of the accident.
