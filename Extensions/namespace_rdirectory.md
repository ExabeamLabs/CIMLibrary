namespace rdirectory
====================

Expression
----------

product = "namespace rdirectory"

Fields
------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| domain             |          | &#10003;  |               |
| fallback_user_name |          |           |               |
| domain_user_name   |          |           |               |
| user               | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type        | Field         | Status | Core | Detection | Informational |
| -------------------- | ------------- | ------ | ---- | --------- | ------------- |
| group-member-add     | dest_user_ou  |        |      |           | &#10003;      |
|                      | dest_user_dn  |        |      |           | &#10003;      |
| user-create          | user_type     | Legacy |      | &#10003;  |               |
| user-delete          |               |        |      |           |               |
| user-disable         |               |        |      |           |               |
| user-enable          |               |        |      |           |               |
| user-modify          | old_attribute |        |      | &#10003;  |               |
|                      | new_attribute |        |      | &#10003;  |               |
| user-password-modify |               |        |      |           |               |

