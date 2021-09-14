# User CRUD (MuleSoft and Salesforce Integration)
This project contains a simple implementation of a REST API built on MuleSoft, which communicates with Salesforce. The API has the complete CRUD for a Custom Salesforce Object that represents users.

## Overview 🔍

### Salesforce ☁️

<p align="center">
  <img src="./img/salesforce-logo.png" align="center" width="85px" alt="AFEMG Logo" style="marin-left: auto; margin-right: auto;"/>
</p>

<div style='text-align: justify;'>
Salesforce is a technology that provides customer relationship management (CRM) service and also provides a complementary suite of enterprise applications focused on customer service, marketing automation, analytics, and application development.
</div>

<a href="https://www.salesforce.com/">See more.</a>


### MuleSoft 🔗

<p align="center">
  <img src="./img/MuleSoft_Logo.png" align="center" width="85px" alt="AFEMG Logo" style="marin-left: auto; margin-right: auto;"/>
</p>

<div style='text-align: justify;'>
MuleSoft is a technology that provides integration software for connecting applications, data and devices, designed to integrate software as a service (SaaS), on-premises software, legacy systems and other platforms.
</div>

<a href="https://www.mulesoft.com/">See more.</a>

### Application Architecture 🧰

<p align="center">
  <img src="./img/Application-Architecture.png" align="center" width="400px" alt="AFEMG Logo" style="marin-left: auto; margin-right: auto;"/>
</p>

<div style='text-align: justify;'>
API-led connectivity is a methodical way to connect data to applications through reusable and purposeful APIs. These APIs are developed to play a specific role – unlocking data from systems, composing data into processes, or delivering an experience. The APIs used in an API-led approach to connectivity fall into three categories:
</div>

<br>

- <strong>System APIs:</strong> access the core systems of record.
- <strong>Process APIs:</strong> interact with and shape data within a single system or across systems.
- <strong>Experience APIs:</strong> data can be reconfigured so that it is most easily consumed by its intended audience.

Here we have only the System level, which access Salesforce record data using four HTTP operations: POST (create), GET (list), PATCH (update), DELETE.
