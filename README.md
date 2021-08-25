- [About](#about)
- [Installation](#installation)
- [Defaults & Variables](#defaults--variables)

# About

Ansible role to do a variety of system related tasks such as changing hostnames, mounting disks, changing timezone, etcetera.

# Installation

The following would be enough to trigger everything. Optionally, you can overrule certain variables.

``` yml
include:
  remote: "https://gitlab.com/carbonique/gitlab-ci-templates/-/raw/main/ansible/deploy/ansible-deploy-template.yml"

```

For system wide installation:
`ansible-galaxy install -r requirements.yml`

For installation to the current directory:
`ansible-galaxy install --roles-path . -r requirements.yml`

# Defaults & Variables

Variables have to be added by user
For variables see: `vars/main.yml`