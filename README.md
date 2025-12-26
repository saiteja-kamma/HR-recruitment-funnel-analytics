# HR-recruitment-funnel-analytics
HR recruitment funnel analytics dashboard analysing CV flow, screening, interview stages, recruiter performance, and hiring conversion using Excel and Power BI.
HR Recruitment Funnel Analytics Dashboard
Project Overview

This project analyses the end-to-end recruitment funnel, tracking candidate movement from CV sourcing to final hiring.
The dashboard focuses on conversion rates, recruiter performance, sourcing effectiveness, and hiring outcomes to support data-driven hiring decisions.

Tools Used

Microsoft Excel – data preparation and validation

Power BI – data modelling, DAX measures, and interactive dashboards

Data Preparation (Excel)

Generated employee-level HR data (ID, CV date, source ID, position ID, rec ID, screen date, screen status, screen rejected, 1st round date, 1st round status, 2nd round date, 2nd round status, 3rd round date, 3rd round status).

source ID is calculated using the following logic:
=RANDBETWEEN(1,6) from pivot table in Excel sheet 2 

position ID is calculated using the following logic:
=RANDBETWEEN(1,6) from pivot table in Excel sheet 2 

Rec ID is calculated using the following logic:
=RANDBETWEEN(1,6) from pivot table in Excel sheet 2 

screen date is = cv date

screen rejection is calculated using the following logic:
=CHOOSE(RANDBETWEEN(1,6), "Over Qualified", "Less Experience", "Not Interested", "Not In Station", "Communication", "Higher Expectation")

The first round date is calculated using the following logic:
=C7+RANDBETWEEN(2,20)

Recruitment Funnel Coverage

Total CVs received

Screened CVs

First-round and second-round interviews

Hired and pending candidates

Stage-wise conversion percentages

Key Analysis Areas

1. Funnel Performance

Clear drop-off visibility from CV submission to hiring

Helps identify bottlenecks in the screening and interview stages

2. CV Source Effectiveness

CV volume comparison across platforms (Internshala, LinkedIn, Naukri, Indeed, Referral, etc.)

Source performance by job position

3. Recruiter Performance

Total CVs handled per recruiter

Total selected and hired candidates

Hire percentage comparison across recruiters

4. Position-Level Insights

Hiring demand and CV distribution by role

Identification of roles requiring a higher sourcing effort

Key Insights Enabled

Significant variation in hiring conversion across recruiters

Certain CV sources contribute more volume but lower hire rates

Recruiter workload and hiring efficiency are not always aligned

Funnel leakage highlights opportunities to improve screening quality

Business Value

Improves recruiter efficiency tracking

Helps optimise CV sourcing strategy

Enables better capacity planning for hiring teams

Supports data-backed recruitment decisions

Notes

The dataset is simulated for learning and portfolio purposes.

Dashboard structure mirrors real corporate recruitment MIS reports.
