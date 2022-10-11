*The dataset consists of 19,000 job postings that were posted through the Armenian human resource portal CareerCenter. The data was extracted from the Yahoo! mailing group https://groups.yahoo.com/neo/groups/careercenter-am.*

This was the only online human resource portal in the early 2000s.

A job posting usually has some structure, although some fields of the posting are not necessarily filled out by the client (poster). The data was cleaned by removing posts that were not job related or had no structure.

*The data consists of job posts from 2004-2015*

Content:

- jobpost – The original job post
- date – Date it was posted in the group
- Title – Job title
- Company - employer
- AnnouncementCode – Announcement code (some internal code, is usually missing)
- Term – Full-Time, Part-time, etc
- Eligibility -- Eligibility of the candidates
- Audience --- Who can apply?
- StartDate – Start date of work
- Duration - Duration of the employment
- Location – Employment location
- JobDescription – Job Description
- JobRequirment - Job requirements
- RequiredQual -Required Qualification
- Salary - Salary
- ApplicationP – Application Procedure
- OpeningDate – Opening date of the job announcement
- Deadline – Deadline for the job announcement
- Notes - Additional Notes
- AboutC - About the company
- Attach - Attachments
- Year - Year of the announcement (derived from the field date)
- Month - Month of the announcement (derived from the field date)
- IT – TRUE if the job is an IT job. This variable is created by a simple search of IT job titles within column “Title”
