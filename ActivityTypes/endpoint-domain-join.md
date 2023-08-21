endpoint-domain-join
====================

Description
-----------
An endpoint added to a domain

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | endpoint             |
| Activity      | domain-join          |
| Activity Type | endpoint-domain-join |
| Pretty Name   | Endpoint Domain Join |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-domain-joinsuccess) or a [fail](#endpoint-domain-joinfail).


endpoint-domain-join:success
----------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| domain    |      |           | &#10003;      |
| dest_host |      | &#10003;  |               |

endpoint-domain-join:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| domain         |      |           | &#10003;      |
| dest_host      |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |