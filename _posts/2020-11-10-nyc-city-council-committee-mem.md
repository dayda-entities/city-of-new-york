---
title: NYC City Council Committee Membership
created: '2020-11-10T17:01:47.382577'
modified: '2020-12-04T19:23:21.528437'
state: active
type: dataset
tags:
  - City Council
  - Committees
  - Council Member
  - Laws
  - Legislation
groups:
  - Local Government
csv_url: 'https://data.cityofnewyork.us/api/views/aabe-yfm9/rows.csv?accessType=DOWNLOAD'
json_url: >-
  https://data.cityofnewyork.us/api/views/aabe-yfm9/rows.json?accessType=DOWNLOAD
layout: post

---
The Council has numerous standing committees that practice oversight of New York City functions, including human services, infrastructure, and government affairs. Each committee is headed by a Council Member (the Chair), includes at least five members, and meets at least once a month. In addition, the Council has several subcommittees, which are convened to review and make recommendations regarding topics of particular interest.

After proposed legislation is heard by its appropriate Committee, it may be voted on and approved at that Committee. If the legislation is passed by Committee, is then sent to be considered by the whole Council. Council Members are assigned to committees through a process that the entire Council votes on.

The NYC City Council Committee Membership dataset is drawn from the City Council's legislative API and updated weekly. Committee membership by City Council Members changes infrequently. This dataset includes committee membership starting Jan 1, 2018. 

Committee Descriptions: https://council.nyc.gov/committees/ 

Github: https://github.com/NewYorkCityCouncil/districts/tree/master/district_data/committees 

More info and API Key for Legislative API: https://council.nyc.gov/legislation/api/ 

Legislative API endpoints utilized for Committee Membership: 

1)http://webapi.legistar.com/Help/Api/GET-v1-Client-Bodies 
https://webapi.legistar.com/v1/nyc/bodies/?token={}&$filter=(BodyTypeName+eq+'Committee'+or+BodyTypeName+eq+'Subcommittee'+or+BodyTypeName+eq+'Land Use')+and+BodyActiveFlag+eq+1 

2)http://webapi.legistar.com/Help/Api/GET-v1-Client-Bodies-BodyId-OfficeRecords 
https://webapi.legistar.com/v1/nyc/bodies/{}/officerecords/?token={}&$filter=OfficeRecordStartDate+ge+datetime'{}'+and+OfficeRecordEndDate+eq+datetime'{}
