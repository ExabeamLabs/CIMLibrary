user-switch
===========

Description
-----------
A user switched into another user account

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | user        |
| Activity      | switch      |
| Activity Type | user-switch |
| Pretty Name   | User Switch |

Legacy Names
------------
| Success            | Fail               |
| ------------------ | ------------------ |
| account-switch<br> | account-switch<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-switchsuccess) or a [fail](#user-switchfail).


user-switch:success
-------------------

| Field                   | Core     | Detection | Informational |
| ----------------------- | -------- | --------- | ------------- |
| dest_user_type          |          | &#10003;  |               |
| source_user_entity_id   |          |           |               |
| user_type               |          | &#10003;  |               |
| source_device_entity_id |          |           |               |
| domain                  |          |           | &#10003;      |
| domain_user_name        |          |           |               |
| src_host                |          | &#10003;  |               |
| user                    | &#10003; | &#10003;  |               |

user-switch:fail
----------------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| dest_user_type   |          | &#10003;  |               |
| failure_code     |          | &#10003;  |               |
| user_type        |          | &#10003;  |               |
| domain           |          |           | &#10003;      |
| domain_user_name |          |           |               |
| failure_reason   |          | &#10003;  |               |
| src_host         |          | &#10003;  |               |
| user             | &#10003; | &#10003;  |               |