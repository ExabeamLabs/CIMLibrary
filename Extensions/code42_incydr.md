code42 incydr
=============

Expression
----------

product = "code42 incydr"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type             | Field                         | Status  | Core     | Detection | Informational |
| ------------------------- | ----------------------------- | ------- | -------- | --------- | ------------- |
| email-send                | bytes                         | Default |          |           | &#10003;      |
|                           | file_type                     | Default |          |           | &#10003;      |
|                           | event_code                    | Default |          |           | &#10003;      |
|                           | log_source                    | Default |          |           | &#10003;      |
|                           | src_host                      | Default |          | &#10003;  |               |
| file-delete               | access                        | Legacy  |          | &#10003;  |               |
|                           | removable_media_name          |         |          |           |               |
|                           | mime                          |         |          |           |               |
|                           | tab_title                     |         |          |           |               |
|                           | domain_user_name              |         |          |           |               |
|                           | device_type                   |         |          |           |               |
|                           | email_dlp_from                |         |          |           |               |
|                           | private_ip                    |         |          |           |               |
|                           | file_category                 |         |          |           |               |
|                           | src_ip                        |         |          |           |               |
|                           | src_translated_ip             |         |          |           |               |
|                           | shared_with                   |         |          |           |               |
|                           | device_name                   |         |          |           |               |
|                           | process_name                  | Legacy  |          |           | &#10003;      |
|                           | file_type                     | Legacy  |          |           | &#10003;      |
|                           | event_code                    |         |          |           |               |
|                           | hash_md5                      |         |          |           |               |
|                           | time_created                  |         |          |           |               |
|                           | directory_id                  |         |          |           |               |
|                           | detection_source_alias        |         |          |           |               |
|                           | process_owner                 |         |          |           |               |
|                           | device_id                     |         |          |           |               |
|                           | service_name                  |         |          |           |               |
|                           | exposure_type                 |         |          |           |               |
|                           | file_owner                    |         |          |           |               |
|                           | src_host                      | Legacy  |          | &#10003;  |               |
|                           | url                           |         |          |           |               |
|                           | tab_url                       |         |          |           |               |
|                           | hash_sha256                   |         |          |           |               |
|                           | removable_media_partition_id  |         |          |           |               |
|                           | time_modified                 |         |          |           |               |
|                           | additional_info               |         |          |           |               |
|                           | sender                        |         |          |           |               |
|                           | bytes                         |         |          |           |               |
|                           | removable_media_vendor        |         |          |           |               |
|                           | domain                        |         |          |           |               |
|                           | log_source                    |         |          |           |               |
|                           | file_id                       |         |          |           |               |
|                           | removable_media_serial_number |         |          |           |               |
|                           | dest_host                     | Legacy  |          | &#10003;  |               |
|                           | removable_media_media_name    |         |          |           |               |
|                           | device_vendor                 |         |          |           |               |
|                           | user                          | Legacy  | &#10003; | &#10003;  |               |
|                           | cloud_drive_id                |         |          |           |               |
|                           | user_uid                      |         |          |           |               |
| file-download             | access                        |         |          |           |               |
|                           | removable_media_name          |         |          |           |               |
|                           | mime                          |         |          |           |               |
|                           | tab_title                     |         |          |           |               |
|                           | domain_user_name              |         |          |           |               |
|                           | device_type                   |         |          |           |               |
|                           | email_dlp_from                |         |          |           |               |
|                           | private_ip                    |         |          |           |               |
|                           | file_category                 |         |          |           |               |
|                           | src_ip                        |         |          |           |               |
|                           | src_translated_ip             |         |          |           |               |
|                           | shared_with                   |         |          |           |               |
|                           | device_name                   |         |          |           |               |
|                           | process_name                  | Legacy  |          |           | &#10003;      |
|                           | file_type                     | Legacy  |          |           | &#10003;      |
|                           | event_code                    |         |          |           |               |
|                           | hash_md5                      |         |          |           |               |
|                           | time_created                  |         |          |           |               |
|                           | directory_id                  |         |          |           |               |
|                           | detection_source_alias        |         |          |           |               |
|                           | process_owner                 |         |          |           |               |
|                           | device_id                     |         |          |           |               |
|                           | service_name                  |         |          |           |               |
|                           | exposure_type                 |         |          |           |               |
|                           | file_owner                    |         |          |           |               |
|                           | src_host                      | Legacy  |          |           | &#10003;      |
|                           | url                           |         |          |           |               |
|                           | tab_url                       |         |          |           |               |
|                           | hash_sha256                   |         |          |           |               |
|                           | removable_media_partition_id  |         |          |           |               |
|                           | time_modified                 |         |          |           |               |
|                           | additional_info               |         |          |           |               |
|                           | sender                        |         |          |           |               |
|                           | bytes                         | Legacy  |          |           |               |
|                           | removable_media_vendor        |         |          |           |               |
|                           | domain                        |         |          |           |               |
|                           | log_source                    |         |          |           |               |
|                           | file_id                       |         |          |           |               |
|                           | removable_media_serial_number |         |          |           |               |
|                           | dest_host                     | Legacy  |          |           | &#10003;      |
|                           | removable_media_media_name    |         |          |           |               |
|                           | device_vendor                 |         |          |           |               |
|                           | user                          | Legacy  | &#10003; | &#10003;  |               |
|                           | cloud_drive_id                |         |          |           |               |
|                           | user_uid                      |         |          |           |               |
| file-read                 | access                        | Legacy  |          | &#10003;  |               |
|                           | removable_media_name          |         |          |           |               |
|                           | mime                          |         |          |           |               |
|                           | tab_title                     |         |          |           |               |
|                           | domain_user_name              |         |          |           |               |
|                           | device_type                   | Legacy  |          |           | &#10003;      |
|                           | email_dlp_from                |         |          |           |               |
|                           | private_ip                    |         |          |           |               |
|                           | file_category                 |         |          |           |               |
|                           | src_ip                        |         |          |           |               |
|                           | src_translated_ip             |         |          |           |               |
|                           | shared_with                   |         |          |           |               |
|                           | device_name                   |         |          |           |               |
|                           | process_name                  | Legacy  |          |           | &#10003;      |
|                           | file_type                     | Legacy  |          |           | &#10003;      |
|                           | event_code                    |         |          |           |               |
|                           | hash_md5                      |         |          |           |               |
|                           | time_created                  |         |          |           |               |
|                           | directory_id                  |         |          |           |               |
|                           | detection_source_alias        |         |          |           |               |
|                           | process_owner                 |         |          |           |               |
|                           | device_id                     | Legacy  |          | &#10003;  |               |
|                           | service_name                  |         |          |           |               |
|                           | exposure_type                 |         |          |           |               |
|                           | file_owner                    |         |          |           |               |
|                           | src_host                      | Legacy  |          | &#10003;  |               |
|                           | url                           |         |          |           |               |
|                           | tab_url                       |         |          |           |               |
|                           | hash_sha256                   |         |          |           |               |
|                           | removable_media_partition_id  |         |          |           |               |
|                           | time_modified                 |         |          |           |               |
|                           | additional_info               |         |          |           |               |
|                           | sender                        |         |          |           |               |
|                           | bytes                         | Legacy  |          |           |               |
|                           | removable_media_vendor        |         |          |           |               |
|                           | domain                        |         |          |           |               |
|                           | log_source                    |         |          |           |               |
|                           | file_id                       |         |          |           |               |
|                           | removable_media_serial_number |         |          |           |               |
|                           | dest_host                     | Legacy  |          | &#10003;  |               |
|                           | removable_media_media_name    |         |          |           |               |
|                           | device_vendor                 |         |          |           |               |
|                           | user                          | Legacy  | &#10003; | &#10003;  |               |
|                           | cloud_drive_id                |         |          |           |               |
|                           | user_uid                      |         |          |           |               |
| file-upload               | access                        |         |          |           |               |
|                           | removable_media_name          |         |          |           |               |
|                           | mime                          |         |          |           |               |
|                           | tab_title                     |         |          |           |               |
|                           | domain_user_name              |         |          |           |               |
|                           | device_type                   |         |          |           |               |
|                           | email_dlp_from                |         |          |           |               |
|                           | private_ip                    |         |          |           |               |
|                           | file_category                 |         |          |           |               |
|                           | src_ip                        |         |          |           |               |
|                           | src_translated_ip             |         |          |           |               |
|                           | shared_with                   |         |          |           |               |
|                           | device_name                   |         |          |           |               |
|                           | process_name                  | Legacy  |          |           | &#10003;      |
|                           | file_type                     | Legacy  |          |           | &#10003;      |
|                           | event_code                    |         |          |           |               |
|                           | hash_md5                      |         |          |           |               |
|                           | time_created                  |         |          |           |               |
|                           | directory_id                  |         |          |           |               |
|                           | detection_source_alias        |         |          |           |               |
|                           | process_owner                 |         |          |           |               |
|                           | device_id                     |         |          |           |               |
|                           | service_name                  |         |          |           |               |
|                           | exposure_type                 |         |          |           |               |
|                           | file_owner                    |         |          |           |               |
|                           | src_host                      | Legacy  |          |           | &#10003;      |
|                           | url                           |         |          |           |               |
|                           | tab_url                       |         |          |           |               |
|                           | hash_sha256                   |         |          |           |               |
|                           | removable_media_partition_id  |         |          |           |               |
|                           | time_modified                 |         |          |           |               |
|                           | additional_info               |         |          |           |               |
|                           | sender                        |         |          |           |               |
|                           | bytes                         |         |          |           |               |
|                           | removable_media_vendor        |         |          |           |               |
|                           | domain                        |         |          |           |               |
|                           | log_source                    |         |          |           |               |
|                           | file_id                       |         |          |           |               |
|                           | removable_media_serial_number |         |          |           |               |
|                           | dest_host                     | Legacy  |          |           | &#10003;      |
|                           | removable_media_media_name    |         |          |           |               |
|                           | device_vendor                 |         |          |           |               |
|                           | user                          | Legacy  | &#10003; | &#10003;  |               |
|                           | cloud_drive_id                |         |          |           |               |
|                           | user_uid                      |         |          |           |               |
| file-write                | access                        | Legacy  |          | &#10003;  |               |
|                           | removable_media_name          |         |          |           |               |
|                           | mime                          |         |          |           |               |
|                           | tab_title                     |         |          |           |               |
|                           | domain_user_name              |         |          |           |               |
|                           | device_type                   | Legacy  |          |           | &#10003;      |
|                           | email_dlp_from                |         |          |           |               |
|                           | private_ip                    |         |          |           |               |
|                           | file_category                 |         |          |           |               |
|                           | src_ip                        |         |          |           |               |
|                           | src_translated_ip             |         |          |           |               |
|                           | shared_with                   |         |          |           |               |
|                           | device_name                   |         |          |           |               |
|                           | process_name                  | Legacy  |          |           | &#10003;      |
|                           | file_type                     | Legacy  |          |           | &#10003;      |
|                           | event_code                    |         |          |           |               |
|                           | hash_md5                      |         |          |           |               |
|                           | time_created                  |         |          |           |               |
|                           | directory_id                  |         |          |           |               |
|                           | detection_source_alias        |         |          |           |               |
|                           | process_owner                 |         |          |           |               |
|                           | device_id                     | Legacy  |          | &#10003;  |               |
|                           | service_name                  |         |          |           |               |
|                           | exposure_type                 |         |          |           |               |
|                           | file_owner                    |         |          |           |               |
|                           | src_host                      |         |          |           |               |
|                           | url                           |         |          |           |               |
|                           | tab_url                       |         |          |           |               |
|                           | hash_sha256                   |         |          |           |               |
|                           | removable_media_partition_id  |         |          |           |               |
|                           | time_modified                 |         |          |           |               |
|                           | additional_info               |         |          |           |               |
|                           | sender                        |         |          |           |               |
|                           | bytes                         | Legacy  |          |           |               |
|                           | removable_media_vendor        |         |          |           |               |
|                           | domain                        |         |          |           |               |
|                           | log_source                    |         |          |           |               |
|                           | file_id                       |         |          |           |               |
|                           | removable_media_serial_number |         |          |           |               |
|                           | dest_host                     | Legacy  |          | &#10003;  |               |
|                           | removable_media_media_name    |         |          |           |               |
|                           | device_vendor                 |         |          |           |               |
|                           | user                          | Legacy  | &#10003; | &#10003;  |               |
|                           | cloud_drive_id                |         |          |           |               |
|                           | user_uid                      |         |          |           |               |
| peripheral_storage-insert | device_product                |         |          |           | &#10003;      |
|                           | drive_letter                  |         |          |           |               |
|                           | device_description            |         |          |           | &#10003;      |
|                           | vendor_name                   |         |          |           |               |
|                           | usb_serial_number             |         |          |           |               |
|                           | src_translated_ip             |         |          |           |               |
|                           | src_ip                        |         |          |           |               |
|                           | device_name                   |         |          |           |               |
|                           | usb_vendor                    |         |          |           |               |
|                           | user_id                       |         |          |           |               |
|                           | device_pid                    |         |          |           | &#10003;      |
|                           | device_class                  |         |          |           | &#10003;      |
|                           | device_vendor                 |         |          |           | &#10003;      |
|                           | device_vid                    |         |          |           | &#10003;      |
|                           | operation                     |         |          |           |               |
| printer-activity          | src_ip                        |         |          |           |               |
|                           | device_id                     |         |          |           |               |
|                           | user_id                       |         |          |           |               |
|                           | event_code                    |         |          |           |               |
|                           | dest_ip                       |         |          |           |               |
|                           | log_source                    |         |          |           |               |
|                           | local_user_name               |         |          |           |               |
|                           | printer_name                  | Legacy  | &#10003; | &#10003;  |               |
|                           | src_host                      | Legacy  |          |           | &#10003;      |
|                           | user                          | Legacy  | &#10003; | &#10003;  |               |
|                           | object                        |         |          |           |               |

