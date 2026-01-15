# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#1`

Describe the purpose of your survey:
```
This survey aims to understand the main reasons employees in entry- and lower-level roles are leaving the company and what changes would most improve job satisfaction and retention. Results will be used to identify priority areas for action (e.g., pay, manager support, workload, growth opportunities) and to design targeted retention strategies.

Describe your target population, sampling frame, sampling units, and observational units:
```
•	Target population: All current employees in entry- and lower-level positions at the company and employees who left these roles within the past 6 months.
•	Sampling frame: (1) Current HR roster for eligible roles; (2) HR exit list/contact emails for employees who resigned/terminated from eligible roles in the last 6 months.
•	Sampling units: Individual employees (current or recently exited).
•	Observational units: Individual survey responses from those employees.
•	Sampling strategy: Stratified sampling by department + role level + location (and optionally tenure bands) to ensure representation across areas where turnover differs, with oversampling of departments with the highest turnover. Use the same survey for both groups (current + exited), with branching logic for exit-specific questions.
```

Your 5-10 question survey:
```
1.	What is your current status?
o	Current employee (entry/lower-level) / Left the company in the past 6 months
2.	Which department/team are you (or were you) in? (dropdown list)
3.	How long have you worked at the company (or did you work before leaving)?
o	<3 months / 3–6 months / 6–12 months / 1–2 years / 2+ years
4.	Overall, how satisfied are you (or were you) in your role? (1–7 scale: very dissatisfied → very satisfied)
5.	Which factors most influenced your decision to stay/leave? (Select up to 3)
o	Compensation/benefits, Workload, Manager support, Team culture, Career growth, Scheduling/flexibility, Training/onboarding, Recognition, Work type/fit, Commute/location, Other (write-in)
6.	Please rate the following areas (1–7 scale each: strongly disagree → strongly agree):
o	I had the tools/resources to do my job well
o	My workload was manageable
o	My manager supported my development
o	Expectations were clear
o	I saw a realistic path for growth/promotion
7.	(If left) What was your primary reason for leaving? (single best answer; same list as Q5)
8.	(If left) Where did you go next?
o	Another company same industry / Different industry / School / Unemployed / Prefer not to say
9.	What is one change that would most improve retention for people in your role? (short answer)
10.	Would you be willing to participate in a 15-minute follow-up interview?
•	Yes (provide email) / No

```

## Part B - Survey Evaluation:
(StatsCan GSS – Giving, Volunteering and Participating, 2018 Cycle 33)
Sample type: Probability household survey with one randomly selected eligible household member. 
Sample size: Field sample was approximately 50,000 units; about 40,000 invitation letters were sent for the electronic questionnaire; completion of 24,000 questionnaires was expected. 
Target population: Non-institutionalized persons aged 15+ in the 10 provinces (person-level weighting factor is for non-institutionalized persons aged 15+). 
Sampling frame: Households in the ten provinces (sample described as representative of all households in the ten provinces). 
Survey mode(s): Electronic questionnaire and CATI (computer-assisted telephone interviewing). 
Timeline (collection period):
2018-09-04 to 2018-12-28. 
Response rate: Overall response rate reported as 41.2%. 
Weights: A person-level weight is provided (e.g., WGHT_PER). Bootstrap weights were also created for design-based variance estimation. 
Data processing (error detection/edits): Edits were done automatically and manually at multiple stages (macro/micro), including flow/consistency checks; CATI had built-in range and flow edits. 
Cleaning, imputation, etc.: Imputation primarily used donor imputation (nearest donor via score function), with mean imputation used when donor imputation wasn’t possible. Income was obtained via linkage for many respondents and imputed when missing. 
Sources of error: Non-response is a key source of error (overall response rate 41.2%). Measurement/reporting issues for income were addressed via linkage and imputation, indicating income non-response/quality issues can be important. 
Limitations / known biases:
•	Voluntary survey + nonresponse may introduce nonresponse bias (response rate 41.2%). 
•	Coverage is households in the ten provinces and non-institutionalized population aged 15+, so results may not generalize to institutionalized populations (and territories are not included in the described household coverage). 
Link to documentation and sources used:https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
Statistics Canada IMDB survey page for GSS GVP 2018 (Cycle 33) (methodology, collection, processing, imputation, weights, response rate). 

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 14 January 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
