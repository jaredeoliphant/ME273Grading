# ME273Grading
Google Apps Scripts code for peer grading of ME273  homework 


The codes described here are for completing the following tasks:
  Step 1. Check who submitted: Search the Google Drive for the correct file submissions
  Step 2. Generate random peer grading assignments based on who actually submitted the assignment
  Step 3. Email all of the students with attached files to be graded as well as a Google form link to fill out
  Step 4. Extract all of the Google form responses and assign each student a score based on the average of their peer grades.
  Step 5. Send an email to everyone with their comments attached
  
Firstly, if you are unfamiliar with Google Apps Script, you should consider reading up on some basics
https://developers.google.com/apps-script/overview
The Help tab will also be very helpful


In order to check who submitted a file you will need to go into the script and change the filenames that the code should look for, as well as the duedate for this assignment:
  Example
  filenames = ['main_'+HWID1+'_HW04.cpp', 'output_'+HWID1+'_HW04.txt']
  var duedate = new Date('October 11, 2018 00:00:00 -0600')



The very first thing that is necessary to do is to generate a roster spreadsheet. You will need two versions of this roster, one that is a google sheet spreadsheet and another that can be loaded into MATLAB. (usually as a string array saved into a *.mat file)
To download a roster from Learning Suite you will


All of the student will submit all assignment onto the Google drive. 

