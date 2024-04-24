detection_group_rule-disable
============================

Description
-----------
Detection group rule was disabled

Parameters
----------
| Parameter     | Value                        |
| ------------- | ---------------------------- |
| Subject       | detection_group_rule         |
| Activity      | disable                      |
| Activity Type | detection_group_rule-disable |
| Pretty Name   | Detection group rule disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#detection_group_rule-disablesuccess) or a [fail](#detection_group_rule-disablefail).


detection_group_rule-disable:success
------------------------------------

There are no fields for this activity type.


detection_group_rule-disable:fail
---------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |