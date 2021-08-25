- [About](#about)
- [Installation](#installation)
- [Defaults & Variables](#defaults--variables)

# About

Ansible role to do a variety of system related tasks such as changing hostnames, mounting disks, changing timezone, etcetera.

# Installation

Add the following to `requirements.yml`:

```
- src: git@gitlab.com:carbonique/ansible-role-system.git
  scm: git
  name: system
  version: #Leave empty for latest. To download a specific version: use the tag as listed in repo
```

For system wide installation:
`ansible-galaxy install -r requirements.yml`

For installation to the current directory:
`ansible-galaxy install --roles-path . -r requirements.yml`


# Defaults & Variables

Variables have to be added by user
For variables see: `vars/main.yml`