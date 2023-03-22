securityiq
==========

Expression
----------

product = "securityiq"

Fields
------

| Field | Core | Detection | Informational |
| ----- | ---- | --------- | ------------- |
| user  |      |           | &#10003;      |

Activity Types
--------------

| Activity Type          | Field      | Status | Core | Detection | Informational |
| ---------------------- | ---------- | ------ | ---- | --------- | ------------- |
| file-delete            | domain     |        |      |           |               |
|                        | user_sid   |        |      |           |               |
|                        | event_name |        |      |           |               |
| file-download          |            |        |      |           |               |
| file-permission-modify | account_id |        |      |           |               |
|                        | access     | Legacy |      | &#10003;  |               |
|                        | domain     |        |      |           |               |
|                        | user_sid   |        |      |           |               |
|                        | event_name |        |      |           |               |
|                        | sid_domain |        |      |           |               |
| file-read              | account_id |        |      |           |               |
|                        | access     | Legacy |      | &#10003;  |               |
|                        | domain     |        |      |           |               |
|                        | user_sid   |        |      |           |               |
|                        | event_name |        |      |           |               |
|                        | sid_domain |        |      |           |               |
| file-upload            | domain     |        |      |           |               |
| file-write             | domain     |        |      |           |               |
|                        | user_sid   |        |      |           |               |
|                        | event_name |        |      |           |               |
| group-member-remove    | group_id   | Legacy |      | &#10003;  |               |
|                        | event_name |        |      |           |               |
| user-create            | user_sid   | Legacy |      |           | &#10003;      |
|                        | event_name |        |      |           |               |
| user-delete            | user_sid   | Legacy |      |           | &#10003;      |
|                        | event_name |        |      |           |               |
| user-lock              | user_sid   | Legacy |      |           | &#10003;      |
|                        | dest_host  | Legacy |      |           | &#10003;      |
|                        | event_name |        |      |           |               |
| user-password-reset    | user_sid   | Legacy |      |           | &#10003;      |
|                        | event_name |        |      |           |               |

