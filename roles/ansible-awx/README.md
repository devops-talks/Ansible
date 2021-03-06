# ansible-awx

An [Ansible](https://www.ansible.com) role to install [AWX](https://github.com/ansible/awx)

> NOTE: AWX provides a web-based user interface, REST API, and task engine built
> on top of Ansible. It is the upstream project for Tower, a commercial derivative
> of AWX.

## Requirements

-   [ansible-docker](https://github.com/mrlesmithjr/ansible-docker)

You can install required Ansible roles by running:

```bash
ansible-galaxy install -r requirements.yml
```

-   [resources](https://github.com/ansible/awx/blob/devel/INSTALL.md#system-requirements)

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

Reference [requirements](#requirements)

## Example Playbook

[playbook.yml](playbook.yml)

# Usage

Login to AWX dashboard by accessing `http://HostnameOrIP` and login with `user:pass`
defined in [defaults/main.yml](defaults/main.yml) under:

-   user: `awx['default_admin_user']`
-   pass: `awx['default_admin_password']`

## License

MIT

## Author Information

Larry Smith Jr.

-   [EverythingShouldBeVirtual](http://www.everythingshouldbevirtual.com)
-   [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
-   mrlesmithjr [at] gmail.com
