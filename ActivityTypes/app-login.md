app-login
=========

Description
-----------
A user logged in to an application

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | app       |
| Activity      | login     |
| Activity Type | app-login |
| Pretty Name   | App Login |

Legacy Names
------------
| Success                              | Fail                                        |
| ------------------------------------ | ------------------------------------------- |
| app-login<br>webconference-login<br> | failed-app-login<br>webconference-login<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-loginsuccess) or a [fail](#app-loginfail).


app-login:success
-----------------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| os               |          | &#10003;  |               |
| login_type       |          | &#10003;  |               |
| mime             |          | &#10003;  |               |
| domain_user_name |          |           |               |
| src_host         |          | &#10003;  |               |
| dest_zone        |          |           |               |
| src_ip           |          | &#10003;  |               |
| src_zone         |          |           |               |
| browser          |          | &#10003;  |               |
| dest_ip          |          | &#10003;  |               |
| domain           |          | &#10003;  |               |
| fingerprint      |          | &#10003;  |               |
| dest_host        |          | &#10003;  |               |
| user             | &#10003; | &#10003;  |               |
| operation        |          | &#10003;  |               |
| user_agent       |          | &#10003;  |               |
| object           |          | &#10003;  |               |
| cid              |          |           | &#10003;      |

app-login:fail
--------------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| failure_code     |          | &#10003;  |               |
| os               |          | &#10003;  |               |
| login_type       |          | &#10003;  |               |
| mime             |          | &#10003;  |               |
| domain_user_name |          |           |               |
| failure_reason   |          | &#10003;  |               |
| src_host         |          | &#10003;  |               |
| dest_zone        |          |           |               |
| src_ip           |          | &#10003;  |               |
| src_zone         |          |           |               |
| browser          |          | &#10003;  |               |
| dest_ip          |          | &#10003;  |               |
| domain           |          | &#10003;  |               |
| fingerprint      |          | &#10003;  |               |
| dest_host        |          | &#10003;  |               |
| user             | &#10003; | &#10003;  |               |
| operation        |          | &#10003;  |               |
| user_agent       |          | &#10003;  |               |
| object           |          | &#10003;  |               |
| cid              |          |           | &#10003;      |