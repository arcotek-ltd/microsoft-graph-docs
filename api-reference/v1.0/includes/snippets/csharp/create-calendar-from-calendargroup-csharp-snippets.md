---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

var graphClient = new GraphServiceClient(requestAdapter);

var requestBody = new Calendar
{
	Name = "Marketing calendar",
};
var result = await graphClient.Me.CalendarGroups["{calendarGroup-id}"].Calendars.PostAsync(requestBody);


```