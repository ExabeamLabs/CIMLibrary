endpoint-policy-verify
======================

```JSON
{"pretty_name":"Endpoint Policy Verify",
"activity":"policy-verify",
"subject":"endpoint",
"activity_type":"endpoint-policy-verify",
"legacy_event_name":["nac-logon"],
"description":"An endpoint policy was verified",
"fields":{"src_ip":{"core":"1",
"detection":"0",
"informational":"0"}},
"outcome":"success"}{"pretty_name":"Endpoint Policy Verify",
"activity":"policy-verify",
"subject":"endpoint",
"activity_type":"endpoint-policy-verify",
"legacy_event_name":["nac-failed-logon"],
"description":"An endpoint policy was verified",
"fields":{"src_ip":{"core":"1",
"detection":"0",
"informational":"0"},
"failure_code":{"core":"0",
"detection":"1",
"informational":"0"},
"failure_reason":{"core":"0",
"detection":"1",
"informational":"0"}},
"outcome":"fail"}
```