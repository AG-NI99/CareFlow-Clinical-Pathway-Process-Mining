
# Work for week1 and week2

# CareFlow-Clinical-Pathway-Process-Mining
Clinical Pathway Process Mining project using synthetic healthcare event data, Python, and Google Colab.
## Development Progress


**Today's Progress:** Started the CareFlow Clinical Pathway Process Mining project by understanding the problem statement, project objectives, and how process mining can help identify delays in hospital patient journey.
Work:
- Understood the CareFlow project requirements.
- Identified the healthcare workflow problem.
- Learned why average ER waiting time alone cannot explain the actual causes of delays.
- Planned the process-mining workflow.


**Today's Progress:** Analyzed patient activity sequences and generated patient-flow visualizations to understand different clinical pathways and identify repeated or unusual activity patterns.
  Work:
- Examined patient activity sequences.
- Generated patient-flow visualizations.
- Investigated how patients moved between clinical activities.
- Identified variations in patient pathways.

  
**Today's Progress:** Explored the structure of healthcare event logs and planned how patient activities and timestamps would be organized to represent realistic hospital journeys.
What I learned:
- What an event log is.
- What a case ID represents.
- How timestamps determine activity order.
- What an activity trace means.


**Today's Progress:** Set up the Google Colab environment for CareFlow and prepared the required Python libraries for healthcare event-log processing and process-mining analysis and Created the synthetic healthcare event log for 500 patient visits, including hospital activities and timestamps to simulate patient movement through the clinical pathway.Worked on preparing and cleaning the synthetic healthcare event log, checking patient records, activity sequences, and timestamps before performing process-mining analysis.


**Today's Progress:** Analyzed patient activity sequences and generated patient-flow visualizations to understand different clinical pathways and identify repeated or unusual activity patterns and Worked on calculating key performance indicators and patient-level summaries to measure clinical pathway duration and understand overall workflow performance. Worked on calculating key performance indicators and patient-level summaries to measure clinical pathway duration and understand overall workflow performance.


Work:
- Calculated transitions between activities.
- Reviewed transition frequency.
- Created a transition table and visualizations.

**Today's Progress:** Analyzed transitions between clinical activities, calculated how frequently patients moved between different stages, and reviewed the transition table to understand common and less frequent pathways. Worked on identifying clinical workflow bottlenecks by reviewing transition counts and elapsed times. Compared average, median, and maximum times to understand where delays occur in the patient journey and worked on process conformance analysis by checking patient activity sequences against the expected clinical workflow and reviewing deviations in the process.

### Completed
- Created the synthetic healthcare event log.
- Implemented initial data processing in Google Colab.
- Generated pathway summaries and KPI calculations.
- Analyzed clinical activity transitions.
- Created initial charts and summary tables.

### In Progress
- Organizing project outputs and documentation.
- Preparing an interactive Power BI dashboard.
- Planning the final project report and presentation.

### Next Steps
- Export and verify analysis results.
- Build and test the interactive dashboard.
- Document the methodology, findings, limitations, and future improvements.

**Data note:** This project uses simulated data for educational purposes. Its findings should not be interpreted as evidence of actual hospital performance.


## Project Progress

### Completed
- Generated and processed a synthetic clinical event log.
- Calculated key performance indicators (KPIs).
- Summarized patient cases and pathway durations.
- Analyzed transitions between clinical activities.
- Created bar and pie charts to visualize results.

### Next Steps
- Develop an interactive dashboard using Power BI.
- Prepare the final project report and presentation.

# Week3 and week4

**Today's Progress:** Reviewed the existing Python analysis and organized project results.


**Today's Progress:** Went through the existing Python analysis, reviewed the KPI results and patient pathways, and checked the charts generated for the project.


**Today's Progress:** Imported `CareFlow_Analysis_Results.xlsx` into Power BI, loaded all seven data sheets, created the Executive Overview page, and added three KPI cards for total patient visits, average pathway duration, and repeat triage percentage.
What I learned:
- Power BI Desktop.
- Importing Excel workbooks.
- Working with tables and fields.
- Preparing analytical data for dashboards.


**Today's Progress:** Worked on the CareFlow dashboard in Power BI Desktop using `CareFlow_Analysis_Results.xlsx`, preparing the clinical pathway analysis data for KPI visualization and performance monitoring.


**Today's Progress:** Spent time working on the CareFlow dashboard in Power BI, using the imported Excel results and arranging the KPI data to make the clinical performance information easier to understand.


**Today's Progress:** Continued working on the CareFlow bottleneck analysis in Power BI using `CareFlow_Analysis_Results.xlsx`. Looked at the number of cases and average time taken between activities, focusing on Doctor Consultation → Triage (40 cases), X-Ray → Triage (73 cases), and Doctor Consultation → X-Ray (335 cases) to understand where patients experience delays.


**Today's Progress:** Completed the CareFlow Power BI bottleneck analysis by creating a median vs. maximum elapsed-time chart, adding titles and data labels, sorting transitions by maximum time, and testing the transition slicer. Arranged the three dashboard charts without overlap, saved the report, and captured screenshots of the Executive Overview, Patient Pathways, and Bottleneck Analysis pages. Also started preparing the final report using the seven sheets in `CareFlow_Analysis_Results.xlsx`.


**Today's Progress:** Continued working on the CareFlow project, reviewing the Power BI dashboard and organizing the analysis outputs for the final report and submission.


**Today's Progress:** Added screenshots of all three Power BI dashboard pages—Executive Overview, Patient Pathways, and Bottleneck Analysis—to Slide 10 of the final presentation. Checked the layout and presentation of the dashboard visuals.


**Today's Progress:** Uploaded all final CareFlow project deliverables to the GitHub repository, including the Python notebook, Excel analysis workbook, Power BI dashboard, PowerPoint presentation, and PDF report. Reviewed the README documentation and prepared it for final project status updates.


## Week 3 & Week 4 – Project Progress Overview

During Weeks 3 and 4, I focused on completing the data analysis, developing the Power BI dashboard, and preparing the final CareFlow project submission. I analyzed patient activity transitions, repeated activities, pathway patterns, and waiting-time bottlenecks using Python and PM4Py.

I exported the analysis results into `CareFlow_Analysis_Results.xlsx`, containing seven sheets, and imported them into Power BI. I developed the Executive Overview dashboard with KPI cards showing 500 total patient visits, 38.80% repeat triage, average pathway duration, and conformance percentage. I also reviewed important bottleneck transitions, including X-Ray → Triage (73 cases), Doctor Consultation → Triage (40 cases), and Doctor Consultation → X-Ray (335 cases).

After developing the dashboard, I reviewed the visuals, captured screenshots, and added them to the final PowerPoint presentation. I also prepared the PDF version, updated the GitHub README with the latest project progress, and organized the final project files for submission.

Throughout this work, I gained practical experience in process mining, healthcare workflow analysis, bottleneck identification, Power BI dashboard development, data visualization, and project documentation. I also learned how to convert raw event-log data into meaningful insights that can help identify operational inefficiencies in healthcare processes.

**Overall Outcome:** Completed an end-to-end Clinical Pathway Process Mining project using Python, PM4Py, Excel, and Power BI, followed by final documentation and project submission.
