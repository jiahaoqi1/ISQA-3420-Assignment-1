# DFD Dictionary
##External Entities  
Developer- The person who finds and implements new code, whether it be open software code or code made in house.   
Manager - the person who is in charge of overseeing the developer and the updating the policy documentation. 
##Data Flows
Software Project - collection of software packages  
Software Package - collection of files, in the case of the DFD, this holds the requests and the information necessary to scan the open source code that the developer has found, through the NIST Vulnerability DB and the applications that scan for the type of licenses that the software has  
Software Package Results- The findings that the scans through the NIST Vulnerability DB and the license application has uncovered  
SW Project Info -  the request information to pull the license and vulnerability data from the database  
Project Results - this is the information pulled from the database that the SW Project Info is requesting  
Policy Check Info -  this is the project information that is checked against the policy documentation as well as the request to check the information with the database  
Policy Check Results - the findings of the Manager Policy Documentation Checks process  
Poliy Documentation Info - the new or updated policy documentation that the manager is pushing to the Policy DB  

##Databases
NIST Vulnerability DB - this is the database that tells the user if the specified open source code has any known vulnerabilities  
SW License and Vulnerability DB - this os the database that holds the results of the vulnerability and license scanning  
Policy DB - this database holds the documentation for company policies  
##Processes  
Manage Software Package for License and Vulnerability Scanning - this controls how the software package, that the developer sends out, is used. It makes sure that the right information is going to the right place, that the licenses and vulnerabilities are being found and placed into the database.  
Manage Software Project Information and Requests - This controls the requests for licenses and vulnerabilities of the project by the manager and developer from the SW License and Vulnerability DB. It sends back the results of the requests.  
Manage Policy Documentation Checks - This process controls the request and data to compare the project information with the current policy documentation  
Update Policy Documentation - This process allows the manager to push new policy documentation to the Policy DB  
Scan for License - this process scans applications, like Fossology, for the license of the specified open source code  
