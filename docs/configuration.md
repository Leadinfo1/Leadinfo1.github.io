#Configuration

Overview of objects and field names that Leadinfo uses to populate data to the Lime integration. The objects and field names are divided by objective and they have to be named exactly as below for the connection to work. There is no configuration or mapping possibility in the current version.

| Objective | Object | Field names | Comment |
| ----------- | ----------- | ----------- | ----------- |
| Build link to existing company dropdown list.| company | Name <br> Visitingcity| |
| Create a company in Lime | company |visitingaddress1 <br> visitingaddress2 <br> visitingzipcode <br> visitingcity <br> country <br> postaladdress1 <br> postaladdress2 <br> postalzipcode <br> postalcity <br> registrationno <br> phone <br> www <br >name <br> coworker <br> buyingstatus --> default prospect | If our data is not empty, then object is company. |

The website visits synchronize one day back from the moment the company is linked to Lime CRM.
The created notes with website visits on the linked companies from Leadinfo are synched each 5 minutes. Leadinfo performs a full sync at 3 am.