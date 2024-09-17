mcafee endpoint security
========================

Expression
----------

product = "mcafee endpoint security"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type             | Field              | Status | Core     | Detection | Informational |
| ------------------------- | ------------------ | ------ | -------- | --------- | ------------- |
| alert-trigger             | result             |        |          |           |               |
|                           | process_name       | Legacy |          | &#10003;  |               |
|                           | dest_ip            | Legacy | &#10003; | &#10003;  |               |
|                           | domain             |        |          |           |               |
|                           | dest_host          | Legacy |          | &#10003;  |               |
|                           | process_dir        |        |          |           |               |
|                           | domain_user_name   |        |          |           |               |
|                           | process_path       | Legacy |          | &#10003;  |               |
|                           | user               | Legacy |          | &#10003;  |               |
| peripheral_storage-insert | device_product     |        |          |           | &#10003;      |
|                           | device_pid         |        |          |           | &#10003;      |
|                           | domain             |        |          | &#10003;  |               |
|                           | dest_ip            |        |          | &#10003;  |               |
|                           | device_description |        |          |           | &#10003;      |
|                           | device_class       |        |          |           | &#10003;      |
|                           | domain_user_name   |        |          |           |               |
|                           | device_vendor      |        |          |           | &#10003;      |
|                           | device_vid         |        |          |           | &#10003;      |
|                           | user               | Legacy | &#10003; | &#10003;  |               |
| printer-activity          | bytes              | Legacy |          | &#10003;  |               |
|                           | domain             |        |          | &#10003;  |               |
|                           | dest_ip            |        |          | &#10003;  |               |
|                           | domain_user_name   |        |          |           |               |
|                           | printer_name       | Legacy | &#10003; | &#10003;  |               |
|                           | user               | Legacy | &#10003; | &#10003;  |               |

