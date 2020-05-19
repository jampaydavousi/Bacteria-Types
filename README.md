# Bacteria-Types
This full stack web applciation provides and interactive visualization of bacteria types found among samples.  For each sample (person) that is selected, the table on the left dispalys the anonymous demographics information for the sample, and the pie chart on the right displays the top 10 bacteria OTU_ID found in that sample.  And the bubble chart at the buttom displays all the bacterias found in the sample- the size of the bubbles provides the relative amount of bacterias in each sample.  By hovering over each graphical object such as slice of a pie or bubble, the attributes are displayed.  One can sobserve the diversity of bacterias present among people, by watching how the pie chart and bubbles chart cahnge as different samples are selected. 

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
1. Python version 2.7 or higher.   You must create a separate environment on your computer for running Python applications.
2. Jupyter notebook*.  Always switch to your Python environment before starting jupyter by typing 'jupyter notebook' on the command line.
3. Flask
4. PostgreSQL or SQLite

*This is a full stack app so add your html, js, css, python.  

## Run the application.

1. Copy all the files in this repository into a local directory on your computer.
2. Switch to the Python Environment
3. Form the PC command line or MacOS Terminal type ls, to make sure you see the app.py file in that directory.
4. Enter on the command line 'python -m http.server 5000'
5. Start another command line (terminal on MacOS) window, and repeat steps 2 and 3.
6. Enter on the command line 'python app.py'
7. Start your local browser and enter 'localhost:5000' in the URL field
8. Follow the options described in the intorduction, to observe the presence and density of bacteria types per sample.



