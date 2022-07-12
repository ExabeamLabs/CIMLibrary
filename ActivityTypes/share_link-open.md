share_link-open
===============

Description
-----------
A shared link that was sent to a user was opened

The possible fields for this activity type will vary depending on whether the activity was a [success](#share_link-opensuccess) or a [fail](#share_link-openfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | share_link      |
| Activity      | open            |
| Activity Type | share_link-open |
| Pretty Name   | Share_link Open |
| Legacy Name   |                 |

share_link-open:success
-----------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| domain |      |           | &#10003;      |
| user   |      |           | &#10003;      |

share_link-open:fail
--------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| domain |      |           | &#10003;      |
| user   |      |           | &#10003;      |