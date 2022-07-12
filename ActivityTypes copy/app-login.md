app-login
=========

```JSON
{"pretty_name":"App Login",
"activity":"login",
"subject":"app",
"activity_type":"app-login",
"legacy_event_name":["app-login",
"webconference-login"],
"description":"A user logged in to an application",
"fields":{"user":{"core":"1",
"detection":"0",
"informational":"0"}},
"outcome":"success"}{"pretty_name":"App Login",
"activity":"login",
"subject":"app",
"activity_type":"app-login",
"legacy_event_name":["failed-app-login",
"webconference-login"],
"description":"A user logged in to an application",
"fields":{"failure_code":{"core":"0",
"detection":"1",
"informational":"0"},
"failure_reason":{"core":"0",
"detection":"1",
"informational":"0"},
"user":{"core":"1",
"detection":"0",
"informational":"0"}},
"outcome":"fail"}
```