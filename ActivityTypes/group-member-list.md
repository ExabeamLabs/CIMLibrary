group-member-list
=================

Description
-----------
An enumeration of group members took place

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | group             |
| Activity      | member-list       |
| Activity Type | group-member-list |
| Pretty Name   | Group Member List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-member-listsuccess) or a [fail](#group-member-listfail).


group-member-list:success
-------------------------

There are no fields for this activity type.


group-member-list:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |