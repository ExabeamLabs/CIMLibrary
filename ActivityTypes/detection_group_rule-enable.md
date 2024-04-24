detection_group_rule-enable
===========================

Description
-----------
Detection group rule was enabled

Parameters
----------
| Parameter     | Value                       |
| ------------- | --------------------------- |
| Subject       | detection_group_rule        |
| Activity      | enable                      |
| Activity Type | detection_group_rule-enable |
| Pretty Name   | Detection group rule enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#detection_group_rule-enablesuccess) or a [fail](#detection_group_rule-enablefail).


detection_group_rule-enable:success
-----------------------------------

There are no fields for this activity type.


detection_group_rule-enable:fail
--------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |