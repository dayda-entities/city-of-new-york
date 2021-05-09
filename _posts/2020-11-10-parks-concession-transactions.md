---
title: Parks Concession Transactions
created: '2020-11-10T17:05:47.339988'
modified: '2020-11-20T17:19:15.740219'
state: active
type: dataset
tags:
  - Concessions
  - Parks
  - Transactions
groups:
  - Local Government
csv_url: 'https://data.cityofnewyork.us/api/views/vmkw-p55f/rows.csv?accessType=DOWNLOAD'
json_url: >-
  https://data.cityofnewyork.us/api/views/vmkw-p55f/rows.json?accessType=DOWNLOAD
layout: post

---
NYC Parks uses a Commercial Off-The-Shelf database for maintaining its concession-related data.  In its raw form, the Parks data within the Yardi Voyager database has a convoluted structure, the majority of which is not being used by Parks to store any data. In an effort to make the data more user friendly, the multitude of tables used by the source database have been distilled into two that contain the essential information for a concessions database. One table (Parks Concessions) represents the concession asset – the place and thing which is being operated – and who holds the contract.  The other (Parks Concession Transactions) represents transactions between those contract holders and NYC Parks.  Parks Concessions is here https://data.cityofnewyork.us/City-Government/Parks-Concessions/53m8-jdtg and can be joined to Parks Concession Transactions using  PersonID, PropertyID and UnitID.
