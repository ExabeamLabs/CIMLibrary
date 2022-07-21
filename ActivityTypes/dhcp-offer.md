dhcp-offer
==========

Description
-----------
A DHCP offer packet

The possible fields for this activity type will vary depending on whether the activity was a [success](#dhcp-offersuccess) or a [fail](#dhcp-offerfail).

| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | dhcp       |
| Activity      | offer      |
| Activity Type | dhcp-offer |
| Pretty Name   | Dhcp Offer |
| Legacy Name   |            |

dhcp-offer:success
------------------

There are no fields for this activity type.


dhcp-offer:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |