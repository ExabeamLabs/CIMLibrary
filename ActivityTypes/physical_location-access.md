physical_location-access
========================

```JSON
{"pretty_name":"Physical_location Access",
"activity":"access",
"subject":"physical_location",
"activity_type":"physical_location-access",
"legacy_event_name":["physical-access"],
"description":"A user opened a door,
 gate,
 or any other entrance using their badge",
"fields":{"user":{"core":"1",
"detection":"1",
"informational":"0"}},
"outcome":"success"}{"pretty_name":"Physical_location Access",
"activity":"access",
"subject":"physical_location",
"activity_type":"physical_location-access",
"legacy_event_name":["failed-physical-access"],
"description":"A user opened a door,
 gate,
 or any other entrance using their badge",
"fields":{"failure_code":{"core":"0",
"detection":"1",
"informational":"0"},
"failure_reason":{"core":"0",
"detection":"1",
"informational":"0"},
"user":{"core":"1",
"detection":"1",
"informational":"0"}},
"outcome":"fail"}
```