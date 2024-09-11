# Interactive F1 Database App

## Instructions to Run:
1) Clone the repository.
2) Run SQL commands through MySQL Workbench.
3) Change image paths in app.py and edit DB configurations accordingly.
4) Install necessary imports.
5) Execution: streamlit run app.py

## About Project:

This project provides a comprehensive SQL-based database for managing and analyzing Formula 1 data including circuits, constructors, drivers, championship points, fastest laps and pole positions. It is designed to track F1 season statistics and can be used for F1-related data analytics, applications or educational purposes.

The F1 database contains the following tables:
1) circuit: Stores details of each F1 circuit (name, location, and length).
2) constructor_list: Contains the constructor (team) names, their base location, and engine.
3) const_champs: Holds constructor championship rankings and points.
4) driver_list: Records driver details such as name, date of birth, nationality, and team.
5) driver_champs: Tracks driver championship positions and points.
6) fastest_lap: Logs the fastest lap times by drivers at different circuits.
7) pole_position: Records pole position data for drivers on specific circuits.

![Screenshot 2024-09-11 161706](https://github.com/user-attachments/assets/2c6b487f-2b79-493e-b34a-be2f15cc1d9b)


## Analysis: 

![Screenshot 2024-09-11 162002](https://github.com/user-attachments/assets/7d7b7cd9-d16a-47b8-8cf3-62272fc5581f)

Structured to support various analysis tasks across different dimensions of Formula 1 racing:

1) Circuits: Analyze track characteristics and race outcomes across various locations.
2) Constructors: Compare team performance over time, including championship points and wins.
3) Drivers: Evaluate driver performance, focusing on rankings, pole positions and fastest laps.
4) Championship Points: Perform ranking and trend analysis of championship standings.


## Suggestions:

Contributions to enhance the database structure or expand its analytical capabilities are welcome. You can contribute by:

1) Adding new tables or metrics.
2) Improving the efficiency of queries.
3) Creating visualizations or reporting tools for better insights.
   
Feel free to submit a pull request or open an issue for any suggestions.
