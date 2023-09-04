<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>



<img width="867" alt="Screen Shot 2023-09-04 at 12 47 11 PM" src="https://github.com/spencerdixon2/post-install-config/assets/143224941/fe2a9df0-517b-4b77-bd33-4d410b5f406f">



Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin



<img width="849" alt="Screen Shot 2023-09-04 at 12 53 34 PM" src="https://github.com/spencerdixon2/post-install-config/assets/143224941/90d4dc12-4b62-4a24-ae4a-88ba57d2f193">



Configure Departments
Admin Panel -> Agents -> Departments
System Administrators



<img width="832" alt="Screen Shot 2023-09-04 at 12 57 17 PM" src="https://github.com/spencerdixon2/post-install-config/assets/143224941/2faf6024-faa1-4f8e-a77f-7003dfa2a8a7">



Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support



<img width="843" alt="Screen Shot 2023-09-04 at 1 01 28 PM" src="https://github.com/spencerdixon2/post-install-config/assets/143224941/a60c4811-d2e4-4598-8f30-305c580e2506">



Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 



<img width="841" alt="Screen Shot 2023-09-04 at 1 06 16 PM" src="https://github.com/spencerdixon2/post-install-config/assets/143224941/76c6a9b0-b203-49a7-8c64-07599ac6a27e">
<img width="843" alt="Screen Shot 2023-09-04 at 1 08 58 PM" src="https://github.com/spencerdixon2/post-install-config/assets/143224941/4ed5d1fc-0151-4ccd-9ca5-f811a0cb5550">



Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John



<img width="843" alt="Screen Shot 2023-09-04 at 1 13 47 PM" src="https://github.com/spencerdixon2/post-install-config/assets/143224941/585ec1e2-d845-4849-8f73-54498ff46854">
<img width="844" alt="Screen Shot 2023-09-04 at 1 15 18 PM" src="https://github.com/spencerdixon2/post-install-config/assets/143224941/5dfae607-5a31-4596-9a2c-5962327a301f">



Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken



<img width="838" alt="Screen Shot 2023-09-04 at 1 20 34 PM" src="https://github.com/spencerdixon2/post-install-config/assets/143224941/f6c9212f-b62f-4c11-a75b-7c8839d474ae">



Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
