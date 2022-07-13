# USAStaffing-Recursive-Process-API
Process API that integrates with USA Staffing Data APIs, recursively retreives any changes made in the last X hrs and transforms the results that can be pesisted into any system such as Salesforce in a customer favorable format 

# Pre-requisites:
- Request an API Key in USA Staffing website
- Once received, populate it against the property key, "staffing.api.key"
- Mention the time period (in hrs) against the key, "time.period.hrs". It is defaulted to 24 hrs.


# How to run:
- Run this as any other mule api
- Invoke the endpoint /staffing/recursive to initiate the process to collect staffing data based (changed in last X hrs)
