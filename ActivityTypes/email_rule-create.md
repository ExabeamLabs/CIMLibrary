email_rule-create
=================

Description
-----------
An email rule was created

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | email_rule        |
| Activity      | create            |
| Activity Type | email_rule-create |
| Pretty Name   | Email_rule Create |

Legacy Names
------------
| Success          | Fail |
| ---------------- | ---- |
| app-activity<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email_rule-createsuccess) or a [fail](#email_rule-createfail).


email_rule-create:success
-------------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| dest_email_domain |      | &#10003;  |               |
| email_domain      |      | &#10003;  |               |
| operation         |      | &#10003;  |               |

email_rule-create:fail
----------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| dest_email_domain |      | &#10003;  |               |
| failure_code      |      | &#10003;  |               |
| email_domain      |      | &#10003;  |               |
| failure_reason    |      | &#10003;  |               |
| operation         |      | &#10003;  |               |