# ME273Grading
Google Apps Scripts code for peer grading of ME273  homework 


The codes described here are for completing the following tasks:
  Step 1. Check who submitted
  Step 2. Generate random grading assignments
  Step 3. Email out grading assignments
  Step 4. Grade all of the Form Responses
  Step 5. Send an email to everyone with their comments attached
  
Firstly, if you are unfamiliar with Google Apps Script, you should consider reading up on some basics
https://developers.google.com/apps-script/overview
The Help tab will also be very helpful


In order to check who submitted a file you will need to go into the script and change the filenames that the code should look for, as well as the duedate for this assignment:
  Example
  filenames = ['main_'+HWID1+'_HW04.cpp', 'output_'+HWID1+'_HW04.txt']
  var duedate = new Date('October 11, 2018 00:00:00 -0600')
