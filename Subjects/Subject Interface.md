Subject Interface
====================

### Description
This core interface defines the subject element. It details the minimum field requirements necessary to identify the subject across possible logs. By design, the subject is maintained as a minimalist interface, including only fields that are fundamental to representing the entity.

### Subjects
| Name | Description | Core Fields| Detection Fields| Informational Fields|
|:-----|:------|:----------|:----------|:----------|
|   file   |  A file is a storage object on endpoints and applications, that contains content, data or settings that can be written into it or read from it    |  file_name  <br> | file_path  <br>file_ext<br>file_dir ||
|   process   |  A process is an endpoint structure that represents an instance of a program that was executed and is now running.    |     process_name <br>dest_process_name  <br>|process_path <br>process_dir  <br>process_command_line<br>dest_process_command_line <br>src_host |process_id <br>dest_process_id  <br>|
|   user   |  A user account is the identity given to a person or a machine with which they can interact with the environment.    |     dest_user<br> | |dest_domain|

```Java
"Subjects": {
  "file": {
    "description": "A file is a storage object on endpoints and applications, that contains content, data or settings that can be written into it or read from it.",
    "fields": {
      "file_name": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "file_path": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "file_ext": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "file_dir": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "process": {
    "description": "A process is an endpoint structure that represents an instance of a program that was executed and is now running.",
    "fields": {
      "process_name": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "process_path": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "process_dir": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "process_command_line": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "process_id": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "dest_process_name": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "dest_process_path": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_process_dir": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_process_command_line": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_process_id": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "src_host": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "user": {
    "description": "A user account is the identity given to a person or a machine with which they can interact with the environment.",
    "fields": {
      "dest_user": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "dest_domain": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "group": {
    "description": "A group is a collection of user accounts or any other type of member, which can globally define their configuration, settings or role in the system.",
    "fields": {
      "group_name": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "group_domain": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "log": {
    "description": "A log (audit log) is a program or a service that collects audit data from an environment and keeps record of it.",
    "fields": {
      "log_name": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      }
    }
  },
  "audit_policy": {
    "description": "An audit policy is a unique configuration given either globally or per service, that defines what type of audit logs will be generated\\recorded and be transferred to a log",
    "fields": {
      "audit_policy_name": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      }
    }
  },
  "configuration": {
    "description": "A configuration is a global setting given to a program or an app, which can define how the system should work, look like or be enforced.",
    "fields": {}
  },
  "dcom": {
    "description": "DCOM (Distributed Component Object Model) objects are Windows endpoint components that allow COM objects to communicate with each other over the network",
    "fields": {
      "clsid": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "appid": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "user": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "domain": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "src_host": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      }
    }
  },
  "email": {
    "description": "An email is a mail message that is sent or received over a computer network",
    "fields": {
      "user": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "domain": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "ds_object": {
    "description": "A directory service object represents every entity that can exist in a directory service configuration, such as OUs or even groups and users. This subject is only used in cases where we aren't sure what was the original subject.",
    "fields": {
      "ds_object_name": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "ds_object_class": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "ds_object_ou": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "ds_object_dn": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "ds_name": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "ds_type": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "physical_location": {
    "description": "A physical location represents a location in a building or a workplace like a door,  a gate, or a room.",
    "fields": {
      "location_door": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "location_building": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "location_city": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "direction": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "badge_id": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "employee_id": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "peripheral_storage": {
    "description": "A peripheral storage device is an external hardware device used for storing files and data such as USB, CD/DVD, or a HD.",
    "fields": {
      "device_id": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "device_type": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "src_host": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "dll": {
    "description": "A dynamic link library (DLL) is a shared program module containing code and functions that may be dynamically called by a process at run time. A DLL usually has a file extension ending in .dll",
    "fields": {
      "process_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "process_path": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "process_dir": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "process_id": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "src_process_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_process_path": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "src_process_dir": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "src_process_id": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "file_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "file_path": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "file_ext": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "file_dir": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "src_host": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "printer": {
    "description": "A printer is an external device which performs the functions of printing\\copying\\faxing\\etc.. on files and documents. ",
    "fields": {}
  },
  "registry": {
    "description": "The registry contains all objects under the Windows registry, such as keys and values. This activity records all operation on registry objects such as setting a registry value or creating a new key.",
    "fields": {
      "registry_key": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "registry_path": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "registry_hive": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "registry_value": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "registry_details": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "registry_details_type": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "src_host": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "service": {
    "description": "A service is an endpoint object that represents a program or a process that runs in the background and quitely performs automated tasks. For example - Windows services or Unix daemon.",
    "fields": {
      "service_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_host": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "scheduled_task": {
    "description": "A scheduled task is an object that is scheduled to trigger and execute a program or run certain commands.",
    "fields": {
      "task_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_host": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "share": {
    "description": "A network share is an endpoint object that allows resources and files to be shared over a computer network as if they were local.",
    "fields": {
      "share_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "share_path": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "meeting": {
    "description": "A meeting represents an instance of a web conference meeting, which allows a group of users to video chat and share screens.",
    "fields": {
      "meeting_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "meeting_host_id": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "user": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "domain": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "network": {
    "description": "The network subject represents all unclassified network traffic and protocols",
    "fields": {
      "protocol": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "bytes": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "src_mac": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_mac": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "src_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "src_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "dns": {
    "description": "Domain Name System (DNS) protocol is a network protocol used to translate hostnames to IP addresses. This subject represents DNS traffic related activities.",
    "fields": {
      "src_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_port": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "dest_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dns_query": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dns_query_flags": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dns_query_type": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "http": {
    "description": "Hyper Text Transfer Protocol (HTTP) is a network protocol used for web requests and communications. This subject represents HTTP (and built upon protocols like HTTPS) traffic related activities.",
    "fields": {
      "user": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "src_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "src_port": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "dest_port": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "uri_path": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "uri_query": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "url": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "web_domain": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "top_domain": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "dhcp": {
    "description": "Dynamic Host Configuration Protocol (DHCP) is a network protocol used to automatically assign a client with an IP address. This subject represents DHCP traffic related activities.",
    "fields": {
      "src_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "dest_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_port": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "dest_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "assigned_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "ssh": {
    "description": "Secure Shell (SSH) is a network protocol used for secure remote login from one computer to another other a network. This subject represents SSH traffic related activities.",
    "fields": {
      "src_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "dest_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "radius": {
    "description": "Remote Authentication Dial-In User Service (RADIUS) is a networking protocol that provides centralized authentication, authorization, and accounting management for users who connect and use a network service.",
    "fields": {
      "src_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "dest_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "rdp": {
    "description": "Remote Desktop Protocol (RDP) is a network protocol which provides a user with a graphical interface to connect to another computer over a network connection. This subject represents RDP traffic related activities.",
    "fields": {
      "src_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "dest_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "app": {
    "description": "The app subject represents applications and contains activities directed straightly towards them",
    "fields": {}
  },
  "endpoint": {
    "description": "The endpoint subject represents an endpoint machine and the objects that can represent said machine inside different applications.",
    "fields": {
      "dest_host": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "vpn": {
    "description": "The VPN subject represents a VPN interface and contains activities directed towards the VPN app",
    "fields": {
      "src_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "database": {
    "description": "The database subject represents a database interface and the resources it contains",
    "fields": {}
  },
  "ftp": {
    "description": "File transfer protocel (FTP) is a network protocol used to transmitting files over the network. This subject represents FTP traffic related activities.",
    "fields": {
      "src_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "branch": {
    "description": "A git branch represents an instance of a specific commit to a project",
    "fields": {
      "branch_name": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "call": {
    "description": "A call is a phonecall, any personal call that is not a meeting, general VOIP sessions any other type of personal video chat session that is not a meeting.",
    "fields": {
      "user": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "dest_user": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "channel": {
    "description": "A channel is a conversation space in communication apps, dedicated to a specific topic of interest. A channel contains multiple people and allows them to share messages and calls. For example - Slack channels, Team teams channels...",
    "fields": {
      "domain": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "user": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "channel_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "cluster": {
    "description": "A cluster is used in virutalization solutions to represent a group of vm hosts.",
    "fields": {
      "cluster_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "datacenter": {
    "description": "A datacenter is a group of datastores that contain VMs and general storage in virutalization solutions.",
    "fields": {
      "datacenter_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "datastore": {
    "description": "A datastore represents the storage space that is used by\\to support virtualization resources (VMs). For example - VMWare datastores, OVirt storage domains...",
    "fields": {
      "datastore_name": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "disk": {
    "description": "A disk is a virtual representation of a volume that is attached to a machine and adds new storage space or a new logical drive.",
    "fields": {
      "disk_name": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "vm_pool": {
    "description": "A virtual machine pool is a group of vm objects that share a common source. The VM pool contains the configuration of the VMs inside it.",
    "fields": {
      "vm_pool_name": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      }
    }
  },
  "vm_template": {
    "description": "A virtual machine template is used in virtualization solutions to create a common structure from which VMs can be created",
    "fields": {
      "vm_template_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "folder": {
    "description": "A folder is a logical object used to store or contain other types of objects beneath in. Note that this subject is not used for file folders.",
    "fields": {
      "folder_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "hook": {
    "description": "A hook\\webhook represents a function that is subscribed to an event and triggers once it occurs. Multiple platforms allow the creation of hooks such as GitHub webhooks or Windows SetWindowsHook...",
    "fields": {}
  },
  "image": {
    "description": "A machine image is a virtualization resource that stores all the properties and data from a VM and is used to launch new instances.",
    "fields": {
      "image_name": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      }
    }
  },
  "incident": {
    "description": "A security incident represents an open case in security products, which are interacted on and expanded by users.",
    "fields": {
      "incident_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "mailbox": {
    "description": "A mailbox is the destination to which email messages are delivered.",
    "fields": {
      "mailbox_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "message": {
    "description": "A message represents a single text message or a post in in-person communication channels, like Teams or Whatsapp.",
    "fields": {
      "domain": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "user": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "password": {
    "description": "A password represents a global password object that is not necessarily associated with a user. These objects are usually stored in vaults. ",
    "fields": {
      "user": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "email_rule": {
    "description": "An email rule is used to automatically perform specific actions on emails that are being received by a user.",
    "fields": {
      "rule": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "rule_id": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "policy": {
    "description": "A security policy is an independent configuration document given to a resource\\identity, that defines what type of permissions, privileges or roles this identity\\resource should be assigned.",
    "fields": {
      "policy_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "report": {
    "description": "A report is a document containing conclusions and information gathered from aggregated data in the system.",
    "fields": {
      "report": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "repository": {
    "description": "A git repository is a folder containing all the changes to versions, commits and instances of a git project",
    "fields": {
      "repository_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "role": {
    "description": "A security role is an independent object representing a group of permissions or privileges that can be assigned to an identity.",
    "fields": {
      "role_name": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "role_id": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "rule": {
    "description": "A security rule represents an instace of a detection condition stored in an object on a security product, meant to trigger once the conditions are met.",
    "fields": {
      "rule": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "secret": {
    "description": "Secrets are a type of digital authenticaiton credentials used by accounts to identify against resources and applicatons.",
    "fields": {
      "secret": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "share_link": {
    "description": "A share link represents the sharing access and location that was given to a user against a resource, usually a file in cloud file sharing applications.",
    "fields": {
      "link": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "link_id": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "vm_host": {
    "description": "A virtual machine host is the server that runs the virtual machines' hypervisors.",
    "fields": {
      "vm_host_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "workspace": {
    "description": "All operations on a workspace. A workspace is a collaboration environment that represents an instance of an application and allows multiple users to work together and share information",
    "fields": {
      "workspace_name": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "log_source": {
    "description": "A log source is the representation of a connection between an audit log and an application, as represented by the application.",
    "fields": {
      "log_source": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "driver": {
    "description": "A driver is a software component that lets the operating system and a device communicate with each other by running code in the kernel. A driver usually has a file extension ending in .sys",
    "fields": {
      "driver_name": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "bucket": {
    "description": "A bucket is the storage container which holds files and data in cloud storage solutions",
    "fields": {
      "bucket_name": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "snapshot": {
    "description": "A snapshot is a copy of a virtual machine's state and content at a given point in time.",
    "fields": {}
  },
  "key": {
    "description": "A key represents a global credential key object that is not necessarily associated with a user. These objects are usually stored in vaults. ",
    "fields": {}
  },
  "alert": {
    "description": "Alert represents any security alert, whether anomaly, correlation or third party",
    "fields": {
      "alert_name": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "alert_type": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "alert_subject": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "alert_severity": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      },
      "alert_source": {
        "core": "1",
        "detection": "0",
        "informational": "0"
      }
    }
  },
  "handle": {
    "description": "A Windows handle is an object that represnets the access point to a single object in memory. Processes in Windows must request a handle before they can directly access resources such as files or other processes;",
    "fields": {
      "handle_id": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "dns_record": {
    "description": "A DNS record is an object used in DNS servers or configurations to store\\cache the results of a DNS translation.",
    "fields": {
      "dns_record_type": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "arp": {
    "description": "Address Resolution Protocol (ARP) is a network protocol used to map IP addresses to fixed MAC addresses over a network. This subject represents ARP traffic related activities.",
    "fields": {
      "src_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "src_mac": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "operation": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      },
      "dest_ip": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_mac": {
        "core": "0",
        "detection": "0",
        "informational": "1"
      }
    }
  },
  "certificate": {
    "description": "A digital certificate is an object that is used to prove the authenticity of a device, server, or user through the use of cryptography",
    "fields": {}
  },
  "ip": {
    "description": "The IP subject represents an IP record\\object used by assignment servers to manage IP assignments and dispensation. ",
    "fields": {}
  },
  "port": {
    "description": "The physical port (or network device port) subject describes a port outlet on network devices and their digital representation on apps such as switches or NACs.",
    "fields": {}
  },
  "smtp": {
    "description": "Simple Mail Transfer Protocol (SMTP) is a network protocol used for email transmission. This subject represents SMTP traffic related activities.",
    "fields": {
      "src_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "dest_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "ssl": {
    "description": "Secure Socket Layer (SSL) is a network protocol used to provide encryption security over a computer network (now replaced with TLS). This subject represents SSL traffic related activities.",
    "fields": {
      "src_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "dest_ip": {
        "core": "1",
        "detection": "1",
        "informational": "0"
      },
      "src_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      },
      "dest_port": {
        "core": "0",
        "detection": "1",
        "informational": "0"
      }
    }
  },
  "clipboard": {
    "description": "A clipboard is an endpoint object that is used as a buffer that store short-term information in activities such as 'copy' and 'cut'.",
    "fields": {}
  },
  "ds": {
    "description": "The directory service (DS) subject represents a directory service interface and contains activities that are unique to the DS system",
    "fields": {}
  },
  "script": {
    "description": "A script is a human readable representation of a coding langauge, which is executed by interpretes or compilers rather the directly by a machine.",
    "fields": {}
  },
  "link": {
    "description": "A link (shell link\\hard link\\soft link...) is an endpoint object used to redirect to another endpoint object whenever accessed. For example - a file shortcut.",
    "fields": {}
  }
},
```
