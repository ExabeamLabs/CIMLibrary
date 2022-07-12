message-send
============

```JSON
{"pretty_name":"Message Send",
"activity":"send",
"subject":"message",
"activity_type":"message-send",
"description":"A chat message was sent to a user",
"fields":{"dest_domain":{"core":"0",
"detection":"0",
"informational":"1"},
"dest_user":{"core":"0",
"detection":"0",
"informational":"1"}},
"outcome":"success"}{"pretty_name":"Message Send",
"activity":"send",
"subject":"message",
"activity_type":"message-send",
"description":"A chat message was sent to a user",
"fields":{"failure_code":{"core":"0",
"detection":"1",
"informational":"0"},
"dest_domain":{"core":"0",
"detection":"0",
"informational":"1"},
"dest_user":{"core":"0",
"detection":"0",
"informational":"1"},
"failure_reason":{"core":"0",
"detection":"1",
"informational":"0"}},
"outcome":"fail"}
```