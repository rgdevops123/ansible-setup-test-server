# ansible-setup-test-server

- Setup test servers using Ansible.
- OS: CentOS 7

## Before Install
- Use DNS Server or update /etc/hosts for all test servers.
- Update hosts file.
- Update variables in vars/main.yml.

### Setup Test Server.
- Run the playbook.

```
ansible-playbook -i hosts setup_server.yml
```
