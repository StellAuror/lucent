# Lucent - R app for Supply Chain Analytics
This is a illustrative repository only, presenting selected screenshots from engineering work on the design of an application for the supply chain in an anonymous company.

## ETL
The application includes 3 different options for loading data.
- The first one is a method of loading a 'snapshot' of data, which is created inside the application for archiving and retrospective purposes.
- The second option allows you to load data directly from the SAP server using the OData protocol.
- The last method allows you to process local Excel files using SAP solutions.
![image](https://github.com/StellAuror/lucent/assets/100155329/4bfd912b-1a0b-4850-8235-b1d616b2d012)

If you choose the last option, you must provide at least one file (the audit file is optional). The data will then be loaded and read into the cache after a short period of time.
![image](https://github.com/StellAuror/lucent/assets/100155329/cea92da7-6f94-4c19-8f51-d79010d9ec7b)

Having already loaded the data into the cache, it is now possible to customize the bookmarks - i.e. the user profile. The tab stores information about preferred filters, views and notes. Each user can create any number of such bookmarks, which only he or she has access to.
![image](https://github.com/StellAuror/lucent/assets/100155329/9e80e68a-c753-46fe-b18c-b89de884a623)

## [1st Dashboard] The Change Tracker
The first dashboard, despite the seemingly small number of visualizations, provides many possibilities for analyzing the process. These possibilities are:
- Providing basic information about business objects (number of unique records for individual objects).
- User profile name
- Gantt chart analysis, providing information on the time frame and status of a given facility (delayed/on time, completed/open)
- Distribution of the selected feature (user-defined) according to the selected measure (also user-defined)
- detailed analysis of task durations (using process and audit data) taking into account the relationships between objects
- User's notebook - here the user can enter any note, assigning it to an object or assigning any ID.

| Drill Down | Description |
| :---:        |     :---:      |
| ![image](https://github.com/StellAuror/lucent/assets/100155329/0a44d159-568b-4d41-b058-ef85b1fabd8a) | User can select the feature of which distribution will be displayed. Then the drukk down mechanism allows to narrow the data to selected values of a given feature. |


| Using Drill Through | Description |
| :---:         |     :---:      |
| ![image](https://github.com/StellAuror/lucent/assets/100155329/23f40d28-1113-4ed1-afa8-335fb6f1872c) | User selects the object in the gantt chart which triggers drill through mechanism so the detailed timelines table is rendered |


| Note | Notebook | Description |
| :---:         |     :---:      |         :---:  |
|  ![image](https://github.com/StellAuror/lucent/assets/100155329/5571a98b-3a00-484e-be58-ec8f0cb0d2f7)   |![image](https://github.com/StellAuror/lucent/assets/100155329/a681cf46-998b-40d9-bcd0-2c329d2a4921) | To each object a note can be assigned. User can pass the object ID by selecting it on the gantt chart or by entering it manually.    |

| Detailed Timelines | Description |
| :---:         |     :---:      |
| ![image](https://github.com/StellAuror/lucent/assets/100155329/473350a0-54f7-4ad8-9d45-35fd9cca7e50) | The timelines table can be maximixed so that it is more spacy and clear. Additionally, users can display and info they need. |
