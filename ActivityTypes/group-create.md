group-create
============

Description
-----------
A group was created

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | group        |
| Activity      | create       |
| Activity Type | group-create |
| Pretty Name   | Group Create |

Legacy Names
------------
| Success | Fail   |
| ------- | ------ |
| NA<br>  | NA<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-createsuccess) or a [fail](#group-createfail).


group-create:success
--------------------

There are no fields for this activity type.


group-create:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |