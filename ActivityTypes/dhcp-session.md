dhcp-session
============

Description
-----------
A summary of a DHCP session

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | dhcp         |
| Activity      | session      |
| Activity Type | dhcp-session |
| Pretty Name   | Dhcp Session |

Legacy Names
------------
| Success            | Fail               |
| ------------------ | ------------------ |
| computer-logon<br> | computer-logon<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dhcp-sessionsuccess) or a [fail](#dhcp-sessionfail).


dhcp-session:success
--------------------

There are no fields for this activity type.


dhcp-session:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |