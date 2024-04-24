detection_group_rule-modify
===========================

Description
-----------
Detection group rule was modified

Parameters
----------
| Parameter     | Value                       |
| ------------- | --------------------------- |
| Subject       | detection_group_rule        |
| Activity      | modify                      |
| Activity Type | detection_group_rule-modify |
| Pretty Name   | Detection group rule modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#detection_group_rule-modifysuccess) or a [fail](#detection_group_rule-modifyfail).


detection_group_rule-modify:success
-----------------------------------

There are no fields for this activity type.


detection_group_rule-modify:fail
--------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |