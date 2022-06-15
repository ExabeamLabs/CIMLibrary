database-activity
=================

```JSON
{"pretty_name":"Database Activity",
"activity":"activity",
"subject":"database",
"activity_type":"database-activity",
"legacy_event_name":["database-access"],
"description":"A generic activity took place in a database (catch all)",
"fields":{"operation":{"core":"1",
"detection":"1",
"informational":"0"}},
"outcome":"success"}{"pretty_name":"Database Activity",
"activity":"activity",
"subject":"database",
"activity_type":"database-activity",
"legacy_event_name":["database-activity-failed"],
"description":"A generic activity took place in a database (catch all)",
"fields":{"failure_code":{"core":"0",
"detection":"1",
"informational":"0"},
"failure_reason":{"core":"0",
"detection":"1",
"informational":"0"},
"operation":{"core":"1",
"detection":"1",
"informational":"0"}},
"outcome":"fail"}
```