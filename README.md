# Overview
The target of the application is to enable users to append their .csv format docs/reports.

_**Functional requirements:**_

- running the app on the server e.g. in **AWS** size `t2.micro` following requirements are accomplished:
    - 2 reports with 1000 entry each will be appended in less than 3 s
    - entired flow will take approximately 5 s
- communication encrypted (using `https` protocol)
- free certificate from `Let's Encrypted`
- communication between front-end and back-end will be encrypted as well
- using `REST API` (`JSON` format)



_**Non-functional requirements**_


# Lessons learnt
On the way when I was creating the functionality I was facing following questions:
- Does user should be redirect to page "Forgot my password" or "Log-in page" when its e-mail exists in Database

# Activity diagram UML for requirement "Create a new user profile"


<p align="center">
<img src="https://github.com/szduniak-ba/User-account-workflow/blob/main/Activity%20diagram%20req.A.2.jpg?raw=true" width="450">
</p>
