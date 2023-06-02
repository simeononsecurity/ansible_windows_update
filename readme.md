# Ansible Role: windows_update

This role automates Windows security patching using Ansible.

## Requirements

- Windows hosts
- Ansible 2.10 or later

## Role Variables

None

## Dependencies

None

## Example Playbook

```yaml
- name: Apply Windows updates
  hosts: windows_hosts
  become: yes

  roles:
    - windows_update
```

License: MIT

Author Information:
This role was created by SimeonOnecurity.
For more information, visit [SimeonOnecurity.ch](https://simeononecurity.ch).

