# Model of Organization – To Be

# Contents

# Summary of changes

Here describe at high level the change(s), and summarize why they should be useful for the organization. Link with critical points identified in As Is analysis.

The aim of managing more projects at the same time, could be achieved orginizing the projects in a more intuitive and efficient way.
Currently, Nextome organizes the files related to projects and all the related documentation by using google drive folders although a  flexible and custom software could be suitable for an increasing number of projects.

The change consists in the implementation of a software that has custom functions related to the services that Nextome offers:
- Add and view a project
- Attach the project plan and the project description to a project
- Set the type of project (development only, localization only, development + localization)
- Link a project to a customer from the CRM
- For locatization projects:
    - Attach digitalized map and signal coverage study
    - Attach a beacon installation company
- For development projects:
    - Attach mockups
    - Select developers
    - Set development milestones
- Analitycs data
    - Analitycs dashboard
    - Montly report via email to the governance

This software will speed up the design and the development processes giving to the managers also a dashboard with measures for KPIs to analyze the trends and improve efficiency.


Argument if the change is first order, second order or third order and summarize the related risks.

The implementation of this software represents a first order change because we are only introducing an IT innovation that minorly modifies the processes of design and development.

Report the here PICK chart used to select the change and argument about it

| | Low payoff| High payoff | 
| -- | -- | -- |
|Easy |Move from the Google suite to the Microsoft suite to take advanantage of Microsoft Teams, creating a team for each project  |Implement a new, customized software to manage projects |
|Hard |Outsource the design and the development process |Hire new people and create different teams|

The following sections are meant to describe in more detail the changes, using the same structure used in the As Is document. If nothing changes, just write 'no change'.

# Business Model Canvas

# IS Dimensions

## Social system

### Size

### Products, services

### Goal, goal type, mission, vision, strategy

### Culture

### Structure

#### IT/IS group / office

### Formalization / specialization/ centralization
This change is a step toward an higher formalization, the structure of the projects and the way it is managed becomes a little more standard.
### Organizational type

## Process dimension

### Conceptual data model

### Processes

Report here BPMN model of process(es) that are changed. In the following table report the software functions needed, especially the functions that are new or modified vs. As is.

The activities for both process are the same, they differ from the AS IS because data and documents will be recorded on the new software instead of google drive.

| Activity in BPMN | Supporting Software functions |
| --- | --- |
| | |

## Technology dimension

### Application portfolio

<!--
Write no change if the portfolio remains as in As Is

Otherwise list here the new portfolio, highlighting new applications, and abandoned applications
-->

No change, the google services will still be used but for doing other things.
The custom application is going to be added to the application portfolio and will be used for managing projects

### Application selection, make vs. buy decision

<!--

Describe the applications considered for the selection

| Application name | Vendor | Description | Price model and fees |
| --- | --- | --- | --- |
| | | | | 

Describe here how the selection of the new application was made

| Criterion | Application1 | Application2 | Application x |
| --- | --- | --- | --- |
| | | | | 

Alternatively argue that the new application should be developed custom for the company.

-->

The market related to the Indoor Positioning is still pretty small (niche market), for this reasons ERP modules related to this field don't exist (or not really specific).

So the solution choosen with the Nextome governance is to develop a custom software that matches perfectly their needs.

### Coverage

Show how the selected application provides the software functions needed (as identified in Process section), discuss gaps, if any

<!--
| Software function needed (from process view) | Software function provided by application selected | Gap analysis |
| --- | --- | --- |
| | | | 
-->

All the software functions needed will be implemented in the new application.

### Hardware software architecture

### Integration

In case a new application is introduced discuss how integration happens in terms of

<!--
- Data exchange (which data is exchanged with other applications)
- Control mechanism (mechanism used by applications to interact, ex message passing, rpc, etc)
-->

- Data exchange: since the software will give the possibility to link a project to a customer from the CRM, data exchange with the CRM related to customer infos will be needed.
- Control mechanisms: the interaction client/server and the communication with the CRM will be implemented using HTTPS request/response. The CRM will expose an API that gives the list of the customers and their informations.


#### Outsourcing

|Outsourcing decision|Yes|No|
|---|---|---|
|Is it strategic for the company?|X|
|The know-how is important?|X|
|Is it commodity (can be fully described)?||X
|Is it available at lower price, higher quality than internally?||X
|Is it subject to law constraints (ex. privacy)?||X

The final decision is to not outsource the development of the new application also because Nextome has a good development capability because of IT people presence (13/17 people ~ 75% of the company) that has deep understanding of software/web development.

The internal development of the custom software will slow a bit the development of the current projects in the short term but will repay in the long run. (TCO)

### IT strategy

The IT strategy continues to be aligned with the company overall strategy, because the aim of this change is to make even more use of their own resources having the possibility to manage more projects.

# Effect of change(s)

## Effect on KPIs and CSFs

(remark, KPIs and CSFs should not depend on the change, but should remain the ones defined in the As Is section – the goal being to compare the effect of the change on the same indicators)

