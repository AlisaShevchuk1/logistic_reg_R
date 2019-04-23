# logistic_reg_R
data for homework
1. Make a prediction using logistic regression 
for Y in bacteria file an for headache in Kostecky file
2. Choose the best threshold for the model, using ROC curve


# bacteria description

- y - presence or absence: a factor with levels n and y.
- ap - active/placebo: a factor with levels a and p.
- hilo - hi/low compliance: a factor with levels hi amd lo.
- week numeric: week of test.
- ID - subject ID: a factor.
- trt -a factor with levels placebo, drug and drug+, a re-coding of ap and hilo

# KosteckiDillon description

- id-Patient id.
- time-time in days relative to the onset of treatment, which occurs at time 0.
- dos-time in days from the start of the study, January 1 of the first year of the study.
- hatype-a factor with levels Aura Mixed No Aura, the type of migraine experienced by a subject.
- age-at onset of treatment, in years.
- airq-a measure of air quality.
- medication-a factor with levels none reduced continuing, representing subjects who discontinued their medication, who continued but at a reduced dose, or who continued at the previous dose.
- headache-a factor with levels no yes.
- sex - a factor with levels female male.
