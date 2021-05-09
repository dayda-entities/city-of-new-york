---
title: Forestry Tree Points
created: '2020-11-10T17:03:22.602313'
modified: '2020-12-04T19:25:27.344415'
state: active
type: dataset
tags:
  - Forestry
  - Parks
  - Trees
groups:
  - Local Government
csv_url: 'https://data.cityofnewyork.us/api/views/hn5i-inap/rows.csv?accessType=DOWNLOAD'
json_url: >-
  https://data.cityofnewyork.us/api/views/hn5i-inap/rows.json?accessType=DOWNLOAD
layout: post

---
Record of Forestry tree points for NYC Parks & Recreation. 

Tree Points and Planting Spaces form the basis of ForMS 2.0’s data inventory and are the core entities that all Service Requests, Inspections, and Work Orders are associated to.  The system has built-in rules to ensure that every Tree Point has a Planting Space and each Planting Space can have no more than one active Tree Point at a given time.  Locations that have had one tree removed and another tree replanted will appear in ForMS 2.0 as a single Planting Space associated with one retired Tree Point (that has a removal Work Order) and one active Tree Point.

This dataset can be joined to the Forestry Planting Spaces dataset by joining PlantingSpaceGlobalID from Forestry Tree Points to GLOBALID from Forestry Planting Spaces.

User guide: https://docs.google.com/document/d/1PVPWFi-WExkG3rvnagQDoBbqfsGzxCKNmR6n678nUeU/edit?usp=sharing

Data dictionary: https://docs.google.com/spreadsheets/d/1yMfZgcsrvx9M0b3-ZdEQ3WCk2dFxgitCWytTrJSwEAs/edit?usp=sharing
