# Customer Complaint Tracking  

# Objective  -  

Develop a Business Intelligence report to track and manage consumer complaints received by the Compliance Department at Bank of America. This report aids the team in monitoring complaint statuses and visualizing complaint trends, ensuring timely responses and minimizing overdue cases.  

# Key Goals - 

1. Calculate top-level KPIs by flagging complaints as "Open" or "Closed" and creating a PivotTable to count the complaints for each status.  
2. Create a new PivotTable that shows the "Open" and "Closed" complaints by week, then visualize the trend using a stacked column chart.
3. Add formatting and polish to the report by modifying the KPIs, chart, and timeline filter.

# Overview -  

This report provides a comprehensive view of consumer complaints by analyzing their status ("Open" or "Closed") and visualizing weekly trends. The primary goals are to measure key performance indicators (KPIs) related to complaint resolutions, offer insights into weekly complaint volumes, and highlight potential overdue cases. Through enhanced visibility and clear tracking mechanisms, this report aims to support the Compliance team in maintaining responsive service to consumer complaints.  

# Findings -  

1. Total Complaints are 62,516
  
3. Total Open Cases 1,494
  
5. Total Closed Cases 61,022

as below we can see July 2023 has most No. of complaints  

| Closed | Open  | Total |
|:------:|:-----:|:-----:|
|  943   | 1,064 | 2,007 |


 
# Calculations -  
```
1. Status -  
    =IF(O2="In progress","Open","Closed")

2. Week start -
   
   =D2-WEEKDAY(D2,2)+1

3. Year, Month, Day
   
   =YEAR(E2) , =TEXT(E2,"MMM"), =DAY(E2)  
```

# Conclusion -  

The Consumer Complaint Tracking Report provides a robust solution for monitoring and managing consumer complaints within the Compliance Department at Bank of America. By integrating key performance indicators, weekly trend visualizations, and user-friendly filters, the report offers a comprehensive overview of complaint volumes and resolution statuses. This enables the Compliance team to proactively address open complaints, minimize overdue cases, and maintain a responsive approach to consumer concerns. Ultimately, the report supports data-driven decision-making, enhances operational efficiency, and contributes to improved customer satisfaction by ensuring timely handling of complaints.  

# Recommendations -  

**Focus on High-Volume Periods (July 2023)-**  

Since July 2023 recorded the highest number of complaints, it’s important to analyze root causes, such as seasonal trends, new product releases, or policy changes. By identifying these drivers, the Compliance Department can better anticipate similar surges and prepare proactive strategies, such as increased staffing or targeted customer communication.  

**Reduce Open Cases to Under 1,000-**  

With 1,494 open cases, efforts should be made to resolve these complaints promptly to bring the total down to under 1,000. This can be achieved by assigning additional resources to address unresolved cases and prioritizing complaints based on their potential impact and severity.  

**Implement a Weekly Complaint Resolution Target-**  

Establishing a weekly target for closing complaints will help prevent the backlog of open cases. For example, setting a goal to close 100 cases per week could gradually reduce the open case volume while promoting consistency in response times.  

**Enhance Tracking for Real-Time Monitoring-**  

Introducing a real-time dashboard that tracks incoming complaints and resolution status will enable the team to monitor open cases continuously and respond to new complaints more quickly. This would also aid in identifying any new complaint spikes early, allowing for timely adjustments to resource allocation.  

**Conduct Monthly Reviews of Complaints-**  

A monthly review meeting to analyze complaint data and resolution metrics could be useful for continuous improvement. Reviewing common issues, response times, and high-complaint months like July could help in refining complaints handling processes and improving response strategies over time.  

![Consumer_Complaints](https://github.com/user-attachments/assets/ff538890-2a1c-4942-a68e-b77682f86c49)
