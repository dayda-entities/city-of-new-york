---
title: DOB NOW Build Elevator Device Details
created: '2020-11-10T17:03:47.537444'
modified: '2020-12-04T19:25:53.807174'
state: active
type: dataset
tags:
  - Buildings
  - Code
  - Dob
  - Elevator
  - Elv1
  - Escalator
  - Filing
  - Job
  - Permit
  - Work
groups:
  - Local Government
csv_url: 'https://data.cityofnewyork.us/api/views/juyv-2jek/rows.csv?accessType=DOWNLOAD'
json_url: >-
  https://data.cityofnewyork.us/api/views/juyv-2jek/rows.json?accessType=DOWNLOAD
layout: post

---
This collection contains elevator applications, aka job filings, submitted online through the "DOB NOW: BUILD" portal. An approved application allows the applicant to pull a permit and begin work on an elevator project.
</p>
DOB NOW: BUILD is an online portal that allows users to file for permit applications, check the status of an application, make payments, schedule appointments, and print permits. 

Data in this collection is limited to elevator applications (also known as ELV1) submitted through DOB NOW, and includes Initial (New), Subsequent, and Post Approval Amendment (PAA) filing types. The collection includes all electrical applications submitted to the Department of Buildings since December 11, 2017, when the applications were launched in DOB NOW and were no longer accepted through other submission processes.

This dataset contains details for each device on the application. There should be one row per device/Job Filing Number in this dataset. For example, an Initial Permit Application for Device 1234 and Device 5678 would have 2 rows (one for 1234 and one for 5678). If a Post Approval Amendment (PAA) was submitted for this application, then the Device rows would be repeated but the Job Filing Number would have a P1 suffix to indicate the PAA.
