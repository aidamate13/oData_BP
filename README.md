oData service for BP creation via HTTPS request

Purpose of the Service: Third party application should be able to create Business Partners in SAP 

Service name: ZBP_CREATION_ODATA

Steps to display the oData

T-code: SEGW

Open project: ZBP_CREATION_ODATA

Service Maintnance

Class Implementation

![image](https://github.com/aidamate13/oData_BP/assets/164672120/4477fd87-00bf-4e24-b138-9311651b5a84)


Fetch CSRF Token and pass it in the post request of bp creation 

![image](https://github.com/aidamate13/oData_BP/assets/164672120/da2be7b3-1cf6-4544-a06f-8ed608f512b8)
![image](https://github.com/aidamate13/oData_BP/assets/164672120/19e6863b-525a-4e33-8108-cff7e8d3a9cf)



POST BP request example:

![image](https://github.com/aidamate13/oData_BP/assets/164672120/1cada3c9-36c6-4515-a518-a45981405661)



FETCH Token request example:

![image](https://github.com/aidamate13/oData_BP/assets/164672120/82e876a7-28ca-4627-9eed-3fea9de4fe61)



GET BP request example:

![image](https://github.com/aidamate13/oData_BP/assets/164672120/b7fe15f3-b44a-46ed-bec9-046a2585eaba)
