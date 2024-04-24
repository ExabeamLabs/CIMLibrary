github
======

Expression
----------

product = "github"

Fields
------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| domain           |      |           | &#10003;      |
| domain_user_name |      |           |               |
| user             |      |           | &#10003;      |

Activity Types
--------------

| Activity Type             | Field           | Status  | Core     | Detection | Informational |
| ------------------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-activity              | resource        | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| app-login                 | src_ip          | Default |          | &#10003;  |               |
|                           | user_agent      | Default |          |           | &#10003;      |
| branch-create             | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| branch-modify             | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| branch-protection-disable | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| branch-protection-enable  | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| branch-protection-modify  | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| configuration-mfa-enable  | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| group-delete              | resource        |         |          |           |               |
|                           | additional_info |         |          |           |               |
|                           | user            | Legacy  | &#10003; |           |               |
|                           | operation       |         |          |           |               |
|                           | object          |         |          |           |               |
| group-member-add          | resource        |         |          |           |               |
|                           | additional_info |         |          |           |               |
|                           | user            | Legacy  | &#10003; | &#10003;  |               |
|                           | operation       |         |          |           |               |
|                           | object          |         |          |           |               |
| group-member-remove       | resource        |         |          |           |               |
|                           | additional_info |         |          |           |               |
|                           | user            | Legacy  | &#10003; | &#10003;  |               |
|                           | operation       |         |          |           |               |
|                           | object          |         |          |           |               |
| group-modify              | resource        |         |          |           |               |
|                           | additional_info |         |          |           |               |
|                           | user            | Legacy  | &#10003; |           |               |
|                           | operation       |         |          |           |               |
|                           | object          |         |          |           |               |
| group-repository-add      | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| group-repository-remove   | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| hook-create               | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| hook-modify               | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| log-download              | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| repository-create         | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| repository-delete         | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| repository-member-add     | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| repository-member-remove  | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| repository-modify         | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| repository-move           | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| repository-pull           | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| repository-push           | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| repository-read           | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| user-create               | resource        |         |          |           |               |
|                           | additional_info |         |          |           |               |
|                           | user            | Legacy  | &#10003; | &#10003;  |               |
|                           | operation       |         |          |           |               |
|                           | object          |         |          |           |               |
| user-delete               | resource        |         |          |           |               |
|                           | additional_info |         |          |           |               |
|                           | user            | Legacy  | &#10003; | &#10003;  |               |
|                           | operation       |         |          |           |               |
|                           | object          |         |          |           |               |
| user-invite               | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| user-invite-cancel        | resource        | Default |          |           | &#10003;      |
|                           | additional_info | Default |          |           | &#10003;      |
|                           | user            | Default |          | &#10003;  |               |
|                           | operation       | Default |          |           | &#10003;      |
|                           | object          | Default |          |           | &#10003;      |
| user-modify               | resource        |         |          |           |               |
|                           | additional_info |         |          |           |               |
|                           | user            | Legacy  | &#10003; |           |               |
|                           | operation       |         |          |           |               |
|                           | object          |         |          |           |               |

