# MiBICI_database_Analysis
Given the databases in https://www.mibici.net/es/datos-abiertos/ we selected the last months of the past year to identify different statistical patterns and tendencies in the city of Guadalajara. We tried to answer three specifically questions about the information given in the datasets:

### 1. Can you predict the destiny given the charactheristics of the user?
This question is really complex because we have around 300 stations, so we dicided to divide all the stations in 6 different groups and then tried to predict the destiny group given the chracteristics of every user. We adjusted de model LDA to a set of training data and then with the test data we obtained a precission of 64%. The predictive characteristics are: age of the user, gender, start time and duration of the travel.

### 2. What kind of user uses this service at different hours?
We only have the age and gender as characteristics of every user. With this characteristics we obtain the different possible clusters of people and observe the frequency of travels making by each group and obtain the kind of people that uses the service at different hours.

### 3. What kind of pattern do we find in the saturation?
We'll see how much is the saturation of the service, we observe the duration of the travels and hours in which there is more saturation of the service. After doing this, we can see that the service is more saturated in two hours and there is a difference of 8 hours between these two. This tells us that the service is more used when people is going to work and when they leave their employees.

