endpoint-logout
===============

```JSON
{"pretty_name":"Endpoint Logout",
"activity":"logout",
"subject":"endpoint",
"activity_type":"endpoint-logout",
"legacy_event_name":["logout-remote",
"winsession-disconnect"],
"description":"A user logged out of an endpoint",
"fields":{"login_type":{"core":"0",
"detection":"1",
"informational":"0"},
"domain":{"core":"0",
"detection":"0",
"informational":"0"},
"user":{"core":"1",
"detection":"1",
"informational":"0"}},
"outcome":"success"}
```