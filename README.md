# Ansible Role: Let’s Encrypt

Installs the [Let’s Encrypt](https://letsencrypt.org/) client onto any Linux server.

## Dependencies

Requires [Git](http://git-scm.com/) to be installed, but there’s no dependency on any particular role.

Red Hat based distributions require the [EPEL repository](https://fedoraproject.org/wiki/EPEL) to be configured, so that `python-virtualenv` can be installed.

## Role Variables

Available variables are listed below, along with default values (see defaults/main.yml):

    letsencrypt_dir: /opt/letsencrypt

The directory to install Let’s Encrypt into.

## Example Playbook

    - hosts: all
      roles:
        - opdavies.letsencrypt

## License

MIT

## Author

[Oliver Davies](https://www.oliverdavies.uk) - PHP Developer and Linux System Administrator.
