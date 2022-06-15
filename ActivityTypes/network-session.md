network-session
===============

```JSON
{"pretty_name":"Network Session",
"activity":"session",
"subject":"network",
"activity_type":"network-session",
"legacy_event_name":["netflow-connection",
"network-connection-successful",
"process-network"],
"description":"A representation of an entire network session",
"fields":{},
"outcome":"success"}{"pretty_name":"Network Session",
"activity":"session",
"subject":"network",
"activity_type":"network-session",
"legacy_event_name":["netflow-connection",
"network-connection-failed",
"process-network-failed"],
"description":"A representation of an entire network session",
"fields":{"failure_code":{"core":"0",
"detection":"1",
"informational":"0"},
"failure_reason":{"core":"0",
"detection":"1",
"informational":"0"}},
"outcome":"fail"}
```