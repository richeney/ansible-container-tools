# Install Docker on Ubuntu for native CLI use

Ansible role to install Docker in WSL Ubuntu. Still usable as the backend for Docker Desktop.

Also installs kubectl and helm binaries.

## Installation

`ansible-galaxy install richeney.container_tools`

## Example Playbook

```yaml
- hosts: all
  roles:
    - richeney.container_tools
```

## Requirements

None.

## Dependencies

None.
