Problem Statement: 
------------------

The objective of this project is to build a notebook about your insights from exploring these real raw COVID-19 data from CDC website (USA only) to answer the following questions:

#. What is the total number of confirmed cases per state from March to June 2020?
#. What do you think about fairness of vaccine distribution across the US? 
#. How do you describe distribution and progression of the pandemic in the US?
#. Based on these data do you think the covid will go away?
#. Any unexpected outcomes you discovered from these data?

Imagine you will present this notebook to a Kaggle audience, or present as a self contained tutorial. Your notebook should tell a cohesive story containing your insights about this COVID-19 data. Illustrate all your steps to show the data preparation and exploration of the data that you used to justify and convince us with your insights. Visualization would be preferable to present the answers, but whatever you believe is the best way to communicate your insights works for us. 

You can use any resources (including us) to help with the pandas code you write during notebook prep. Think of this notebook as a showcase of your creative approach towards teaching and evangelising pandas for data science, and not simply a demonstration of your grasp of pandas. 
Optional questions to answer (time permits and if you think they fit your notebook story):
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. According to MeicineNet,  second wave is defined as a phenomenon of infections that can develop during a pandemic. The disease infects one group of people first. Infections appear to decrease. And then, infections increase in a different part of the population, resulting in a second wave of infections. When do you think the second wave happened?
#. Did warm weather stop the outbreak of covid?
#. What are the chances that covid will hit again?
#. Why is covid dangerous?
#. What insights do you have for both infection and mortalilty rates in first and second wave?




Data:
-----

Data is avaialable in the data folder.

#. United_States_COVID-19_Cases_and_Deaths_by_State_over_Time.csv

            * submission_date: Date of counts
            * state: Jurisdiction
            * tot_cases: Total number of cases
            * conf_cases: Total confirmed cases
            * prob_cases: Total probable cases
            * new_case: Number of new cases
            * pnew_case: Number of new probable cases
            * tot_death: Total number of deaths
            * conf_death: Total number of confirmed deaths
            * prob_death: Total number of probable deaths
            * new_death: Number of new deaths
            * pnew_death: Number of new probable deaths
            * created_at: Date and time record was created
            * consent_cases: If Agree, then confirmed and probable cases are included. If Not Agree, then only total cases are included.
            * consent_deaths: If Agree, then confirmed and probable deaths are included. If Not Agree, then only total deaths are included.

#. covid19_vaccinations_in_the_united_states.csv

