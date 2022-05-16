# How to Create Linkedin Certificates for Completed Certifications

## Arguments
| Information      | Description                                                                                 | Value (Defualt)              |
|------------------|---------------------------------------------------------------------------------------------|------------------------------|
| Name             | Name of the Certification                                                                   | Test Certificate             |
| organizationId   | Your organization ID (if your organization has an existing page on LinkedIn)                | 86063538                     |
| organizationName | Your organization name (Use organizationID as we already have a LinkedIn Page, ID 86063538) |                              |
| issueYear        | Year the certification exam was completed.                                                  | 2022                         |
| issueMonth       | Month the certification exam was completed.                                                 | 1                            |
| expirationYear   | The year the certification exam will expire (Leave Blank)                                   |                              |
| expirationMonth  | The month the certification exam will expire (Leave Blank)                                  |                              |
| certId           | The ID of the Certificate (Email Neil Shah, Dr. Gabo, or Noah)                              | 1234                         |
| certUrl          | The URL of the Certificate (Email Neil Shah, Dr. Gabo, or Noah)                             | https://pycert.org/exam/name |

## Default URL
```
https://www.linkedin.com/profile/add?startTask=CERTIFICATION_NAME&name=Test%20Certificate&organizationId=86063538&issueYear=2022&
issueMonth=1&certUrl=https://pycert.org/exam/name&certId=1234
```
## Create Button (HTML)
```
<div>
  <a href=https://www.linkedin.com/profile/add?startTask=CERTIFICATION_NAME&name=Test%20Certificate&organizationId=86063538&issueYear=2022&
  issueMonth=1&certUrl=https://pycert.org/exam/name&certId=1234">
  <img src="https://download.linkedin.com/desktop/add2profile/buttons/en_US.png " alt="LinkedIn Add to Profile button">
  </a>
</div>
```
