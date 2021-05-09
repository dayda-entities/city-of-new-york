---
title: Parks Concessions
created: '2020-11-10T17:00:45.104229'
modified: '2020-11-20T17:14:28.370061'
state: active
type: dataset
tags:
  - Concessions
  - Parks
groups:
  - Local Government
csv_url: 'https://data.cityofnewyork.us/api/views/53m8-jdtg/rows.csv?accessType=DOWNLOAD'
json_url: >-
  https://data.cityofnewyork.us/api/views/53m8-jdtg/rows.json?accessType=DOWNLOAD
layout: post

---
NYC Parks uses a Commercial Off-The-Shelf database for maintaining its concession-related data.  In its raw form, the Parks data within the Yardi Voyager database has a convoluted structure, the majority of which is not being used by Parks to store any data. In an effort to make the data more user friendly, the multitude of tables used by the source database have been distilled into two that contain the essential information for a concessions database. One table (Parks Concessions) represents the concession asset – the place and thing which is being operated – and who holds the contract.  The other (Parks Concession Transactions) represents transactions between those contract holders and NYC Parks.  Parks Concession Transactions is here https://data.cityofnewyork.us/City-Government/Parks-Concession-Transactions/vmkw-p55f and can be joined to Parks Concessions using  PersonID, PropertyID and UnitID.
