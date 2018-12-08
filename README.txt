Given a description of an ailment, we created a program that identifies a possible diagnosis. The program takes in information regarding your symptoms and their duration, and checks whether they match a certain disease(s) inside of our database. If it does not exist, you have the option to add the diagnosis into the database so we can help you next time. 

Sample Queries:

type    patient(Diagnosis).    to start

I have had concentration issues for years
Ive had joint pain for years
I have had itchy spots everywhere for over a month
I have had itchy spots everywhere since last week
I have had a fever for over a week

For disease queries not currently in our database, see below:

Query asked: I feel fatigued for years

this will fail, next type in:     new(Diagnosis).    and then type in the following for each prompt:

- Symptom prompt: fatigued
- Duration prompt: years
- Diagnosis prompt: anemia
try running the original query again.


Rithikha Rajamohan & Bashara Hussain
