Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: azure-metrics
### New-Scale Activity Type: app-activity:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields          | New-Scale Fields |
| ------------------- | ---------------- |
| authorization_scope | auth_scope       |
| bucket              | bucket_name      |
| device              | device_name      |
| user_email          | email_address    |
| log_type            | event_category   |
| source              | legacy_product   |
| service             | service_name     |
| full_url            | url              |
| action,<br>outcome  | action           |
| result,<br>outcome  | result           |