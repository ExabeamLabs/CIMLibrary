app-activity
============

```JSON
{"pretty_name":"App Activity",
"activity":"activity",
"subject":"app",
"activity_type":"app-activity",
"legacy_event_name":["app-activity",
"webconference-operations-activity"],
"description":"An activity in an application",
"fields":{"operation":{"core":"0",
"detection":"0",
"informational":"0"}},
"outcome":"success"}{"pretty_name":"App Activity",
"activity":"activity",
"subject":"app",
"activity_type":"app-activity",
"legacy_event_name":["app-activity-failed",
"webconference-operations-activity"],
"description":"An activity in an application",
"fields":{"failure_code":{"core":"0",
"detection":"1",
"informational":"0"},
"failure_reason":{"core":"0",
"detection":"1",
"informational":"0"},
"operation":{"core":"0",
"detection":"0",
"informational":"0"}},
"outcome":"fail"}
```