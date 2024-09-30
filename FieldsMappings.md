Field Mapping by Event
======================

This table maps old event types to their corresponding new-scale activity types. You can do the following with this table:

 - Click an old event type link to open a page that maps all of the old fields to the corresponding new-scale fields that comply with the Common Information Model.
 - Click a new-scale activity type link to open a page that provides parameters and CDI information for the selected activity type.

| Old Event Type| New-Scale Activity Type |
| ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| [account-creation](FieldsMappings/account-creation_fields.md) | [user-create:success](ActivityTypes/user-create.md) |
| [account-deleted](FieldsMappings/account-deleted_fields.md) | [user-delete:fail](ActivityTypes/user-delete.md)|
| [account-disabled](FieldsMappings/account-disabled_fields.md) | [user-disable:success](ActivityTypes/user-disable.md) |
| [account-enabled](FieldsMappings/account-enabled_fields.md) | [user-enable:success](ActivityTypes/user-enable.md) |
| [account-lockout](FieldsMappings/account-lockout_fields.md) | [user-lock:fail](ActivityTypes/user-lock.md)|
| [account-password-change](FieldsMappings/account-password-change_fields.md) | [user-password-modify:success](ActivityTypes/user-password-modify.md) |
| [account-password-change-failed](FieldsMappings/account-password-change-failed_fields.md) | [password-modify:fail](ActivityTypes/password-modify.md)|
| [account-password-reset](FieldsMappings/account-password-reset_fields.md) | [user-password-reset:fail](ActivityTypes/user-password-reset.md)|
| [account-switch](FieldsMappings/account-switch_fields.md) | [user-switch:success](ActivityTypes/user-switch.md) |
| [account-unlocked](FieldsMappings/account-unlocked_fields.md) | [user-unlock:success](ActivityTypes/user-unlock.md) |
| [alert-iot](FieldsMappings/alert-iot_fields.md) | [alert-trigger:success](ActivityTypes/alert-trigger.md) |
| [app-activity](FieldsMappings/app-activity_fields.md) | [app-activity:fail](ActivityTypes/app-activity.md)|
| [app-activity-failed](FieldsMappings/app-activity-failed_fields.md) | [app-activity:fail](ActivityTypes/app-activity.md)|
| [app-login](FieldsMappings/app-login_fields.md) | [app-authentication:success](ActivityTypes/app-authentication.md) |
| [audit-log-clear](FieldsMappings/audit-log-clear_fields.md) | [endpoint-notification:success](ActivityTypes/endpoint-notification.md) |
| [audit-policy-change](FieldsMappings/audit-policy-change_fields.md) | [audit_policy-modify:success](ActivityTypes/audit_policy-modify.md) |
| [authentication-failed](FieldsMappings/authentication-failed_fields.md) | [app-authentication:fail](ActivityTypes/app-authentication.md)|
| [authentication-successful](FieldsMappings/authentication-successful_fields.md) | [app-authentication:success](ActivityTypes/app-authentication.md) |
| [aws-bucket-accessblock](FieldsMappings/aws-bucket-accessblock_fields.md) | [bucket-accessblock-modify:success](ActivityTypes/bucket-accessblock-modify.md) |
| [aws-bucket-accessblock-failed](FieldsMappings/aws-bucket-accessblock-failed_fields.md) | [bucket-accessblock-modify:fail](ActivityTypes/bucket-accessblock-modify.md)|
| [aws-bucket-cors](FieldsMappings/aws-bucket-cors_fields.md) | [bucket-permission-modify:success](ActivityTypes/bucket-permission-modify.md) |
| [aws-bucket-cors-failed](FieldsMappings/aws-bucket-cors-failed_fields.md) | [bucket-permission-modify:fail](ActivityTypes/bucket-permission-modify.md)|
| [aws-bucket-create](FieldsMappings/aws-bucket-create_fields.md) | [bucket-create:success](ActivityTypes/bucket-create.md) |
| [aws-bucket-create-failed](FieldsMappings/aws-bucket-create-failed_fields.md) | [bucket-create:fail](ActivityTypes/bucket-create.md)|
| [aws-bucket-policy](FieldsMappings/aws-bucket-policy_fields.md) | [bucket-policy-modify:success](ActivityTypes/bucket-policy-modify.md) |
| [aws-bucket-policy-failed](FieldsMappings/aws-bucket-policy-failed_fields.md) | [bucket-policy-modify:fail](ActivityTypes/bucket-policy-modify.md)|
| [aws-compute-list](FieldsMappings/aws-compute-list_fields.md) | [endpoint-list:success](ActivityTypes/endpoint-list.md) |
| [aws-compute-list-failed](FieldsMappings/aws-compute-list-failed_fields.md) | [endpoint-list:fail](ActivityTypes/endpoint-list.md)|
| [aws-function-write](FieldsMappings/aws-function-write_fields.md) | [function-write:success](ActivityTypes/function-write.md) |
| [aws-function-write-failed](FieldsMappings/aws-function-write-failed_fields.md) | [function-write:fail](ActivityTypes/function-write.md)|
| [aws-general-activity](FieldsMappings/aws-general-activity_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [aws-general-activity-failed](FieldsMappings/aws-general-activity-failed_fields.md) | [app-activity:fail](ActivityTypes/app-activity.md)|
| [aws-identity-addtogroup](FieldsMappings/aws-identity-addtogroup_fields.md) | [group-member-add:success](ActivityTypes/group-member-add.md) |
| [aws-identity-addtogroup-failed](FieldsMappings/aws-identity-addtogroup-failed_fields.md) | [group-member-add:fail](ActivityTypes/group-member-add.md)|
| [aws-identity-creds-write](FieldsMappings/aws-identity-creds-write_fields.md) | [user-key-create:success](ActivityTypes/user-key-create.md) |
| [aws-identity-creds-write-failed](FieldsMappings/aws-identity-creds-write-failed_fields.md) | [user-key-create:fail](ActivityTypes/user-key-create.md)|
| [aws-identity-list](FieldsMappings/aws-identity-list_fields.md) | [group-list:success](ActivityTypes/group-list.md) |
| [aws-identity-list-failed](FieldsMappings/aws-identity-list-failed_fields.md) | [group-list:fail](ActivityTypes/group-list.md)|
| [aws-identity-loginprofile](FieldsMappings/aws-identity-loginprofile_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [aws-identity-loginprofile-failed](FieldsMappings/aws-identity-loginprofile-failed_fields.md) | [app-activity:fail](ActivityTypes/app-activity.md)|
| [aws-identity-write](FieldsMappings/aws-identity-write_fields.md) | [user-create:success](ActivityTypes/user-create.md) |
| [aws-identity-write-failed](FieldsMappings/aws-identity-write-failed_fields.md) | [user-create:fail](ActivityTypes/user-create.md)|
| [aws-image-create](FieldsMappings/aws-image-create_fields.md) | [image-create:success](ActivityTypes/image-create.md) |
| [aws-image-create-failed](FieldsMappings/aws-image-create-failed_fields.md) | [image-create:fail](ActivityTypes/image-create.md)|
| [aws-image-modify](FieldsMappings/aws-image-modify_fields.md) | [image-modify:success](ActivityTypes/image-modify.md) |
| [aws-image-modify-failed](FieldsMappings/aws-image-modify-failed_fields.md) | [image-modify:fail](ActivityTypes/image-modify.md)|
| [aws-instance-command](FieldsMappings/aws-instance-command_fields.md) | [endpoint-command:success](ActivityTypes/endpoint-command.md) |
| [aws-instance-command-failed](FieldsMappings/aws-instance-command-failed_fields.md) | [endpoint-command:fail](ActivityTypes/endpoint-command.md)|
| [aws-instance-create](FieldsMappings/aws-instance-create_fields.md) | [endpoint-create:success](ActivityTypes/endpoint-create.md) |
| [aws-instance-create-failed](FieldsMappings/aws-instance-create-failed_fields.md) | [endpoint-create:fail](ActivityTypes/endpoint-create.md)|
| [aws-instance-creds-read](FieldsMappings/aws-instance-creds-read_fields.md) | [key-read:success](ActivityTypes/key-read.md) |
| [aws-instance-creds-read-failed](FieldsMappings/aws-instance-creds-read-failed_fields.md) | [key-read:fail](ActivityTypes/key-read.md)|
| [aws-instance-creds-write](FieldsMappings/aws-instance-creds-write_fields.md) | [key-write:success](ActivityTypes/key-write.md) |
| [aws-instance-creds-write-failed](FieldsMappings/aws-instance-creds-write-failed_fields.md) | [key-write:fail](ActivityTypes/key-write.md)|
| [aws-instance-login](FieldsMappings/aws-instance-login_fields.md) | [endpoint-login:success](ActivityTypes/endpoint-login.md) |
| [aws-instance-login-failed](FieldsMappings/aws-instance-login-failed_fields.md) | [endpoint-login:fail](ActivityTypes/endpoint-login.md)|
| [aws-instance-modify](FieldsMappings/aws-instance-modify_fields.md) | [endpoint-modify:success](ActivityTypes/endpoint-modify.md) |
| [aws-instance-modify-failed](FieldsMappings/aws-instance-modify-failed_fields.md) | [endpoint-modify:fail](ActivityTypes/endpoint-modify.md)|
| [aws-instance-screenshot](FieldsMappings/aws-instance-screenshot_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [aws-instance-screenshot-failed](FieldsMappings/aws-instance-screenshot-failed_fields.md) | [app-activity:fail](ActivityTypes/app-activity.md)|
| [aws-login](FieldsMappings/aws-login_fields.md) | [app-login:success](ActivityTypes/app-login.md) |
| [aws-login-failed](FieldsMappings/aws-login-failed_fields.md) | [app-login:fail](ActivityTypes/app-login.md)|
| [aws-policy-attach](FieldsMappings/aws-policy-attach_fields.md) | [group-policy-attach:success](ActivityTypes/group-policy-attach.md) |
| [aws-policy-list](FieldsMappings/aws-policy-list_fields.md) | [policy-list:success](ActivityTypes/policy-list.md) |
| [aws-policy-list-failed](FieldsMappings/aws-policy-list-failed_fields.md) | [policy-list:fail](ActivityTypes/policy-list.md)|
| [aws-policy-setversion](FieldsMappings/aws-policy-setversion_fields.md) | [policy-modify:success](ActivityTypes/policy-modify.md) |
| [aws-policy-setversion-failed](FieldsMappings/aws-policy-setversion-failed_fields.md) | [policy-modify:fail](ActivityTypes/policy-modify.md)|
| [aws-policy-write](FieldsMappings/aws-policy-write_fields.md) | [policy-create:success](ActivityTypes/policy-create.md) |
| [aws-role-assume](FieldsMappings/aws-role-assume_fields.md) | [role-assume:success](ActivityTypes/role-assume.md) |
| [aws-role-assume-failed](FieldsMappings/aws-role-assume-failed_fields.md) | [role-assume:fail](ActivityTypes/role-assume.md)|
| [aws-role-assumepolicy](FieldsMappings/aws-role-assumepolicy_fields.md) | [role-permission-modify:success](ActivityTypes/role-permission-modify.md) |
| [aws-role-switch](FieldsMappings/aws-role-switch_fields.md) | [role-assume:success](ActivityTypes/role-assume.md) |
| [aws-role-write](FieldsMappings/aws-role-write_fields.md) | [role-create:fail](ActivityTypes/role-create.md)|
| [aws-snapshot-create](FieldsMappings/aws-snapshot-create_fields.md) | [snapshot-create:success](ActivityTypes/snapshot-create.md) |
| [aws-snapshot-create-failed](FieldsMappings/aws-snapshot-create-failed_fields.md) | [snapshot-create:fail](ActivityTypes/snapshot-create.md)|
| [aws-snapshot-modify](FieldsMappings/aws-snapshot-modify_fields.md) | [snapshot-modify:success](ActivityTypes/snapshot-modify.md) |
| [aws-snapshot-modify-failed](FieldsMappings/aws-snapshot-modify-failed_fields.md) | [snapshot-modify:fail](ActivityTypes/snapshot-modify.md)|
| [aws-storage-acl](FieldsMappings/aws-storage-acl_fields.md) | [bucket-permission-modify:success](ActivityTypes/bucket-permission-modify.md) |
| [aws-storage-acl-failed](FieldsMappings/aws-storage-acl-failed_fields.md) | [bucket-permission-modify:fail](ActivityTypes/bucket-permission-modify.md)|
| [aws-storage-list](FieldsMappings/aws-storage-list_fields.md) | [bucket-list:success](ActivityTypes/bucket-list.md) |
| [aws-storage-list-failed](FieldsMappings/aws-storage-list-failed_fields.md) | [bucket-list:fail](ActivityTypes/bucket-list.md)|
| [aws-storageobject-copy](FieldsMappings/aws-storageobject-copy_fields.md) | [file-copy:success](ActivityTypes/file-copy.md) |
| [aws-storageobject-copy-failed](FieldsMappings/aws-storageobject-copy-failed_fields.md) | [file-copy:fail](ActivityTypes/file-copy.md)|
| [aws-storageobject-read](FieldsMappings/aws-storageobject-read_fields.md) | [file-read:success](ActivityTypes/file-read.md) |
| [aws-storageobject-read-failed](FieldsMappings/aws-storageobject-read-failed_fields.md) | [file-read:fail](ActivityTypes/file-read.md)|
| [aws-storageobject-write](FieldsMappings/aws-storageobject-write_fields.md) | [file-write:success](ActivityTypes/file-write.md) |
| [aws-storageobject-write-failed](FieldsMappings/aws-storageobject-write-failed_fields.md) | [file-write:fail](ActivityTypes/file-write.md)|
| [aws-volume-attach](FieldsMappings/aws-volume-attach_fields.md) | [disk-attach:success](ActivityTypes/disk-attach.md) |
| [aws-volume-attach-failed](FieldsMappings/aws-volume-attach-failed_fields.md) | [disk-attach:fail](ActivityTypes/disk-attach.md)|
| [aws-volume-create](FieldsMappings/aws-volume-create_fields.md) | [disk-create:success](ActivityTypes/disk-create.md) |
| [aws-volume-create-failed](FieldsMappings/aws-volume-create-failed_fields.md) | [disk-create:fail](ActivityTypes/disk-create.md)|
| [aws-volume-modify](FieldsMappings/aws-volume-modify_fields.md) | [disk-modify:success](ActivityTypes/disk-modify.md) |
| [aws-volume-modify-failed](FieldsMappings/aws-volume-modify-failed_fields.md) | [disk-modify:fail](ActivityTypes/disk-modify.md)|
| [azure-blob-read](FieldsMappings/azure-blob-read_fields.md) | [file-read:fail](ActivityTypes/file-read.md)|
| [azure-blob-write](FieldsMappings/azure-blob-write_fields.md) | [file-write:fail](ActivityTypes/file-write.md)|
| [azure-container-acl](FieldsMappings/azure-container-acl_fields.md) | [file-permission-modify:fail](ActivityTypes/file-permission-modify.md)|
| [azure-disk-write](FieldsMappings/azure-disk-write_fields.md) | [disk-write:success](ActivityTypes/disk-write.md) |
| [azure-image-write](FieldsMappings/azure-image-write_fields.md) | [image-write:success](ActivityTypes/image-write.md) |
| [azure-instance-creds-write](FieldsMappings/azure-instance-creds-write_fields.md) | [key-write:success](ActivityTypes/key-write.md) |
| [azure-instance-write](FieldsMappings/azure-instance-write_fields.md) | [image-write:success](ActivityTypes/image-write.md) |
| [azure-keyvault-read](FieldsMappings/azure-keyvault-read_fields.md) | [key-read:fail](ActivityTypes/key-read.md)|
| [azure-keyvault-write](FieldsMappings/azure-keyvault-write_fields.md) | [key-write:fail](ActivityTypes/key-write.md)|
| [azure-role-assign](FieldsMappings/azure-role-assign_fields.md) | [user-role-assign:success](ActivityTypes/user-role-assign.md) |
| [azure-role-write](FieldsMappings/azure-role-write_fields.md) | [role-write:success](ActivityTypes/role-write.md) |
| [azure-snapshot-write](FieldsMappings/azure-snapshot-write_fields.md) | [snapshot-write:success](ActivityTypes/snapshot-write.md) |
| [azure-storage-list](FieldsMappings/azure-storage-list_fields.md) | [file-list:fail](ActivityTypes/file-list.md)|
| [batch-logon](FieldsMappings/batch-logon_fields.md) | [endpoint-login:fail](ActivityTypes/endpoint-login.md)|
| [cloud-admin-activity](FieldsMappings/cloud-admin-activity_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [cloud-admin-activity-failed](FieldsMappings/cloud-admin-activity-failed_fields.md) | [app-activity:fail](ActivityTypes/app-activity.md)|
| [computer-logon](FieldsMappings/computer-logon_fields.md) | [dhcp-session:success](ActivityTypes/dhcp-session.md) |
| [config-change](FieldsMappings/config-change_fields.md) | [configuration-modify:fail](ActivityTypes/configuration-modify.md)|
| [database-access](FieldsMappings/database-access_fields.md) | [database-activity:success](ActivityTypes/database-activity.md) |
| [database-activity-failed](FieldsMappings/database-activity-failed_fields.md) | [database-activity:fail](ActivityTypes/database-activity.md)|
| [database-alert](FieldsMappings/database-alert_fields.md) | [alert-trigger:success](ActivityTypes/alert-trigger.md) |
| [database-delete](FieldsMappings/database-delete_fields.md) | [database-delete:success](ActivityTypes/database-delete.md) |
| [database-failed-login](FieldsMappings/database-failed-login_fields.md) | [database-login:fail](ActivityTypes/database-login.md)|
| [database-login](FieldsMappings/database-login_fields.md) | [database-login:success](ActivityTypes/database-login.md) |
| [database-query](FieldsMappings/database-query_fields.md) | [database-query:fail](ActivityTypes/database-query.md)|
| [database-update](FieldsMappings/database-update_fields.md) | [database-modify:success](ActivityTypes/database-modify.md) |
| [dcom-activation-failed](FieldsMappings/dcom-activation-failed_fields.md) | [dcom-activate:fail](ActivityTypes/dcom-activate.md)|
| [dlp-alert](FieldsMappings/dlp-alert_fields.md) | [alert-trigger:success](ActivityTypes/alert-trigger.md) |
| [dlp-email-alert-in](FieldsMappings/dlp-email-alert-in_fields.md) | [email-receive:success](ActivityTypes/email-receive.md) |
| [dlp-email-alert-in-failed](FieldsMappings/dlp-email-alert-in-failed_fields.md) | [email-receive:fail](ActivityTypes/email-receive.md)|
| [dlp-email-alert-out](FieldsMappings/dlp-email-alert-out_fields.md) | [email-send:success](ActivityTypes/email-send.md) |
| [dlp-email-alert-out-failed](FieldsMappings/dlp-email-alert-out-failed_fields.md) | [email-send:fail](ActivityTypes/email-send.md)|
| [dns-query](FieldsMappings/dns-query_fields.md) | [dns-request:fail](ActivityTypes/dns-request.md)|
| [dns-response](FieldsMappings/dns-response_fields.md) | [dns-response:fail](ActivityTypes/dns-response.md)|
| [ds-access](FieldsMappings/ds-access_fields.md) | [ds_object-activity:success](ActivityTypes/ds_object-activity.md) |
| [email_rule-create](FieldsMappings/email_rule-create_fields.md) | [email_rule-create:success](ActivityTypes/email_rule-create.md) |
| [email_rule-delete](FieldsMappings/email_rule-delete_fields.md) | [email_rule-delete:success](ActivityTypes/email_rule-delete.md) |
| [email_rule-disable](FieldsMappings/email_rule-disable_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [email_rule-enable](FieldsMappings/email_rule-enable_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [email_rule-modify](FieldsMappings/email_rule-modify_fields.md) | [email_rule-modify:success](ActivityTypes/email_rule-modify.md) |
| [failed-app-login](FieldsMappings/failed-app-login_fields.md) | [app-login:fail](ActivityTypes/app-login.md)|
| [failed-ds-access](FieldsMappings/failed-ds-access_fields.md) | [ds_object-activity:fail](ActivityTypes/ds_object-activity.md)|
| [failed-logon](FieldsMappings/failed-logon_fields.md) | [endpoint-authentication:fail](ActivityTypes/endpoint-authentication.md)|
| [failed-physical-access](FieldsMappings/failed-physical-access_fields.md) | [physical_location-access:fail](ActivityTypes/physical_location-access.md)|
| [failed-usb-activity](FieldsMappings/failed-usb-activity_fields.md) | [peripheral_storage-activity:fail](ActivityTypes/peripheral_storage-activity.md)|
| [failed-vpn-login](FieldsMappings/failed-vpn-login_fields.md) | [vpn-login:fail](ActivityTypes/vpn-login.md)|
| [file-alert](FieldsMappings/file-alert_fields.md) | [alert-trigger:success](ActivityTypes/alert-trigger.md) |
| [file-close](FieldsMappings/file-close_fields.md) | [file-close:success](ActivityTypes/file-close.md) |
| [file-delete](FieldsMappings/file-delete_fields.md) | [file-delete:fail](ActivityTypes/file-delete.md)|
| [file-download](FieldsMappings/file-download_fields.md) | [file-download:fail](ActivityTypes/file-download.md)|
| [file-move](FieldsMappings/file-move_fields.md) | [file-move:success](ActivityTypes/file-move.md) |
| [file-permission-change](FieldsMappings/file-permission-change_fields.md) | [file-permission-modify:success](ActivityTypes/file-permission-modify.md) |
| [file-read](FieldsMappings/file-read_fields.md) | [file-read:fail](ActivityTypes/file-read.md)|
| [file-share](FieldsMappings/file-share_fields.md) | [file-share:success](ActivityTypes/file-share.md) |
| [file-upload](FieldsMappings/file-upload_fields.md) | [file-share:success](ActivityTypes/file-share.md) |
| [file-write](FieldsMappings/file-write_fields.md) | [file-copy:success](ActivityTypes/file-copy.md) |
| [gcp-bucket-create](FieldsMappings/gcp-bucket-create_fields.md) | [bucket-create:success](ActivityTypes/bucket-create.md) |
| [gcp-compute-list](FieldsMappings/gcp-compute-list_fields.md) | [disk-list:success](ActivityTypes/disk-list.md) |
| [gcp-disk-attach](FieldsMappings/gcp-disk-attach_fields.md) | [disk-attach:success](ActivityTypes/disk-attach.md) |
| [gcp-disk-create](FieldsMappings/gcp-disk-create_fields.md) | [disk-create:success](ActivityTypes/disk-create.md) |
| [gcp-function-write](FieldsMappings/gcp-function-write_fields.md) | [function-write:success](ActivityTypes/function-write.md) |
| [gcp-general-activity](FieldsMappings/gcp-general-activity_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [gcp-image-create](FieldsMappings/gcp-image-create_fields.md) | [image-create:success](ActivityTypes/image-create.md) |
| [gcp-instance-create](FieldsMappings/gcp-instance-create_fields.md) | [endpoint-create:success](ActivityTypes/endpoint-create.md) |
| [gcp-instance-screenshot](FieldsMappings/gcp-instance-screenshot_fields.md) | [endpoint-screenshot:success](ActivityTypes/endpoint-screenshot.md) |
| [gcp-instance-setmachinetype](FieldsMappings/gcp-instance-setmachinetype_fields.md) | [endpoint-modify:success](ActivityTypes/endpoint-modify.md) |
| [gcp-instance-setmetadata](FieldsMappings/gcp-instance-setmetadata_fields.md) | [endpoint-modify:success](ActivityTypes/endpoint-modify.md) |
| [gcp-policy-write](FieldsMappings/gcp-policy-write_fields.md) | [bucket-permission-modify:success](ActivityTypes/bucket-permission-modify.md) |
| [gcp-role-list](FieldsMappings/gcp-role-list_fields.md) | [role-list:success](ActivityTypes/role-list.md) |
| [gcp-role-write](FieldsMappings/gcp-role-write_fields.md) | [role-create:success](ActivityTypes/role-create.md) |
| [gcp-serviceaccount-creds-write](FieldsMappings/gcp-serviceaccount-creds-write_fields.md) | [user-key-create:success](ActivityTypes/user-key-create.md) |
| [gcp-serviceaccount-write](FieldsMappings/gcp-serviceaccount-write_fields.md) | [user-create:success](ActivityTypes/user-create.md) |
| [gcp-snapshot-create](FieldsMappings/gcp-snapshot-create_fields.md) | [snapshot-create:success](ActivityTypes/snapshot-create.md) |
| [gcp-storage-list](FieldsMappings/gcp-storage-list_fields.md) | [bucket-list:fail](ActivityTypes/bucket-list.md)|
| [gcp-storageobject-acl](FieldsMappings/gcp-storageobject-acl_fields.md) | [file-permission-modify:success](ActivityTypes/file-permission-modify.md) |
| [gcp-storageobject-read](FieldsMappings/gcp-storageobject-read_fields.md) | [file-read:success](ActivityTypes/file-read.md) |
| [gcp-storageobject-write](FieldsMappings/gcp-storageobject-write_fields.md) | [file-write:success](ActivityTypes/file-write.md) |
| [group-role-assign](FieldsMappings/group-role-assign_fields.md) | [group-role-assign:success](ActivityTypes/group-role-assign.md) |
| [group-role-revoke](FieldsMappings/group-role-revoke_fields.md) | [group-role-revoke:success](ActivityTypes/group-role-revoke.md) |
| [image-loaded](FieldsMappings/image-loaded_fields.md) | [dll-load:success](ActivityTypes/dll-load.md) |
| [kerberos-logon](FieldsMappings/kerberos-logon_fields.md) | [endpoint-authentication:success](ActivityTypes/endpoint-authentication.md) |
| [local-logon](FieldsMappings/local-logon_fields.md) | [endpoint-login:fail](ActivityTypes/endpoint-login.md)|
| [logout-remote](FieldsMappings/logout-remote_fields.md) | [endpoint-logout:success](ActivityTypes/endpoint-logout.md) |
| [m365-app-activity](FieldsMappings/m365-app-activity_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [m365-app-activity-fail](FieldsMappings/m365-app-activity-fail_fields.md) | [app-activity:fail](ActivityTypes/app-activity.md)|
| [m365-file-copy](FieldsMappings/m365-file-copy_fields.md) | [file-copy:success](ActivityTypes/file-copy.md) |
| [m365-file-delete](FieldsMappings/m365-file-delete_fields.md) | [file-delete:success](ActivityTypes/file-delete.md) |
| [m365-file-download](FieldsMappings/m365-file-download_fields.md) | [file-download:success](ActivityTypes/file-download.md) |
| [m365-file-move](FieldsMappings/m365-file-move_fields.md) | [file-move:success](ActivityTypes/file-move.md) |
| [m365-file-read](FieldsMappings/m365-file-read_fields.md) | [file-read:success](ActivityTypes/file-read.md) |
| [m365-file-rename](FieldsMappings/m365-file-rename_fields.md) | [file-rename:success](ActivityTypes/file-rename.md) |
| [m365-file-write](FieldsMappings/m365-file-write_fields.md) | [file-write:success](ActivityTypes/file-write.md) |
| [m365-group-create](FieldsMappings/m365-group-create_fields.md) | [group-create:success](ActivityTypes/group-create.md) |
| [m365-user-create](FieldsMappings/m365-user-create_fields.md) | [user-create:success](ActivityTypes/user-create.md) |
| [m365-user-create-fail](FieldsMappings/m365-user-create-fail_fields.md) | [user-create:fail](ActivityTypes/user-create.md)|
| [m365-user-delete](FieldsMappings/m365-user-delete_fields.md) | [user-delete:success](ActivityTypes/user-delete.md) |
| [mailbox-item-delete](FieldsMappings/mailbox-item-delete_fields.md) | [mailbox-item-delete:success](ActivityTypes/mailbox-item-delete.md) |
| [mailbox-item-read](FieldsMappings/mailbox-item-read_fields.md) | [mailbox-item-read:success](ActivityTypes/mailbox-item-read.md) |
| [mailbox-modify](FieldsMappings/mailbox-modify_fields.md) | [mailbox-modify:success](ActivityTypes/mailbox-modify.md) |
| [member-added](FieldsMappings/member-added_fields.md) | [group-member-add:success](ActivityTypes/group-member-add.md) |
| [member-removed](FieldsMappings/member-removed_fields.md) | [group-member-remove:success](ActivityTypes/group-member-remove.md) |
| [nac-failed-logon](FieldsMappings/nac-failed-logon_fields.md) | [endpoint-authentication:fail](ActivityTypes/endpoint-authentication.md)|
| [nac-logon](FieldsMappings/nac-logon_fields.md) | [endpoint-authentication:success](ActivityTypes/endpoint-authentication.md) |
| [netflow-connection](FieldsMappings/netflow-connection_fields.md) | [network-session:success](ActivityTypes/network-session.md) |
| [network-alert](FieldsMappings/network-alert_fields.md) | [alert-trigger:success](ActivityTypes/alert-trigger.md) |
| [network-connection-failed](FieldsMappings/network-connection-failed_fields.md) | [network-close:success](ActivityTypes/network-close.md) |
| [network-connection-successful](FieldsMappings/network-connection-successful_fields.md) | [dns-traffic:success](ActivityTypes/dns-traffic.md) |
| [network-info](FieldsMappings/network-info_fields.md) | [network-notification:success](ActivityTypes/network-notification.md) |
| [ntlm-logon](FieldsMappings/ntlm-logon_fields.md) | [endpoint-authentication:success](ActivityTypes/endpoint-authentication.md) |
| [physical-access](FieldsMappings/physical-access_fields.md) | [physical_location-access:success](ActivityTypes/physical_location-access.md) |
| [print-activity](FieldsMappings/print-activity_fields.md) | [printer-activity:success](ActivityTypes/printer-activity.md) |
| [privileged-access](FieldsMappings/privileged-access_fields.md) | [user-privilege-assign:success](ActivityTypes/user-privilege-assign.md) |
| [privileged-object-access](FieldsMappings/privileged-object-access_fields.md) | [user-privilege-use:success](ActivityTypes/user-privilege-use.md) |
| [process-alert](FieldsMappings/process-alert_fields.md) | [alert-trigger:success](ActivityTypes/alert-trigger.md) |
| [process-created](FieldsMappings/process-created_fields.md) | [process-create:success](ActivityTypes/process-create.md) |
| [process-created-failed](FieldsMappings/process-created-failed_fields.md) | [process-create:fail](ActivityTypes/process-create.md)|
| [process-network](FieldsMappings/process-network_fields.md) | [network-session:success](ActivityTypes/network-session.md) |
| [process-network-failed](FieldsMappings/process-network-failed_fields.md) | [network-session:fail](ActivityTypes/network-session.md)|
| [registry-write](FieldsMappings/registry-write_fields.md) | [registry-create:success](ActivityTypes/registry-create.md) |
| [remote-access](FieldsMappings/remote-access_fields.md) | [endpoint-login:fail](ActivityTypes/endpoint-login.md)|
| [remote-logon](FieldsMappings/remote-logon_fields.md) | [endpoint-login:fail](ActivityTypes/endpoint-login.md)|
| [security-alert](FieldsMappings/security-alert_fields.md) | [alert-trigger:success](ActivityTypes/alert-trigger.md) |
| [service-created](FieldsMappings/service-created_fields.md) | [service-create:success](ActivityTypes/service-create.md) |
| [service-logon](FieldsMappings/service-logon_fields.md) | [endpoint-login:success](ActivityTypes/endpoint-login.md) |
| [share-access](FieldsMappings/share-access_fields.md) | [share-access:success](ActivityTypes/share-access.md) |
| [share-access-denied](FieldsMappings/share-access-denied_fields.md) | [share-access:fail](ActivityTypes/share-access.md)|
| [share_link-create](FieldsMappings/share_link-create_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [share_link-member-add](FieldsMappings/share_link-member-add_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [share_link-modify](FieldsMappings/share_link-modify_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [share_link-use](FieldsMappings/share_link-use_fields.md) | [share_link-open:success](ActivityTypes/share_link-open.md) |
| [system-info](FieldsMappings/system-info_fields.md) | [certificate-request:success](ActivityTypes/certificate-request.md) |
| [task-created](FieldsMappings/task-created_fields.md) | [scheduled_task-create:fail](ActivityTypes/scheduled_task-create.md)|
| [usb-activity](FieldsMappings/usb-activity_fields.md) | [peripheral_storage-activity:success](ActivityTypes/peripheral_storage-activity.md) |
| [usb-insert](FieldsMappings/usb-insert_fields.md) | [peripheral_storage-insert:success](ActivityTypes/peripheral_storage-insert.md) |
| [usb-read](FieldsMappings/usb-read_fields.md) | [file-read:success](ActivityTypes/file-read.md) |
| [usb-write](FieldsMappings/usb-write_fields.md) | [file-write:success](ActivityTypes/file-write.md) |
| [user-role-assign](FieldsMappings/user-role-assign_fields.md) | [user-role-assign:success](ActivityTypes/user-role-assign.md) |
| [user-role-revoke](FieldsMappings/user-role-revoke_fields.md) | [user-role-revoke:success](ActivityTypes/user-role-revoke.md) |
| [vpn-connection](FieldsMappings/vpn-connection_fields.md) | [vpn-login:fail](ActivityTypes/vpn-login.md)|
| [vpn-login](FieldsMappings/vpn-login_fields.md) | [vpn-login:success](ActivityTypes/vpn-login.md) |
| [vpn-logout](FieldsMappings/vpn-logout_fields.md) | [vpn-logout:success](ActivityTypes/vpn-logout.md) |
| [web-activity-allowed](FieldsMappings/web-activity-allowed_fields.md) | [http-request:success](ActivityTypes/http-request.md) |
| [web-activity-denied](FieldsMappings/web-activity-denied_fields.md) | [http-request:fail](ActivityTypes/http-request.md)|
| [web-meeting-created](FieldsMappings/web-meeting-created_fields.md) | [meeting-create:success](ActivityTypes/meeting-create.md) |
| [web-meeting-ended](FieldsMappings/web-meeting-ended_fields.md) | [meeting-end:success](ActivityTypes/meeting-end.md) |
| [web-meeting-participant-joined](FieldsMappings/web-meeting-participant-joined_fields.md) | [meeting-member-join:success](ActivityTypes/meeting-member-join.md) |
| [web-meeting-started](FieldsMappings/web-meeting-started_fields.md) | [meeting-start:success](ActivityTypes/meeting-start.md) |
| [web-meeting-updated](FieldsMappings/web-meeting-updated_fields.md) | [meeting-modify:success](ActivityTypes/meeting-modify.md) |
| [webconference-login](FieldsMappings/webconference-login_fields.md) | [app-login:success](ActivityTypes/app-login.md) |
| [webconference-operations-activity](FieldsMappings/webconference-operations-activity_fields.md) | [app-activity:success](ActivityTypes/app-activity.md) |
| [winsession-disconnect](FieldsMappings/winsession-disconnect_fields.md) | [endpoint-logout:success](ActivityTypes/endpoint-logout.md) |
| [workstation-locked](FieldsMappings/workstation-locked_fields.md) | [endpoint-lock:success](ActivityTypes/endpoint-lock.md) |
| [workstation-unlocked](FieldsMappings/workstation-unlocked_fields.md) | [endpoint-unlock:success](ActivityTypes/endpoint-unlock.md) |