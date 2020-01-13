# BankMaster
This is Customer Statement Processor for bank

1. Create war file of the project and deploy onto Tomcat7 server.
2. http://localhost:8081/BankCSP/rabobank/processStatment

Clone the project Rabobank (Spring REST project).
git clone https://github.com/jayagopi1993/Assignment.git
Run maven command to install dependency.
Compile and run the project using tomcat 7.
This Web service application have one active service to process Csv/Xml files. please find service url below, http://localhost:8081/RobobankCSP/rabobank/processStatment
Upload input csv/xml file in the service using postman client.
The input file will be validated based on two conduction mentioned in the problem statment.(validation condition mentioned in expected output section)
Duplicate Transaction key check,
End balance calculation check. (endbalance = startbalance – mutation)
Finally invalid records will be getting as webservice response with status code.
