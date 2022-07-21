netwrix auditor
===============

Expression
----------

product = "netwrix auditor"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type       | Field           | Status  | Core     | Detection | Informational |
| ------------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-activity        | event_id        | Default |          |           | &#10003;      |
|                     | application     | Default |          |           | &#10003;      |
|                     | resource        | Default |          |           | &#10003;      |
|                     | object_type     | Default |          |           | &#10003;      |
|                     | additional_info | Default |          |           | &#10003;      |
|                     | event_code      | Default |          |           | &#10003;      |
|                     | domain          | Default |          |           | &#10003;      |
|                     | dest_host       | Default |          | &#10003;  |               |
|                     | src_host        | Default |          | &#10003;  |               |
|                     | user            | Default |          | &#10003;  |               |
|                     | monitoring_plan | Default |          |           | &#10003;      |
|                     | object          | Default |          |           | &#10003;      |
| app-login           | additional_info | Default |          |           | &#10003;      |
|                     | src_host        | Default |          | &#10003;  |               |
| database-activity   | src_ip          | Default |          | &#10003;  |               |
|                     | db_name         | Default |          |           | &#10003;      |
|                     | additional_info | Default |          |           | &#10003;      |
|                     | service_name    | Default |          |           | &#10003;      |
|                     | domain          | Default |          |           | &#10003;      |
|                     | dest_host       | Default |          | &#10003;  |               |
|                     | user            | Default |          | &#10003;  |               |
| database-login      | src_ip          | Default |          | &#10003;  |               |
|                     | db_name         | Default |          |           | &#10003;      |
|                     | additional_info | Default |          |           | &#10003;      |
|                     | service_name    | Default |          |           | &#10003;      |
|                     | dest_host       | Default |          | &#10003;  |               |
| ds_object-activity  | additional_info | Default |          |           | &#10003;      |
|                     | domain          | Default |          |           | &#10003;      |
|                     | src_host        | Default |          | &#10003;  |               |
|                     | user            | Default |          | &#10003;  |               |
| ds_object-create    | event_id        | Default |          |           | &#10003;      |
|                     | resource        | Default |          |           | &#10003;      |
|                     | additional_info | Default |          |           | &#10003;      |
|                     | event_code      | Default |          |           | &#10003;      |
|                     | domain          | Default |          |           | &#10003;      |
|                     | dest_host       | Default |          | &#10003;  |               |
|                     | user            | Default |          | &#10003;  |               |
|                     | operation       | Default |          |           | &#10003;      |
|                     | monitoring_plan | Default |          |           | &#10003;      |
|                     | object          | Default |          |           | &#10003;      |
| ds_object-delete    | event_id        | Default |          |           | &#10003;      |
|                     | resource        | Default |          |           | &#10003;      |
|                     | additional_info | Default |          |           | &#10003;      |
|                     | event_code      | Default |          |           | &#10003;      |
|                     | domain          | Default |          |           | &#10003;      |
|                     | dest_host       | Default |          | &#10003;  |               |
|                     | user            | Default |          | &#10003;  |               |
|                     | operation       | Default |          |           | &#10003;      |
|                     | monitoring_plan | Default |          |           | &#10003;      |
|                     | object          | Default |          |           | &#10003;      |
| ds_object-modify    | event_id        | Default |          |           | &#10003;      |
|                     | resource        | Default |          |           | &#10003;      |
|                     | additional_info | Default |          |           | &#10003;      |
|                     | event_code      | Default |          |           | &#10003;      |
|                     | domain          | Default |          |           | &#10003;      |
|                     | dest_host       | Default |          | &#10003;  |               |
|                     | user            | Default |          | &#10003;  |               |
|                     | operation       | Default |          |           | &#10003;      |
|                     | monitoring_plan | Default |          |           | &#10003;      |
|                     | object          | Default |          |           | &#10003;      |
| file-delete         | src_ip          |         |          |           |               |
|                     | access          | Legacy  |          | &#10003;  |               |
|                     | event_id        |         |          |           |               |
|                     | file_type       | Legacy  |          |           | &#10003;      |
|                     | event_code      |         |          |           |               |
|                     | domain          |         |          |           |               |
|                     | src_host        | Legacy  |          | &#10003;  |               |
|                     | user            | Legacy  | &#10003; | &#10003;  |               |
| file-write          | src_ip          |         |          |           |               |
|                     | access          | Legacy  |          | &#10003;  |               |
|                     | event_id        |         |          |           |               |
|                     | file_type       | Legacy  |          |           | &#10003;      |
|                     | event_code      |         |          |           |               |
|                     | domain          |         |          |           |               |
|                     | src_host        |         |          |           |               |
|                     | user            | Legacy  | &#10003; | &#10003;  |               |
| group-member-add    | additional_info |         |          |           |               |
|                     | domain          | Legacy  |          |           | &#10003;      |
|                     | src_host        | Legacy  |          | &#10003;  |               |
|                     | user            | Legacy  | &#10003; | &#10003;  |               |
| group-member-remove | additional_info |         |          |           |               |
|                     | domain          | Legacy  |          |           | &#10003;      |
|                     | src_host        | Legacy  |          | &#10003;  |               |
|                     | user            | Legacy  | &#10003; | &#10003;  |               |
| role-create         | event_id        | Default |          |           | &#10003;      |
|                     | resource        | Default |          |           | &#10003;      |
|                     | additional_info | Default |          |           | &#10003;      |
|                     | event_code      | Default |          |           | &#10003;      |
|                     | domain          | Default |          |           | &#10003;      |
|                     | dest_host       | Default |          | &#10003;  |               |
|                     | user            | Default |          | &#10003;  |               |
|                     | operation       | Default |          |           | &#10003;      |
|                     | monitoring_plan | Default |          |           | &#10003;      |
|                     | object          | Default |          |           | &#10003;      |
| user-create         | event_id        |         |          |           |               |
|                     | resource        |         |          |           |               |
|                     | additional_info |         |          |           |               |
|                     | event_code      |         |          |           |               |
|                     | domain          | Legacy  |          |           | &#10003;      |
|                     | dest_host       | Legacy  |          | &#10003;  |               |
|                     | user            | Legacy  | &#10003; | &#10003;  |               |
|                     | operation       |         |          |           |               |
|                     | monitoring_plan |         |          |           |               |
|                     | object          |         |          |           |               |
| user-delete         | event_id        |         |          |           |               |
|                     | resource        |         |          |           |               |
|                     | additional_info |         |          |           |               |
|                     | event_code      |         |          |           |               |
|                     | domain          | Legacy  |          |           | &#10003;      |
|                     | dest_host       | Legacy  |          |           | &#10003;      |
|                     | user            | Legacy  | &#10003; | &#10003;  |               |
|                     | operation       |         |          |           |               |
|                     | monitoring_plan |         |          |           |               |
|                     | object          |         |          |           |               |
| user-disable        | additional_info |         |          |           |               |
|                     | domain          | Legacy  |          |           | &#10003;      |
|                     | src_host        |         |          |           |               |
|                     | user            | Legacy  | &#10003; | &#10003;  |               |
| user-lock           | additional_info |         |          |           |               |
|                     | domain          |         |          |           |               |
|                     | src_host        | Legacy  | &#10003; | &#10003;  |               |
|                     | user            | Legacy  | &#10003; | &#10003;  |               |
| user-modify         | event_id        |         |          |           |               |
|                     | resource        |         |          |           |               |
|                     | additional_info |         |          |           |               |
|                     | event_code      | Legacy  |          |           | &#10003;      |
|                     | domain          | Legacy  |          |           | &#10003;      |
|                     | dest_host       | Legacy  |          |           | &#10003;      |
|                     | user            | Legacy  | &#10003; |           |               |
|                     | operation       |         |          |           |               |
|                     | monitoring_plan |         |          |           |               |
|                     | object          |         |          |           |               |
| user-password-reset | additional_info |         |          |           |               |
|                     | src_host        |         |          |           |               |
| user-unlock         | additional_info |         |          |           |               |
|                     | domain          |         |          |           |               |
|                     | src_host        |         |          |           |               |
|                     | user            | Legacy  | &#10003; | &#10003;  |               |

