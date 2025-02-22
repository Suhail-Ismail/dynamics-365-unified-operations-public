---
# required metadata

title: Manage recruiting processes
description: This topic describes a concept that recruiters can use to track the steps in a recruiting process.
author: twheeloc
ms.date: 01/10/2022
ms.topic: article
ms.prod: 
ms.technology: 

# optional metadata

ms.search.form: HRMApplication, HRMRecruitingTable
# ROBOTS: 
audience: Application User
# ms.devlang: 
ms.reviewer: twheeloc
# ms.tgt_pltfrm: 
ms.custom: 7501
ms.assetid: 1ad725bf-20e2-42a1-8068-111f7ddddad9
ms.search.region: Global
# ms.search.industry: 
ms.author: twheeloc
ms.search.validFrom: 2016-02-28
ms.dyn365.ops.version: AX 7.0.0

---

# Manage recruiting processes

> [!IMPORTANT]
> The recruiting functionality in this topic will be referred to as Recruitment projects and focuses on applicants, applications, and recruitment projects. 


This topic describes a concept that recruiters can use to track the steps in a recruiting process, including efforts to advertise open positions and recruit applicants, tracking applicant and application information, interviewing applicants, and selecting one or more candidates to fill the open positions in your organization.

## Overview

Recruitment projects can help you organize the steps you'll complete when filling open positions in a legal entity. An applicant is a person who applies for employment to your enterprise. An application is an applicant's expression of interest in being employed by a company and may be tied to a recruitment project to express interest in a specific opening. A single applicant may have multiple applications within the same legal entity or across multiple companies in your organization.

## Recruitment projects

Recruitment projects allow recruiters to track progress against filling one or more open positions. The recruitment project identifies the department and job for which one or more positions are open. Recruitment projects also track following information for open positions:

- The specific number of open positions
- The hiring manager and an alternative contact for the position
- The date that the requisition was approved
- The application deadline
- The estimated start date

The recruitment project contains the **Job ad** value that is used on the **Employee self service** page to advertise the opening. The opening can be shown to employees only if the recruitment project has a **Job ad** value, the **Display on employee self service** field is set to **Yes**, the **Application deadline** field is set to a future date, and the recruitment project has a **Project status** value of **Started**. The following table lists the possible recruitment project statuses and their description.

| Status    | Indicates that…                                                                         |
|-----------|-----------------------------------------------------------------------------------------|
| Scheduled | Recruiting efforts are being prepared. Recruiting has not yet started for this project. |
| Started   | Applications are now being accepted for the openings in this project.                   |
| Finished  | All openings for this project have been filled.                                         |
| Canceled  | Recruiting has been canceled for this project.                                          |

Recruiters can also record the **Media** used to advertise the opening through external outlets as well as track **Developments** against the project or applications.

## Applicants

An applicant is a person who applies for a job in your enterprise. Applicants are shared among all legal entities in your organization. Therefore, you have a large pool of talent to search in. You can maintain competencies, references, accommodation requests, and personal information for applicants. When you create an applicant record, a person record for that applicant is created in the global address book. You can use the **Applicant** page to update the following global address book information for people who are applicants:

- Address information
- Contact information
- Identification information
- Name details
- Personal information

## Applications

You can record information from employment applications that you receive in the **Application** page. The application is the applicant's expression of interest in a job opening in your organization. To create an application, the applicant must already exist as an applicant or person in your system.

Employment applications submitted by applicants on the web are either solicited applications that were entered in response to a job ad, or are unsolicited applications. Solicited applications are automatically associated with the recruitment project that the job ad was created from. Unsolicited applications are associated with the recruitment project that is specified in the **Recruitment** area of the **Human resources parameters** page.

### Application status

The application status indicates where an application is in the recruitment process. The following table lists the possible application statuses and their description.

| Status    | Indicates that…                                                                           |
|-----------|-------------------------------------------------------------------------------------------|
| Received  | The application was received.                                                             |
| Confirmed | A notice can be sent to the applicant to confirm receipt of their application.            |
| Interview | An interview invitation can be sent to the applicant.                                     |
| Rejection | A rejection letter can be sent to the applicant.                                          |
| Canceled  | A withdrawal confirmation can be sent to the applicant. This status is assigned manually. |
| Employed  | An employment offer can be sent to the applicant.                                         |

### Correspondence actions

An application's correspondence action determines the document or email template that you use to communicate with the applicant who submitted the application. By associating **application bookmarks** with correspondence actions, you can use values from the **Application**, **Applicant**, **Interview**, and **Recruitment project** pages in your communications with applicants. By creating **application email templates** for the correspondence actions, you can quickly send emails to applicants whose applications have a specific combination of a status and a correspondence action. For example, you can send a confirmation email to all applications that have a **Status** value of **Received** and a **Correspondence action** value of **Received**. After you send the email, you have the option to automatically update the status of the applications.

## Application routing

If an application must be reviewed by several workers, you can use the **Application routing** page to create a worker circulation list in order to manage the process.

## Interviews

**Applicant interviews** can be scheduled from the **Applications** page. Use the **Send meeting information** button to send a calendar file with the interview schedule information to the applicant and interviewer.

## Skill mapping

**Skill mapping** and **Skill mapping profiles** can be used to identify candidates who may be a good fit for an opening.

## Hiring applicants

Use the **Applications** page to hire an applicant. When you hire an applicant, the application record will have a status of **Employed** and the applicant's global address book person record is associated with the new worker record. Modifications to the global address book information for the new worker record are also displayed in the applicant record. This can help reduce data entry if the new worker ever applies for a different job within your enterprise. To hire an existing worker into a new position, click **Change position** in the **Application status** drop down to initiate the transfer process.

[!INCLUDE[footer-include](../../../includes/footer-banner.md)]
