user-privilege-use
==================

Description
-----------
A user called his privilege to access to an object

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | user               |
| Activity      | privilege-use      |
| Activity Type | user-privilege-use |
| Pretty Name   | User Privilege Use |

Legacy Names
------------
| Success                                           | Fail |
| ------------------------------------------------- | ---- |
| privileged-access<br>privileged-object-access<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-privilege-usesuccess) or a [fail](#user-privilege-usefail).


user-privilege-use:success
--------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| privileges      |      |           |               |
| process_name    |      | &#10003;  |               |
| src_zone        |      |           |               |
| local_user_name |      |           |               |
| process_dir     |      | &#10003;  |               |
| src_host        |      | &#10003;  |               |
| user            |      | &#10003;  |               |
| dest_zone       |      |           |               |

user-privilege-use:fail
-----------------------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| privileges |      |           |               |
| user       |      | &#10003;  |               |