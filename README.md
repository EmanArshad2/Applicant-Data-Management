Applicant Data Management
This C/C++ program is designed to manage applicant data collected during a recruitment process. It allows users to read data from a file, edit, add, or delete records, and then write the modified data back to the file. Users can search for records based on ID or name, and the displayed information includes age in years and months and weight in kilograms along with units.

Problem Overview
In a recruitment program, two different interns collected applicant data:

One intern collected numerical ID, first name, and ages in months.
The other intern mistakenly collected numerical ID, first name, and weights in kilograms.
There were a total of 1000 applicants, each assigned an ID from 1 to 1000. On the recruitment test day, not everyone showed up, so the age and weight data for only those who showed up was collected, put in a file (data.txt), and sorted by ID.

Data Format
The data.txt file contains records in comma-separated values. Each line represents one record with the following format:
Data Structure
Each record is read into a struct with three elements:

ID: Short integer for applicant ID.
Name: Character array of size 12 for the first name.
AgeOrWeight: Union of two elements:
lval: Long integer to store age in months.
fval: Float to store weight in kilograms.
Usage Instructions
Clone this repository to your local machine.
Compile the source code using a C/C++ compiler.
Run the compiled program.
Follow the on-screen prompts to perform operations such as reading data, editing records, adding new records, deleting records, and searching for records by ID or name.
View the displayed information, including age in years and months and weight in kilograms with units.
