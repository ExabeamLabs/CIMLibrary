function-modify
===============

Description
-----------
An automation cloud function's code or configuration was modified

The possible fields for this activity type will vary depending on whether the activity was a [success](#function-modifysuccess) or a [fail](#function-modifyfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | function        |
| Activity      | modify          |
| Activity Type | function-modify |
| Pretty Name   | Function Modify |
| Legacy Name   |                 |

function-modify:success
-----------------------

There are no fields for this activity type.


function-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |