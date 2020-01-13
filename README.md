# BankMaster
This is Customer Statement Processor for bank

1. Create war file of the project and deploy onto Tomcat7 server.
git clone https://github.com/rajsingh0802/BankMaster/blob/master/Bank-master.zip
2. http://localhost:8081/BankCSP/rabobank/processStatment
Run maven command to install dependency.
3. Compile and run the project using tomcat 7.

4. Upload input csv/xml file in the service using postman client.
The input file will be validated based on two conduction mentioned in the problem statment.(validation condition mentioned in expected output section)
Duplicate Transaction key check,
End balance calculation check. (endbalance = startbalance – mutation)

Finally invalid records will be getting as webservice response with status code.
