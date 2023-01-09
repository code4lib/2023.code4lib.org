---
layout: presentation
type: talk
categories: talks
time: 11:35 AM
startTime: 2023-03-15T11:35
length: 15
day: 1
group: 1
spot: 7
location: frist
room: mpr
speakers:
- amelia-sutton
speaker-text: Amelia Sutton
title: "Lowering Technical Barriers in Open Source Systems - A Case Study"
---
The Five Colleges Library Consortium (5C) recently migrated to an open source Library Services Platform (LSP) and with that change came a change in the reporting tools available to us. In our previous system, Aleph, we had access to the Aleph Reporting Center (ARC) that allowed folks without the technical skills to generate sql queries to create and run reports as needed, independently from technical staff. FOLIO doesn’t have much in the way of built-in reporting, and the other options we have for reporting involve making API queries or writing and running SQL queries. With the large volume of regular reports that need to be run across the 5C, and significant understaffing, we needed a simple way to reduce the burden on technical staff in report running. I have created, and will demonstrate in this presentation, a simple python program that allows non-technical users to execute SQL pre-written queries on our LDlite reporting database instance, even allowing queries to include parameters to give more flexibility in reports. I will focus this talk around the importance of minimizing technical barriers for entry when working with open source systems, especially systems still undergoing significant development. 
