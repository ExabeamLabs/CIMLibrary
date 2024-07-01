group-member-add
================

Description
-----------
A group member was added to a group

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | group            |
| Activity      | member-add       |
| Activity Type | group-member-add |
| Pretty Name   | Group Member Add |

Legacy Names
------------
| Success          | Fail             |
| ---------------- | ---------------- |
| member-added<br> | member-added<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-member-addsuccess) or a [fail](#group-member-addfail).


group-member-add:success
------------------------

| Field                | Core     | Detection | Informational |
| -------------------- | -------- | --------- | ------------- |
| user_ou              |          | &#10003;  |               |
| dest_local_user_name |          |           |               |
| group_id             |          | &#10003;  |               |
| src_zone             |          |           |               |
| local_user_name      |          |           |               |
| member               | &#10003; | &#10003;  |               |
| dest_user            |          | &#10003;  |               |
| src_host             |          | &#10003;  |               |
| user                 |          | &#10003;  |               |
| dest_zone            |          |           |               |

group-member-add:fail
---------------------

| Field                | Core     | Detection | Informational |
| -------------------- | -------- | --------- | ------------- |
| user_ou              |          | &#10003;  |               |
| dest_local_user_name |          |           |               |
| failure_code         |          | &#10003;  |               |
| group_id             |          | &#10003;  |               |
| src_zone             |          |           |               |
| local_user_name      |          |           |               |
| member               | &#10003; | &#10003;  |               |
| dest_user            |          | &#10003;  |               |
| failure_reason       |          | &#10003;  |               |
| src_host             |          | &#10003;  |               |
| user                 |          | &#10003;  |               |
| dest_zone            |          |           |               |