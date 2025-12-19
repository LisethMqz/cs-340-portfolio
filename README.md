# cs-340-portfolio
Portfolio repository for CS 340 featuring a MongoDB backed dashboard application and supporting CRUD module.

My name is Liseth Marquez Torres, and this project is for CS-340 Client/Server Development. For this project, I created a web application dashboard for Grazioso Salvare, an animal rescue organization. The dashboard connects to a MongoDB database and allows users to view and filter animal shelter data.
The dashboard lets users see animal records in a table, filter the data based on rescue type, view animal locations on a map, and see breed information displayed in a chart. The purpose of the dashboard is to help Grazioso Salvare quickly identify animals that may be suitable for different rescue operations.
The zipped submission includes all the files needed to run the dashboard. This includes ProjectTwoDashboard.ipynb, which contains the Python code for the dashboard, and CRUD_Python_Module.py, which contains the CRUD module used to connect to MongoDB. This README file is also included along with screenshots showing the dashboard working.
To run the dashboard, open the Codio environment and make sure the CRUD Python module is in the same folder as the dashboard notebook. Open ProjectTwoDashboard.ipynb and run all the cells. The dashboard will display directly in the notebook.
The CRUD module uses an AnimalShelter class to create, read, update, and delete records in the MongoDB database. The dashboard imports this class and uses it to retrieve data and apply filters.
The dashboard includes radio button filters for Reset (All), Water Rescue, Mountain/Wilderness Rescue, and Disaster Rescue / Individual Tracking. When a filter is selected, the data table updates along with the map and chart.
Screenshots are included to show the dashboard loading correctly, a filter being applied, and the map and chart displaying data. These screenshots demonstrate that the dashboard works as required.
This project shows how a client/server application can be built using Python, MongoDB, and Dash. All required files, code, and screenshots are included in the submission.
