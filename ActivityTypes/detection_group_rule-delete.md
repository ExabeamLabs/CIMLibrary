detection_group_rule-delete
===========================

Description
-----------
Detection group rule was deleted

Parameters
----------
| Parameter     | Value                       |
| ------------- | --------------------------- |
| Subject       | detection_group_rule        |
| Activity      | delete                      |
| Activity Type | detection_group_rule-delete |
| Pretty Name   | Detection group rule delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#detection_group_rule-deletesuccess) or a [fail](#detection_group_rule-deletefail).


detection_group_rule-delete:success
-----------------------------------

There are no fields for this activity type.


detection_group_rule-delete:fail
--------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |