-----------------------------------Hello Everyone !!! ------------------------------------------------

This Repository contains the source code of an Agent based model for the simulation of COVID-19 built using official data from Tamil Nadu government website.

Language : Python 3.9.*, (recommended 3.9 and above)
IDE and format : Jupyter notebook, .ipynb (note book)

The core packages used:
1. Mesa (An open source package which provides Agent based simulation platform)
2. Bokeh (An interactive tool using which visualizing data becomes more sophisticated)

Files in repository:
1. COVIDABM-Version 2.0 - The source code in .ipynb format in which the project is built.
2. Positive Cases.xlsx - The excel file containing the COVID -19 positive (clinically tested positive for the disease) cases data collected day by day for 3 months from Tamil Nadu Government (a state in India)
3. Vaccinated.xlsx - The excel file containing the vaccinated details collected day by day for 3 months from Tamil Nadu Government (a state in India)

Scope:
1. The project was built with hopes to simulate the spread of COVID 19 pandemic to a small scale of population.
2. To built a trust worthy simulation of the disease - the spread rate of the virus and the vaccination rates are based on Mathematical calculations done by other scholars making the work legit.
3. To provide a detailed graph on how the Susceptible (prone to acquire the disease), Infected (affected person), Removed (dead person), Immunized (Vaccinated) graphs move over the time line.

Working:
Using the Mesa tool we have created a virtual environment in which population of your desired numbers can be fitted and a simulation can be run. 
The system asks the user to input the number of person and to enter the district and city name. Since the project incorporates publicly available data from Tamil Nadu government, such a real time simulation can be done, paving way for researches and case studies.
Once the information sought are provided, from the Positive cases and Vaccinated data files, information is pipelined and the simulation begins.
The time elapsed is calculated by steps (steps of Mesa are roughly to be considered as days) at the end of the simulation, the time elapsed and the remaining counts of individuals are shown to the user.
The simulation (interaction between the agents/persons) can be better viewed using the Bokeh modules provided in the respective code snippets.
At the end of the program, a line chart depicting the complete events of our simulation will be downloaded to the local system. Allowing further studies and research on the subject.

Creator notes:
I have given you the gist of what happens in the project. Please feel free to download and work around the codes. I have also mentioned comments in between the cells defining what's what.

------------------------------------------------------------Happy coding!!!--------------------------------------------------------------------------------
