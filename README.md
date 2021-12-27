# HR-dashboard-Power-BI
A basic dashboard around open positions and joined employees in a company using power BI


Installations/pre Requisites:
Power BI Desktop, Microsoft Excel
No need to purchase any power bi license to create this.
This is with an assumption that, you have atleast a basic experience on power BI like understanding what is Power Query(no need of m-code experience), how to refresh, where to refresh, basic DAX commands(nothing high level), how drill down works, how relationships work.

SCOPE:
The idea is to create a visual infographic analysis for (1) open positions (2) Joined candidates
This prvodies more analysis on Joined candidates and less about open positions.

Background work:
For practial purposes, I have choosen Excel as my data input.
You can refer to the  <> file for underlying data.
The power BI file <> provides the information around ETL and the visualization.

Power BI visual page:
Position Board-
The idea is to show a high level metrics with responsive filters on only Open positions and not on the Joined ones. To explain what is the current open positions acrosss location/month/designations/sub services/skills
This can be scaled to user specific metrics suppose like country or multiple organizations. It is completely dependent on the data at hand.

Joined Board-
The idea is to show a high level metrics with responsive filters on only Joined candidates and not on the Open positions. To explain what is the status of the joined candidates acrosss Gender/Previous Organization/Location/month/Job Source/designations/sub services/skills

This can be scaled to user specific metrics suppose like country or multiple organizations. It is completely dependent on the data at hand.

Joined Board 2-
This tab is to provide information on some financial metrics with responsive filters on only Joined candidates. 

Joined Board Ageing-
This tab is to provide information on turn around time metrics with responsive filters on only Joined candidates.

Further, you can understand more in detail in the power BI file.

