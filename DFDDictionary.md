# DFD Dictionary
##External Entities  
Developer- The person who finds and implements new code, whether it be open software code or code made in house.   
Manager - the person who is in charge of overseeing the developer and the updating the policy documentation. 
##Data Flows
Software Project - collection of packages  
Software Package - collection of files, in the case of the DFD, this holds the requests and the information necessary to scan the open source code that the developer has found, through the NIST Database and the applications that scan for the type of licenses that the software has  
Software Package Results- The findings that the scans through the NIST DB and the License application has uncovered  

##Databases
NIST Vulnerability DB - this is the database that tells the user if the specified open source code has any known vulnerabilities  
SW License and Vulnerability DB - this os the database that holds the results of the vulnerability and license scanning  
Policy DB - this database holds the documentation for company policies  
##Processes  
Manage Software Packager for License and Vulnerability Scanning - this controls how the software package, that the developer sends out, is used. It makes sure that the right information is going to the right place, that the licenses and vulnerabilities are being found and placed into the database.  
Manage Software Project Information and Requests - This controls the requests for licenses and vulnerabilities of the project by the manager and developer from the SW License and Vulnerability DB. It sends back the results of the requests.
Manage Policy Documentation Checks - This process controls the request to compare the project information with the current policy documentation  
