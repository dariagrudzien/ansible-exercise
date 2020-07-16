# Ansible playbook to install nginx

This is an example Ansible playbook to update yum packages, install nginx and reboot the host.

## Prerequities

- [Ansible installed](https://docs.ansible.com/ansible/latest/installation_guide/index.html)
- a host machine you are able to ssh into
- a `hosts` file located in root directory following this example:

```sh
[all]
<host name or IP>
```

## Running

```sh
    ansible-playbook nginx.yml -l all
```

