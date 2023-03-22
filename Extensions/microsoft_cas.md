microsoft cas
=============

Expression
----------

product = "microsoft cas"

Fields
------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| src_ip          |      |           | &#10003;      |
| additional_info |      |           | &#10003;      |
| domain          |      |           | &#10003;      |
| user            |      |           | &#10003;      |
| user_agent      |      |           | &#10003;      |

Activity Types
--------------

| Activity Type             | Field     | Status  | Core | Detection | Informational |
| ------------------------- | --------- | ------- | ---- | --------- | ------------- |
| alert-trigger             | operation |         |      |           |               |
| app-activity              | access    | Default |      |           | &#10003;      |
|                           | dest_ip   | Default |      | &#10003;  |               |
|                           | object    | Default |      |           | &#10003;      |
| email-create              | operation | Default |      |           | &#10003;      |
| email-delete              | operation | Default |      |           | &#10003;      |
| email-modify              | operation | Default |      |           | &#10003;      |
| email-move                | operation | Default |      |           | &#10003;      |
| email-send                | operation | Default |      |           | &#10003;      |
| file-delete               | operation |         |      |           |               |
| file-move                 | operation | Default |      |           | &#10003;      |
| file-read                 | operation |         |      |           |               |
| file-rename               | operation | Default |      |           | &#10003;      |
| file-write                | operation |         |      |           |               |
| group-member-add          | operation |         |      |           |               |
| group-member-remove       | operation |         |      |           |               |
| group-modify              | operation |         |      |           |               |
| mailbox-item-create       | operation | Default |      |           | &#10003;      |
| mailbox-item-delete       | operation | Default |      |           | &#10003;      |
| mailbox-item-modify       | operation | Default |      |           | &#10003;      |
| mailbox-item-move         | operation | Default |      |           | &#10003;      |
| mailbox-permission-modify | operation | Default |      |           | &#10003;      |
| user-create               | operation |         |      |           |               |
| user-modify               | operation |         |      |           |               |
| user-role-assign          | operation | Default |      |           | &#10003;      |