Report only indicators that are supposed to change, argument on why the change has an effect on them, report how much the indicator could change. Do not forget the unit cost of the product / service.

| Indicator (Csf, Kpi) name | Effect | Quantitative estimate of variation (absolute, %) |
| --- | --- | --- |
| | | | 


### Process "Software design"
| Indicator (Csf, Kpi) name | Effect | Quantitative estimate of variation (absolute, %) |
| --- | --- | --- |
|#started| Decrease short term (first year) due to the new custom software development that needs the design manager to work on it, increase long term| Difficult to estimate
|#completed | Dependent to #started| Difficult to estimate
|LT_manager| The management of the design will be faster |  Difficult to estimate
|LT_total| Decrease dependent to LT_manager
|UC_project| Will be increased during the development of the new software (first year) that needs the design manager to work on it but will decrease in the long term  | Difficult to estimate

### Process "Software development"
| Indicator (Csf, Kpi) name | Effect | Quantitative estimate of variation (absolute, %) |
| --- | --- | --- |
|#started| Decrease short term (first year) due to the new custom software development, increase long term| Difficult to estimate
|#completed | Dependent to #started| Difficult to estimate
|LT_manager| The management of the development will be faster|Difficult to estimate
|LT_total| Decrease dependent to LT_manager
|UC_development| Will be increased during the development of the new software (first year) but will decrease in the long term. It will decrease less that UC_project related to the software design process because the change affect it less| Difficult to estimate

Also the customer satisfaction indicator will improve due to faster design and development that will produce a faster delivery for the customer.

## TCO, ROI and Break even

Define the TCO for the change (use a 3 -5 years horizon)

Estimate costs (from TCO) and savings, and discuss the number of years needed to recover the investment

Estimated time for development made by 3 FTEs (RAL 30K) is 4 months

TCO:
- Construction: 3(FTEs)\*30k\*4/12= €30k
- Added cost for decrease in project delivery during the 4 months of development: (3 FTEs out of 15) (Turnover_2021 = € 641.029) Turnover_2021 * 4 / 12 * 3/15 = € 43k
- Deployment: ~1k€ for release on the server
- Operation: ~2k€/year for server management
- Regular maintenance: 0€/year
- Exceptional maintenance: ~5k€/year for bug fixing
- Dismissal: ~2k€ for the export of data and documents


To estimate the benefits of this change let's consider that the every project will last 5% time less using the new software.

duration_new = duration_old * 0,95

This means that it will be possible to conclude more projects per year

nProjectsNew = nProjectsOld * 1/0,95 = nProjectsOld * 1,05

So this change brings a 5% increase in projects delivered and so a 5% increase on the yearly turnover.

For the first year there will be a benefit only for the last 8 months of the year since in the first 4 the software will be in development.

Turnover_2021 = € 641.029

Benfit 1st year: Turnover_2021 * 8 / 12 * 5%  = € 21367

Benefits for the following years: Turnover_2021 * 5% = € 32051


|Period|0|1|2|3|4|Total
|---|---|---|---|---|---|---|
|Cost|Construction: 3*30K/3 = 30k Deployment: 1k Cost for missed projects during the development: 43k|Operation: 2k Maintenance: 5k|Operation: 2k Maintenance: 5k|Operation: 2k Maintenance: 5k|Operation: 2k Maintenance: 5k|100k
|Benefit|21k|32k|32k|32k|32k|149k
|Benefit - cost|-53k|-28k|-3k|22k|49k|49k

TCO = € 100k

ROI = (149k - 100k)/100k = 49%

Break even: 3 years


# Change management plan

Considering the order of the change (first, second, third), discuss the key risk factors related to the change, and sketch a change plan to reduce these risks and introduce the changes in the organization.

The key risk factors related to this change are:
- The manager is not motivated in using the new software and thinks that the new software is too strict and inflexible

Change plan using the ADKAR model by Jeff Hyatt:
- Awareness of need: involvement of the managers during the first steps, using also their opinions to improve the final software
- Desire to participate: promise of RAL increase proportional to the overall turnover increase if the managers start using the new software 
- Knowledge on how to change: training and education on using the new software
- Ability to implement the change: the manager has a tutor during the first project to teach him
- Reinforcement to sustain:
    - € 1k bonus for the first manager who completes 5 projects using the new software
    - 5% RAL increase for managers using the new software

# Conclusion

In summary, why the organization should buy (and pay for) your proposal of change?

The great fortune of this company is that they don't have to commit too much in searching new customers, since their services are high demand, so they can only focus on productivity.

The implementation of this change will give NEXTOME the possibility to handle even more projects increasing the yearly turnover by 5%, without modifying at all the structure of the company or hiring new people.

Furthermore the emplyees will be happier thanks to the RAL increases and this will boost their productivity and discourage them to leave the organization.

It must be said, however, that in order to have a significant increase in turnover, hiring new people is necessary.

The money gain due to this new software can be used in the future with the purpose of hiring new employees and boosting HR.

