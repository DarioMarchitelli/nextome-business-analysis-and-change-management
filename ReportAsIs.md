# Model of Organization – as is

# Contents


# Identification

Name: Nextome 

Address: Via San Francesco 31, 70014 Conversano - Italy

Fiscal ID: 07546950721

Ateco: 62.01

Website: https://nextome.com

# Financial and legal information

Legal form: srl

Turn over year 2021: € 641.029

# Business Model Canvas

Remark: key processes box must be consistent with Process dimension (below)

Key Partners:
- iBeacons providers (Sensor ID)
- Microsoft Azure for Cloud
- Additional Features for Nextome App
- Social Network integration in App (Facebook, LinkedIn, Twitter)
- ABI Research, GrizzlyAnalytics, ZDNet
- Indoors map providers
- Companies that outsource web/mobile development
- Solution providers
- Independent software vendors
- System integrators
- Universities (Politecninco di Bari, Politecnico di Milano, Sapienza di Roma, Aldo Moro di Bari)

Key Activities:
- Sell licenses for the software to compute indoor position
- Distribution
- Technology Innovation
- Understanding of needs and constraints for each installation environment
- Acquire opportunity to commercialize the navigable digital/physical space
- Consulting for web/mobile development

Key Resources:
- Intellectual Properties
- Human Resources (Web/Mobile developers, R&D, Sales, UX/UI designer, Accounting)
- Two offices in Conversano

Value proposition:
- Solve the problem of indor positioning and wayfinding with precision under a meter
- App and tools to use and manage the software
- Advertising services
- Asset tracking

Customer relationships:
- B2C: 
    - No communication with the end users and no B2C customers (the service is indicated only for B2B integrators)

- B2B:
    - Self service via website
    - Personal assitance with sales office and customer relationship via email or call

Channels:
- Web Presence
- Mobile Advertisement platform
- Social Networks (Facebook, Instagram, LinkedIn)
- Hackathons and events
- Museums/Retail/Exhibitions innovations webinars 

Customer Segments:

- System integrators
- Building Owners (analytics)
- Developers (SDK integration)
- Museums (Nextome App) with thematic tours, advertising and in-app purchases
- Manufacturing (employees tracking)
- Exhibitions, Airports, Travel ,Hospitals, Universities (Research), others ….  
- End-Users (for In-App purchases, advertising)

Cost Structure:
- Research and Developments (Innovations)
- Advertising and Promotion
- Customer Care
- Low Cost Beacons infrastructure for each building
- Legal contracts with each building
- Human resources wage
- Cost for hosting and IT infrastructure

Revenue Streams
- Mobile Advertising
- In App purchases (temathic tours,media content, physical objects, …) 
- Licensing SDK
- Analytics
- Proximity Marketing
- Beacons DemoKit with Nextome SDK License (University & Research)
- Pilot Installations
- Premium Assistance
- Time and material in case of consulting for web/mobile development


# IS Dimensions

According to the definition of Piccoli and Pigni, an IS has four dimensions. In the following they are described under sections Social system (Structure and People), Process, Technology.


## Social system

### Size

15 FTEs for 2021 (13 Full-time, 4 Part-time 50%)

### Products, services

- Indoor wayfinding and navigation: users and customers can move and find their way easily and quickly inside indoor spaces
- Indoor tracking and monitoring: track and monitor people and assets in real-time 

### Goal, goal type, mission, vision, strategy

The goal of Nextome is to provide indoor positioning services, by selling the licence for their software, to system integrators (utilitarian goal).

The missions of Nextome are:
- Bringing Nextome into every smartphone in the world
- Being listed on Euronext within the next three years
- Building a team open to impossible challenges

### Culture

- Growing economy, creating occupation and promoting prosperity by investing in sustainable infrastructure and scientific and technological R&D
- Improving people’s, community and society life conditions contributing to a better education
- Eliminating gender gap
- Ensuring health and wellness
- Adopt climate protection measures

Nextome states that they have seen many young brains emigrate from their area in several years (south of Italy) and they want to write a different story and stop the surge of talents from their area. 

