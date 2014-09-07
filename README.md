ViolenceAgainstWomen
===============================
Project by Nicholas Neuteufel while working for Tremendous Hearts (Cape Town, South Africa)


Written in R language. 

Uses UN Women data (http://www.endvawnow.org/uploads/browser/files/vawprevalence_matrix_june2013.pdf) and the following R packages: randomForest, quantregForest, WDI, rworldmap, and countrycode.

NEXT STEPS:

a) Political, conflict, and cultural indicators

b) Try to get war/polity scores working. Then re-run both imputations.

c) Region analysis (Statistically analyzing trends by continent and regions within continents)

d) Geography-weighted regression (GWR)



VERSION 1.0

*****

STEP 1: Mapping Out Violence (see Mapping) -- COMPLETE 

http://imgur.com/H0W1OoO

*****


STEP 2: The "Missing" Statistics--trying to predict missing data

A) Experimentally -- COMPLETE 

a) Random Forests (RF) -- complete (see ExperimentingDataImputation)


B) Empirically -- COMPLETE-ish

a) Using older data from WDI to fill-in incomplete cases (NAs) -- COMPLETE

b) Comparing empirical data to RF predicted imputation (pending C(a))


*****

STEP 3: Predicting key countries with missing data (with both 95% confidence and prediction intervals)

No particular order:

a) Asia: China, South Korea, Saudi Arabia, Iraq, Iran, Pakistan, Indonesia.

b) Latin America: Argentina.

c) Africa: South Africa.

d) Europe: Spain, France.

*****

STEP 4: Mapping the world; project evaluation.
