- [About](#about)
- [Variables](#variables)

# About

Ansible role to do a variety of system related tasks such as changing hostnames, mounting disks, changing timezone, etcetera.

# Variables

| Variable        | Description                                | Default  | Optional/Required |
|-----------------|--------------------------------------------|----------|-------------------|
| system_hostname | Hostname for the system                    | null     | Required          |
| timezone        | Timezone system should use                 | null     | Required          |
| user_PUID       | UID for the user that owns the mount paths | null     | Required          |
| user_PGID       | GID for the user that own the mount paths  | null     | Required          |
| ssd_mount_path  | Path to mount the ssd to                   | /mnt/ssd | Required          |
| ssd_label       | Label of the ssd                           | ssd      | Required          |
| hdd_mount_path  | Path to mount the hdd to                   | /mnt/hdd | Required          |
| hdd_label       | Label of the hdd                           | hdd      | Required          |