### Structure

![Nextome organizational chart](/organization.png "Organizational chart")

The structure is functional, in fact employees are grouped accordind to similar skills.
The main reasons for this structure is the limited number of employees and the presence of only one product.

#### IT/IS group / office

The IT office is composed by 13 people (most of the company) this because the product sold is a software product.
Roles covered are:
- R&D related to the indoor positioning technology
- Web/mobile development: for the App and web portal implementation and for consulting
- SDK development: for implementing the position computation and the low level functions of the indoor positioning solution
- Infrastructure administration (the backup serves is inside the office, while hosting is outsourced mostly to Azure)

Estimate expenses: 13 (people) * 30000 (medium yearly wage) + 30000 (IT infrastructure) = €420000

Expense in IT / Turn over Ratio: 420000 / 641029 = 0,65
IT expenses represents 65% of the turnover.

### Formalization / specialization/ centralization

The **formalization** is low because the activities are not standard, this is mainly due to the small size where the decision allocation is often at the governance level, this means high **centralization**.
We need to remark that Nextome is a company that is growing, so they are starting to implement formalization also thanks to the ISO 9001 certification.

The **specialization** and the level of specificity of employees is low (small company).

### Organizational type

The organization has a **natural system design** and the organization type is **enterprenurial start up** this is due to the small size and the low level of specialization and formalization.

## Process dimension

### Conceptual data model

UML class diagram for data conceptual model (common to all processes / all organization)

![Data model](/data.png "Data model")

### Processes

