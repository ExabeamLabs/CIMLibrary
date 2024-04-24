detection_group_rule-create
===========================

Description
-----------
Detection Group Rule Created

Parameters
----------
| Parameter     | Value                       |
| ------------- | --------------------------- |
| Subject       | detection_group_rule        |
| Activity      | create                      |
| Activity Type | detection_group_rule-create |
| Pretty Name   | Detection Group Rule Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#detection_group_rule-createsuccess) or a [fail](#detection_group_rule-createfail).


detection_group_rule-create:success
-----------------------------------

There are no fields for this activity type.


detection_group_rule-create:fail
--------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |