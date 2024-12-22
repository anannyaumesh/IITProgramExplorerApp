# IIT-NIT Program Explorer

## Description
The IIT-NIT Program Explorer is a user-friendly tool designed to assist IIT/NIT aspirants in selecting or finding the institute best suited for them. This application provides various functionalities such as accessing frequently asked questions (FAQs), exploring institute details, viewing the institute locations on a map, and filtering program options based on different criteria. 

## Features
1. **FAQ Section**: Users can access commonly asked questions regarding program cutoffs, institute competitiveness, NAAC grades, NIRF rankings, campus events, and more.
2. **Institute Details**: Provides detailed information about individual institutes including total enrollment, campus size, NAAC grade, NIRF ranking, and year of establishment.
3. **Map View**: Displays the locations of IITs and NITs on a map, allowing users to visually understand the distribution of these institutes across India.
4. **Filter Options**: Allows users to filter program options based on rounds, institute types, institute names, program names, and categories.

## Installation Instructions
1. **Program Setup**: Using Python Jupyter Notebook through Anaconda, open a new kernel and paste the code.
2. **Library Installation**: Install the required libraries using the following commands: 
    pip install tkinter

    pip install mysql-connector-python

    pip install tkintermapview

3. **Database Setup**: Import the provided CSV files into MySQL using a tool like MySQL Workbench.
4. **Image Setup**: Download all the images referenced in the code and place them in a folder named "pics" and change the address on the code accordingly.
5. **Run the Code**: Open the code in Jupyter Notebook and execute it.


## Usage
1. **Launching the Application**: Run the code in Jupyter Notebook to launch the application.
2. **FAQ Section**: Click on the "FAQ" button to access commonly asked questions and their answers.
3. **Institute Details**: Click on the "Institute Details" button to view detailed information about specific institutes.
4. **Map View**: Click on the "MAP" button to visualize the locations of IITs and NITs on a map.
5. **Filter Options**: Click on the "Find My Options!" button to filter program options based on different criteria such as rounds, institute types, institute names, program names, and categories.
6. We have referenced the database as "iit_nitcutoff", using the same table names and database name is highly recommended.

## Dataset Information
The application utilizes data from three tables:
- **Student_data**: Contains information about students, including exam year, institute type, round number, quota, program details, ranks, and more.
- **Institute_details**: Provides details about institutes, including location, establishment year, campus size, total enrollment, NAAC grade, and NIRF ranking.
- **Events**: Stores information about events organized by institutes, including venue, event name, date, and time.

For further information about the tables, please find the table description pdf in the zip file.