| Process name | Description (text) | Input | Output | Organizational units involved |
| --- | --- | --- | --- | --- |
|Software design|The design manager analyze the requirements and perform different actions related to localization, cloud & infrastructure and development. Eventually it creates a paper project plan with a project description|Functional and non-functional requirements|Project plan and description|UI/UX design, Design manager (from Governance), Customer|
|Software development|The development manager receives a project plan with a project description and manage the developers on developing the solution requested from the customer. The development is split in different milestones, at the end of each one there is a validation from the customer|Project plan and description|Project up and running on prod|Beacon installation company, Customer, Development manager (from Governance), Developers, Designer|
|Software maintenance|The customer request a maintenance that can be a new functionality or the resolution of a bug. Sales & Marketing receive the request, IT do the maintenance, Accounting & Finance issues the invoice (if is a new functionality). If the maintenance is relative to a mulfunction the invoice is not issued.|Customer request of maintenance|Maintenance completed|Sales & Marketing, Accounting & Finance, IT|
|Offer management|Sales & Marketing receives a request for an offer, the requirements are sent to the IT that analyze them and compute the time and material needed, the Accounting & Finance evaluate and estimate the price and produce the offer. The offer is sent to the customer.|Request for an offer| Offer sent to the customer|  Sales & Marketing, Accounting & Finance, IT
|Invoice issue|There is the necessity to issue a new invoice in the case of a new implementation (implementation cost), or every year (license cost). |Necessity to issue a new invoice|Invoice paid| Accounting & Finance
|Employee training| When the governance needs to train a group of employees on a certain topic they need to find a training activity and a training institution. Then they choose the emplyees to be involved and the course is delivered. |Necessity of training in a specific field|Training completed|Governance (since IT doesn't exist), employees involed in the training|
|Procurement of materials|The employee compile a material request module specyfing the product to buy, the quantity and the reason to buy a certain item. The employee sends the module to the governance via email. The governance buy the item and gives it to the employee. |An employee need new material| The employee receive the material requested.|Governance, requesting employee

(must be consistent with key processes box in BMC)

For processes that will be changed in the transition to To Be, report BPMN model

Software design process:
![Software design](/design.png "Software design")

Software development process
![Software development](/development.png "Software development")


## Technology dimension

### Application portfolio

List IT applications or services used

| Application name | Vendor (or internal if made internally) | Main functions |
| --- | --- | --- |
|Google services|Google|Drive, Email, Meet|
|Trello|Atlassian|Task management
|Slack|Slack|Instant messaging|
|Microsoft Azure|Microsoft|Cloud solutions and hosting|
|Visual Studio Code|Microsoft|Development|
|Github|Github|Version Control System|
|Hubspot|Hubspot|ERP,CRM
|Excel|Microsoft|Accounting
|Fattura elettronica, il servizio delle Camere di Commercio| InfoCamere SCpA| Invoicing
 

### Hardware software architecture

UML deployment diagram, showing computational nodes, and allocation of applications + data clusters to nodes

(data clusters == group of classes, from the data model, UML class diagram)

(applications are the ones identified in application portfolio)

UML Deployment diagram
![Deployment diagram](/deployment.png "Deployment diagram")

#### Outsourcing

Highlight which IT service is outsourced (if any)

The outsourced IT services are:
- File and email management (Google)
- Cloud and hosting (Azure)
- ERP, CRM (Hubspot)
- Accounting and Invoicing softwares

### IT strategy

Summarize the current IT strategy, discuss if it is consistent with the company strategy

Nextome's IT strategy consists in investing in the development of an indoor positioning software that can be implemented in the most diverse environments (museums, train stations, hospitals, etc.).
I think that the IT strategy is aligned really well with the company strategy that is based on making the most out of the (relatively low) fixed cost (economy of scale). This is also consistent with the functional (and not divisional) organization structure.

It must be said that this strategy is possible as the number of requests from customers is always greater than the number of manageable projects, therefore the demand is always greater than the possible "supply".
# Indicators

## CSF

| CSF ID | Type (domain, distinguishing, environment, contingency) | Textual description, link to strategy | Related Metric(s) | Current value (if available) |
| --- | --- | --- | --- | --- |
| CSF1 |Business|Manage as many projects as possible at the same time|Number of projects in the same time and for each project: lead time, punctuality, customer satisfaction||
 

## KPI

### Process "Software design"

(Process name must be consistent with Process dimension)

KPI table for process "Software design"
(1 year timespan)

| KPI name | KPI type (general, service..) | description | Unit of measure | CSF covered (if any) | Current value (if available) |
| --- | --- | --- | --- | --- | --- |
|#started|General|Number of design processes started||CSF1||
|#completed|General|Number of design processes completed||CSF1||
|#iterations|General|Number of iteration of design processes, the customer doesn't accept some parts of the project plan||CSF1||
|LT_manager|Service|Lead time for project plan creation|Days|CSF1
|LT_validation|Service|Lead time for the customer validation|Days|CSF1
|LT_total|Service|Total lead time for the design|Days|CSF1
|UC_project|Efficiency|Design cost per project  (Design manager RAL + IT costs (releated to design) + cost of the designer)/#completed|€|CSF1


### Process "Software development"

KPI table for process "Software development"
(1 year timespan)

| KPI name | KPI type (general, service..) | description | Unit of measure | CSF covered (if any) | Current value (if available) |
| --- | --- | --- | --- | --- | --- |
|#started|General|Number of development processes started||CSF1||
|#completed|General|Number of development processes completed||CSF1||
|LT_manager|Service|Lead time for the development management|Days|CSF1
|LT_developer|Service|Lead time for the actual development|Days|CSF1
|LT_validation|Service|Lead time for the customer validation|Days|CSF1
|LT_total|Service|Total lead time for the development|Days|CSF1
|UC_development|Efficiency|Development cost per project  (Development manager RAL + Developers RAL + IT costs (related to development) + cost of the designer)/#completed|€|CSF1
|Punctuality|Service|LT_total - estimated_LT_total|Days|CSF1

An indicator that is not a KPI is customer satisfaction (CS).

# Summary analysis

Critical points in the organization and their possible relation with IS.
IT alignment problems.

There aren't particular critical points, the organization is still flexibile because of his size, so it is normal to have little or absent standardization and formalization.
Maybe to work toward the CSF is needed a transition from file management for managing the projects (project files in different folders, all organized in google drive) to an application that organize the projects and lets the (design and development) managers guide the projects in a more effective and efficient way.

