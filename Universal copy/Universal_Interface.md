 Universal Interface
====================

###  Description

The universal interface defines a set of global fields. These are fields that are required for every event, regardless of event type. The following list represents the minimum fields required to define an event. The list includes the CDI values for each field.

```Java
"universal": {
  "description": "",
  "fields": {
    "time": {
      "core": "1",
      "detection": "0",
      "informational": "0"
    },
    "product": {
      "core": "1",
      "detection": "0",
      "informational": "0"
    },
    "product_category": {
      "core": "0",
      "detection": "1",
      "informational": "0"
    },
    "vendor": {
      "core": "1",
      "detection": "0",
      "informational": "0"
    },
    "platform": {
      "core": "0",
      "detection": "1",
      "informational": "0"
    },
    "landscape": {
      "core": "0",
      "detection": "1",
      "informational": "0"
    },
    "outcome": {
      "core": "1",
      "detection": "0",
      "informational": "0"
    },
    "subject": {
      "core": "1",
      "detection": "0",
      "informational": "0"
    },
    "host": {
      "core": "0",
      "detection": "0",
      "informational": "1"
    },
    "activity_type": {
      "core": "1",
      "detection": "0",
      "informational": "0"
    }
  }
},
```