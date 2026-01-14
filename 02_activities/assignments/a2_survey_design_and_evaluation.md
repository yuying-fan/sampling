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
The purpose would be to identify reasons why employees in entry- and lower-level positions are leaving the company. Also, to identify areas where improvements could increase employee satisfaction and retention. This survey would help the Human Resources Department in developing strategies to improve workplace conditions and decrease turnover.

```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: All current and past entry- & lower-level employees that worked in the company within the past 12 months
Sample frame: List of all employees, the contact/employee records, which include email addresses 
Sampling unit: Individual entry- and lower-level employees selected from the company's employee database
Observation unit: Responses provided by individual employees on the survey regarding their work experiences and job satisfaction
```

Your 5-10 question survey:
```
1. How long have you been working at the company?
2. Which department do you currently work in or most recently worked in? 
3. How satisfied are you with your overall work experience? 
4. Which factors influenced your decision to leave or consider leaving the company? (Select from Compensation, Workload, Management, Career growth, Company culture, Work-life balance, Other) 
5. How likely would you recommend this company to a friend seeking employment? 
6. What improvements would most increase your satisfaction at the company?
7. Did you receive adequate support from your manager/supervisor?
8. Do you feel you had sufficient opportunities for career advancement? 
9. Is there any other feedback you would like to provide to help the company improve employee retention?
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: Stratified random sample. It's a two-stage sampling design with households selected first, then by one random eligible individual within each household
2. Sample size: 24,000 questionnaires were completed

3. Target population: All individuals aged 15 years and older living in private households in the ten provinces of Canada. Full-time residents of institutions (residing for more than six months) are excluded

4. Sampling frame: Uses a frame that combines landline and cellular telephone numbers from the Census and various administrative sources with Statistics Canada’s dwelling frame. Records on the frame consist of one or more telephone numbers associated with the same address (or single telephone number where a link between a telephone number and an address could not be established)

5. Survey mode(s):
Data were collected using a mixed-mode approach, with either computer-assisted telephone interviewing or through a self-completed electronic questionnaire. Respondents could complete the survey in either English or French

6. Timeline: 
Took place from September 4, 2018 to December 28, 2018. This period is the 12 months preceding the interview date

7. Response rate: 41.9%

8. Weights: A person-level survey weight (WGHT_PER) is provided for all respondents to produce population estimates for individuals aged 15 years and older living in the ten provinces. The weights account for the stratified sampling design, non-response, and the rejective sub-sampling of non-volunteers. Bootstrap weights are also provided for variance estimation

9. Data processing: 
Data processing used Statistics Social Survey Processing Environment (SSPE) processing steps

10. Cleaning, imputation, etc: 
Automated and manual edits were applied at both macro and micro levels in various stages (included family, consistency and flow edits) to ensure integrity of matrix data, consistency, valid age based on birth date, and that respondents followed the correct path.
Almost all imputations were made using donor records selected through a score function. In cases where donor imputation was not possible, mean imputation in a pool of donors was used. 
Personal income was not asked so this infomration was obtained by linking to their tax data (for individuals that agreed). Missing information for others was imputed. Family income (obtained through direct linkage) was used instead of household income. Missing information  was imputed

11. Sources of error: 
The survey is subject to both sampling and non-sampling error. Sampling error arises from surveying a sample rather than the entire population and precise estimates of sampling variability can be measured using bootstrap methods. Non-sampling errors can include imperfect coverage, non-response, coverage error, response error, and processing error. As a specific example: households without telephones or those with telephone services that weren't covered by the current frame

12. Limitations, known biases, etc: 
The survey excludes institutionalized populations and households without telephone access. 
Because information is self-reported, responses may be affected by recall error or respondents answering in socially desirable ways. Not all selected individuals participated in the survey, so non-response bias may remain even after weighting adjustments. In addition, the use of rejective sampling for volunteers means that some received shorter questionnaires, which can add to potential bias

13. Link to documentation and any additional sources used: 
https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
For the files, I went and clicked on 2018 hyperlink (which downloads a zip) on this website, https://www150.statcan.gc.ca/n1/pub/45-25-0001/index-eng.htm
```

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
- [x] Create a branch called `assignment-2`.
- [x] Ensure that the repository is public.
- [x] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [x] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
