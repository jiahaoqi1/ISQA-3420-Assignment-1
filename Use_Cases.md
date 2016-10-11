# Determine Licenses and Vulnerablility information
Primary Actor: Manager  
Goal in Context: The manager is able to tell the licenses and vulnerability of software.  
Stakeholders: Manager: get relevent and easy to understand information, Developer: To see if the software has the proper licenses and are not vulnerable.  
Preconditions: Relevent package data is composed and sent to the process. Proper project info has been provided.  
Main Success Senario: Manager can see the licenses and they are accurate, as well as see the vulnerability information.  
Failed End Conditions: Manager cannot see the information.  
Trigger: Developer pushes a software package check.  
  
# Change policy documentation  
Primary Actor: Manager  
Goal in Context: The manager is able to change and add new policy documentation to the Policy DB.  
Stakeholders: Manager: can make changes as need be, Developer: can see those changes and use the documentation.  
Preconditions: The data is sent to the right place. The right information has been provided.  
Main Sucess Senario: Manager updates the DB sucessfully.  
Failed End Condition: Manger cannot update the Policy Documentation.  
Trigger: Manager pushes the policy documentation data.  

# Scan For License and Vulnerability
Primary Actor: Developer  
Goal in Context: The developer is able to correctly scan the specified pieces of code for their vulnerability and licenses, and place that information into the database.  
Stakeholders: Developer: get the correct information for that piece of code, Manager: gets the correct information when they pull the data from the database. 
Preconditions: Relevant data is composed and sent to the right place. Proper info has been provided.  
Main Success Senario: The developer is sucessfully able to scan the code and retrieve the information from the database.  
Failed End Conditions: The developer is unable to scan the code.  
Trigger: Developer pushes a software package check.  
