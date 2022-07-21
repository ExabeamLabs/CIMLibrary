rule-delete
===========

Description
-----------
A security rule was deleted on a security product or program

The possible fields for this activity type will vary depending on whether the activity was a [success](#rule-deletesuccess) or a [fail](#rule-deletefail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | rule        |
| Activity      | delete      |
| Activity Type | rule-delete |
| Pretty Name   | Rule Delete |
| Legacy Name   |             |

rule-delete:success
-------------------

There are no fields for this activity type.


rule-delete:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |