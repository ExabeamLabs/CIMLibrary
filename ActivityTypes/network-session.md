network-session
===============

Description
-----------
A representation of an entire network session

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | network         |
| Activity      | session         |
| Activity Type | network-session |
| Pretty Name   | Network Session |

Legacy Names
------------
| Success                                                                    | Fail                                                                          |
| -------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| netflow-connection<br>network-connection-successful<br>process-network<br> | netflow-connection<br>network-connection-failed<br>process-network-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#network-sessionsuccess) or a [fail](#network-sessionfail).


network-session:success
-----------------------

| Field | Core | Detection | Informational |
| ----- | ---- | --------- | ------------- |
| cid   |      |           | &#10003;      |

network-session:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |