# Data Scientists' Job Satisfaction
Part of a course assignment.

## Dataset Detail

| Variable              | Role     | Description                                                                                                                                     |
|-----------------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------------
| JobSatisfaction       | dv       | Satisfaction of a respondent with the current job, expressed on a scale from 1 (totally unsatisfied) to 5 (totally satisfied).                  |
| Age                   | Control  | Age of the respondent in years.                                                                                                                 |
| EmployerSize          | Control  | Size of the company a respondent works for, expressed as the median of indicated ranges (e.g., 750 means that the indicated range was 500 to 999 employees), except for the range ‘10,000 or more’, which was coded as 10,000. |
| EmploymentDummy       | Control  | Dummy that indicates if a respondent has a full-time (0) or part-time (1) contract.                                                             |
| JobFunctionDummy01    | Control  | Dummies that express the nature of the respondent’s work: 00 = data scientist, 01 = data analyst and 10 = data engineer.                        |
| JobFunctionDummy02    | Control  | Dummies that express the nature of the respondent’s work: 00 = data scientist, 01 = data analyst and 10 = data engineer.                        |
| CompensationAmount    | Control  | Reported yearly salary, expressed in US dollars.                                                                                               |
| RemoteWork            | Control  | Remote work frequency of a respondent. Used scale: 1 = never, 2 = rarely, 3 = sometimes, 4 = most of the time and 5 = always.                  |
| Tenure                | Control  | Number of years the respondent works for a company, expressed as the minimum value of the indicated ranges (e.g., 4 means that the indicated range was 3-6 years), except for the range ‘More than 10 years’, which was coded as 10. |
| BarriersOrganizational | iv       | Mean score on answers given to 7 items regarding perceived barriers in terms of organization (e.g., 'At work, how often did you experience these barriers or challenges within the past year? - Inability to integrate findings into organization’s decision-making process'). Used scale: 1 = rarely, 2 = sometimes, 3 = often and 4 = most of the time. |
| BarriersSupport       | iv       | Mean score on answers given to 5 items regarding perceived barriers in terms of support (e.g., ‘At work, how often did you experience these barriers or challenges within the past year? - Lack of funds to buy useful datasets from external sources’). Used scale: 1 = rarely, 2 = sometimes, 3 = often and 4 = most of the time. |
| BarriersTechnical     | iv       | Mean score on answers given to 8 items regarding perceived barriers in terms of technology (e.g., ‘At work, how often did you experience these barriers or challenges within the past year? - Scaling data science solution up to full database’). Used scale: 1 = rarely, 2 = sometimes, 3 = often and 4 = most of the time. |
