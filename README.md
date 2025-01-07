<h1>file update with python algorithmn</h1>


<h2>Project Description</h2>
At my organization, access to restricted content is controlled with an allow list of IP addresses. The "allow_list.txt" file identifies these IP addresses. A separate remove list identifies IP addresses that should no longer have access to this content. I created an algorithm to automate updating the "allow_list.txt" file and remove these IP addresses that should no longer have access. 

<br />




<h2> Utilities Used</h2>
 
- <b>Google Cloud Quick Labs</b>


<h2>Environment Used </h2>

- <b>Windows 10</b> (21H2) 

<h2>Program walk-through:</h2>
- <b>Vulnerability Assessment Report</b>
   
     1st  January, 20XX

- <b>System Description</b> 

The server hardware consists of a powerful CPU processor and 128GB of memory. It runs on the latest version of Linux operating system and hosts a MySQL database management system. It is configured with a stable network connection using IPv4 addresses and interacts with other servers on the network. Security measures include SSL/TLS encrypted connections.

- <b>Scope</b> 

The scope of this vulnerability assessment relates to the current access controls of the system. The assessment will cover a period of three months, from June 20XX to August 20XX. NIST SP 800-30 Rev. 1 is used to guide the risk analysis of the information system.

- <b>Purpose</b>

The database server is a centralized computer system that stores and manages large amounts of data. The server is used to store customer, campaign, and analytic data that can later be analyzed to track performance and personalize marketing efforts. It is critical to secure the system because of its regular use for marketing operations.

- <b>Risk Assessment</b>

<img src="https://imgur.com/SJHK0cI.png" height="80%" width="80%" alt="Threat And Vulnerability Assessments"/>



- <b>Approach</b>

Risks that were measured considered the data storage and management procedures of the business. Potential threat sources and events were determined using the likelihood of a security incident given the open access permissions of the information system. The severity of potential incidents were weighed against the impact on day-to-day operational needs.

- <b>Remediation Strategy</b>

Implementation of authentication, authorization, and auditing mechanisms to ensure that only authorized users access the database server. This includes using strong passwords, role-based access controls, and multi-factor authentication to limit user privileges. Encryption of data in motion using TLS instead of SSL. IP allow-listing to corporate offices to prevent random users from the internet from connecting to the database.

