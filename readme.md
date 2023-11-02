# Ansible Role: windows_update

This role automates Windows security patching using Ansible.

## Requirements

- Windows hosts
- Ansible 2.10 or later

## Role Variables

None

## Dependencies

None

## Installation
```bash
ansible-galaxy install simeononsecurity.windows_update
```

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
This role was created by SimeonOnSecurity.
For more information, visit [SimeonOnSecurity.com](https://simeononsecurity.com).



## [Learn more about Automating Windows Patching with Ansible](https://simeononsecurity.com/guides/automate-windows-patching-and-updates-with-ansible/)
<a href="https://simeononsecurity.com" target="_blank" rel="noopener noreferrer">
  <h2>Explore the World of Cybersecurity</h2>
</a>
<a href="https://simeononsecurity.com" target="_blank" rel="noopener noreferrer">
  <img src="https://simeononsecurity.com/img/banner.png" alt="SimeonOnSecurity Logo" width="300" height="300">
</a>

### Links:
- #### [github.com/simeononsecurity](https://github.com/simeononsecurity)
- #### [simeononsecurity.com](https://simeononsecurity.com)
