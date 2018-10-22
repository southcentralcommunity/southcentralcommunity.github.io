
Thanks for your interest in helping out the community by adding groups/events to our index.

## Events
Events are typically longer than 4 hours and happen on an irregular schedule.

To Add an event create a Markdown File with a URL friendly name for the event. It should start with the date of the event in year, month, day format and an underscore (i.e. `20181020_EventName.md`).

In the file you create you will enter the details for your event, it should look like this. 

```
---
state: TX
region: DFW
title: Serverless Open Hack
event_url: https://www.microsoftevents.com/profile/form/index.cfm?PKformID=0x4714091abcd
start_date: 2018-10-23
end_date: 2018-10-25
cost: Free
topics: [ azure, webdev, dotnet ]
---
```

Keep in Mind
 - state, region and topics values must match an exsiting item
 - dates must be in year month date format (i.e. `2018-10-25`)
 - If the event is a single day, you do not need to include the end_date field

## Groups
Groups are typically monthly meetings for an hour or two.

To Add a group create a Markdown File with a URL friendly name for the group (i.e. `GroupName.md`).

In the file you create you will enter the details for your group, it should look like this. 

```
---
state: TX
region: Austin
title: Austin Azure Meetup
group_url: https://www.meetup.com/azureaustin/
topics: [ azure, webdev ]
---
```

Keep in Mind
 - state, region and topics values must match an exsiting item

## Topics
Topics allow the community to see groups/events accross a specific topic.

To Add a topic create a Markdown File with a URL friendly name for the topic (i.e. `mytopic.md`).

In the file you create you will enter the details for your topic, it should look like this. 

```
---
layout: topic
slug: azure
title: Azure
---
```

Keep in Mind
 - the slug should match the file name with out the file extension

## Regions
If you have to add one of these please open a GitHub Issue

## States
We should not need to add any of these.
