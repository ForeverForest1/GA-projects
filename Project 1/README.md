#__Project 1: SAT & ACT Analysis__

__##Problem statement__
This study aims to identify the trends in SAT and ACT participation rates and scores, based on state-level statistics from continental US for 2017 and 2018, which are the 2 years following the enactment of the revised SAT format. The report will conclude with preliminary recommendations on which states to target for initial trials to improve SAT participation rates as well as brief discussion for future studies to refine the results.

__##Approach of this study__

1. Data cleaning
2. Data exploration to identify trends and correlations in relation to real-world developments
3. Define potential approach to shortlist states for preliminary trials
4. Identifying states which fit the defined criteria, and discuss approach for future studies

__##Data Dictionary__

|Feature|Type|Dataset|Description|
|:---|:---:|:---:|:---|
|State|Index|SAT/ACT|US state which the ACT and SAT scores are taken from|
|act_2017_participation|float|ACT|Members of the graduating class who had taken the ACT test in 2017 as a percentage of the total number of high school graduates that year in a particular state|
|act_2017_eng|float|ACT|State-level mean score for ACT English subject test in 2017|
|act_2017_math|float|ACT|State-level mean score for ACT Math subject test in 2017|
|act_2017_reading|float|ACT|State-level mean score for ACT Reading subject test in 2017|
|act_2017_science|float|ACT|State-level mean score for ACT Science subject test in 2017|
|act_2017_composite|float|ACT|State-level mean ACT Composite score (average of English, Math, Reading and Science scores) in 2017|
|act_2018_participation|float|ACT|Members of the graduating class who had taken the ACT test in 2018 as a percentage of the total number of high school graduates that year in a particular state|
|act_2018_composite|float|ACT|State-level mean ACT Composite score (average of English, Math, Reading and Science scores) in 2018|
|act_2018_eng|float|ACT|State-level mean score for ACT English subject test in 2018|
|act_2018_math|float|ACT|State-level mean score for ACT Math subject test in 2018|
|act_2018_reading|float|ACT|State-level mean score for ACT Reading subject test in 2018|
|act_2018_science|float|ACT|State-level mean score for ACT Science subject test in 2018|
|sat_2017_participation|float|SAT|Members of the graduating class of 2017 who had taken the SAT as a percentage of the total number of high school graduates that year in a particular state|
|sat_2017_erw|float|SAT|State-level mean score for SAT 'Evidence-Based Reading and Writing' test in 2017|
|sat_2017_math|float|SAT|State-level mean score for SAT Math test in 2017|
|sat_2017_total|float|SAT|State-level mean total SAT score (sum of scores for 'Evidence-Based Reading and Writing' and Math tests for 2017|
|sat_2018_participation|float|SAT|Members of the graduating class of 2018 who had taken the SAT as a percentage of the total number of high school graduates that year in a particular state|
|sat_2018_erw|float|SAT|State-level mean score for SAT 'Evidence-Based Reading and Writing' test in 2018|
|sat_2018_math|float|SAT|State-level mean score for SAT Math test in 2018|
|sat_2018_total|float|SAT|State-level mean total SAT score (sum of scores for 'Evidence-Based Reading and Writing' and Math tests for 2018|


__##Conclusions/Recommendations__

__Key trends observed in datasets:__

* Participation rates tend to correlate negatively with total score for both ACT and SAT in both years. Higher participation usually leads to greater spread in candidate abilities, which likely causes a decrease in mean total score.

* ACT and SAT participation rates tend to be negatively correlated. This is likely because most students tend to take either one of the test before high school graduation.

__Recommendations__
This study suggests taking a calibrated approach to identifying factors that could influence SAT adoption, to help College Board decide which states to invest resources into to raise SAT participation rate. A small scale trial targeting 4 initial states is proposed. These states were identified based on the factors of state-wide participation in standardised tests, SAT participation rate and SAT scores Favorable combinations of factors as well as states which do not conform strongly to the identified trends could be further investigated.

The final list of identified states for initial testing are:

Group 1 (low SAT participation, high SAT score) : Iowa
Group 2 (low SAT participation, low SAT score) : New Mexico
Group 3 (high SAT participation, high SAT score) : Oregon
Group 4 (high SAT participation, low SAT score) : California