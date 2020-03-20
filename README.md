# covid-analysis
Modelling the spread of coronavirus and the likely trends in mortality.

Based on article by Tomas Pueyo (https://medium.com/@tomaspueyo/coronavirus-act-today-or-people-will-die-f4d3d9cd99ca)

The assumptions underpinning the model are that by looking at the mortality rate (the percentage of people who will ultimately die from COVID-19) and knowing how long it takes on average for people to die having been infected we can infer the actual number of people infected at a given point in time.

Note that this will be significantly different from the reported cases due to delays / lack of testing, patients with mild or no symptoms, the lag between being infected, developing symptoms and being tested. Furthermore due to differences in testing it is almost impossible to compare across countries, for example by March 17th South Korea had conducted 295,000 tests with 2.85% returning positive. In contrast by March 14th the US had only tested 44,872 samples with 14.5% testing positive. Death rates are much more likely to be accurate

Having determined an estimate for the number of people infected we can then model the spread of the virus by knowing its doubling rate which seems to be between 2 and 5 days (Tomas Pueyo covers the evidence in significant detail in his blog post!)

We can then estimate the number of deaths in the future on the basis of how many people were likely infected with the disease in the past.

Whilst, it is too early to fully assess the accuracy of the model it seems to do a good job of tracking the current deaths in the US, UK and Italy.
