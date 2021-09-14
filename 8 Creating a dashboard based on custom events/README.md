__Topic:__ Creating a dashboard based on custom events.

__Purpose:__ 
Create a dashboard in which to open:
1. the history of events by card topics (two graphs -
absolute numbers and percentage ratio);
2. share of events by source topics;
3. the number of events depending on the source topics and
card topics

__Stack:__ 
1. Creating a remote machine in Yandex.Cloud service. 
2. PostgreSQL installation, database deployment. 
3. Writing a pipeline script that allows you to collect data for a certain period of time, and configuring it to work offline via crontab. 
4. Uploading data using an sql query. 
5. Creating a dashboard in Tableau Public. 
6. Creating a presentation.

__Conclusion:__ 
The developed dashbrod allows you to analyze the history of events by card topics , determine the share of source topics and the number of events
depending on the source topics and card topics.
At the same time, it is possible to filter data by time, card topics, and age groups of users
The dashboard is publicly available, the link to the dashboard is on the Tableau Public website:
[dashboard](https://public.tableau.com/app/profile/nikolay.z./viz/Book1_16310247944990/sheet4?publish=yes)

__Skills and tools:__ Python, SQLAlchemy, PostgreSQL, dash, Tableau, product metrics, building dashboards

__Project status:__ Completed.
