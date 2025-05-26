# Calvary Scholarship Board Requirements Management Plan (RMP)

## Document Information

| **Field**                 | **Value**                                   |
|---------------------------|---------------------------------------------|
| Target Release            | Version 1.1                                 |
| Epic                      | Calvary Scholarship Board Homepage          |
| Document Status           | DRAFT                                       |
| Project Sponsor           | Sean Audley                                 |
| Document Owner            | Tomi Olaniyan                                |
| UI/UX Designer            | Mark Sheringhan                             |
| Developer                 | Anthony Doyle                               |
| QA                        | Sarp Hewt                                    |
| Project Manager           | Harry Northfield                            |

---

## Background

Calvary Mission, established in 1973, is a religious institution focused on strengthening community bonds and assisting the less fortunate. Initially founded as an interdenominational church in the Bronx, the organization has expanded its activities to include various empowerment programs and community projects. Recognizing the critical role education plays in reducing crime rates, unemployment, and substance abuse, Calvary Mission allocates a significant portion of its budget to educational funding. In 2010, the organization established the Calvary Scholarship Board to provide scholarships and educational opportunities to deserving individuals within the community.

By prioritizing education and community development, Calvary Mission strives to make a positive and lasting impact on individuals and the community at large.

---

## Business Problem

The current process of awarding grants and scholarships involves manual paper forms and a cumbersome approval process, leading to delays, document loss, bias, and a lack of transparency. Recognizing the need for a more efficient and transparent system, the Calvary Scholarship Board is seeking the assistance of Speed Technology Systems to develop a web portal that automates the application and awarding process. This portal will streamline the process, ensuring faster approval times, improved document management, and increased transparency. The portal will have the following features:

- Homepage  
- Application Page  
- About Us Page  
- Application Tracker  
- Contact/Support Page  

---

## Requirements Owner

- Tomiwa Olaniyan

---

## Goals

- Build the Calvary Scholarship Board Homepage.

---

## Assumptions

- Personas will be able to:
  - Visit the portal’s homepage
  - Apply for scholarships
  - Track applications
  - View approved applications
  - Access support services

---

## Areas of System Affected

| **Area of System Affected** | **Y/N** | **Comments** |
|-----------------------------|---------|--------------|
| Homepage                    | Y       |              |
| Application Page            | N       |              |
| Tracking Page               | N       |              |
| Support Page                | N       |              |

---

## Actors and Personas

| **Actor**     | **Persona** | **Comments** |
|---------------|-------------|--------------|
| Applicant     | Raymond Jenkins, a freshman college graduate whose ambition is to be a legal practitioner. He completed Calvary Mission’s empowerment program for low-income individuals, making him eligible for the scholarship/grant. Raymond hopes to use the portal for applying, accessing terms and conditions, tracking his application, and logging issues. |  |
| Administrator | Rev. Richard Jakes, the administrator and coordinator of Calvary’s scholarship board. Responsible for ensuring transparency, timely processing, and issue resolution. He hopes to use the automated portal to monitor applications, track progress, and ensure prompt notifications and support. |  |

---

## Use Case Diagrams

*(To be developed)*

---

## Workflow / Process Flows

### AS-IS

*(To be developed)*

### TO-BE

*(To be developed)*

---

## Non-Functional Requirements

| **Category**     | **Non-Functional Requirement**                              |
|-------------------|-----------------------------------------------------------|
| Performance       | The system shall have a response time of 0.1 seconds.      |
| System Requirement| The feature will run on SQL Server database and Microsoft .NET. |
| Scalability       | The registration page shall support 500 users per hour.    |
| Availability      | The webpage must be available to users 98% of the time each month. |
| Reliability       | The system must have 85% reliability for a month.          |
| Maintainability   | The system must have 75% maintainability for 24 hours.     |
| Security          | The system shall encrypt personal information.             |

---

## Functional Requirements

| **Requirement ID** | **User Story**                             | **Requirements**                                                                                                                                         |
|---------------------|-------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1                   | As an applicant, I want to be able to access the Board’s Scholarship portal so that I can navigate to apply for a scholarship or grant. | - When I input `https://www.calgaryscholarshipboard.com` on my browser’s address bar, the system shall direct me to the homepage. <br> - The homepage shall display tabs with selectable links to all portal functionalities: Home, Register, Apply, Track, Contact Us, Follow Us. <br> - The Home menu shall remain fixed throughout the portal and redirect users to the homepage at any time it is selected. <br> - When the Register link is selected, the system shall redirect to the applicant registration form. <br> - When the Apply link is selected, the system shall redirect to the scholarship and grant application form. <br> - The Track link shall redirect to the application tracker page displaying the status of applications. <br> - When the Contact Us link is selected, the system shall redirect to the Board’s contact details (email, phone, office address). <br> - The system shall display selectable icons of the respective social media pages when the Follow Us button is selected. <br> - The homepage shall have a background picture slideshow displaying achievements and activities of the scholarship board. <br> - Copyright information and year shall be displayed at the base of the homepage in smaller fonts. |

---

## Mockups

*(To be developed)*

---



[View RMP](https://github.com/tomiolaniyan/Artifacts/blob/main/Calvary%20Scholarhip%20Board%20RMP%20Template.docx)
