---
name: User Story
about: This is about sudent having a hard time submiting the assignment wthout having
  to go to the campus.
title: ''
labels: ''
assignees: ''

---

As a stuudent 
 I need submit my assignment on time(online)
 So that i dont have to go to the campus 
   
 ### Details and Assumptions
The student has a registered account
The system supports PDF and DOCX files
Internet connection is available
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given the student is logged into the system
When the student uploads a valid assignment file and clicks submit
Then the system saves the file and shows a submission confirmation message
 ```
