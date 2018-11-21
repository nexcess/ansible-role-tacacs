# Ansible Role: Containerized TACACS+ Instance

Installs and configures TACACS+ (lfkeitel/tacacs_plus) inside a Docker container. Only usable with Docker Compose version 3.

## Role Variables

See `defaults/main.yml`


## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-tacacs.git
      name: nexcess.tacacs

## Example Playbook

    - hosts: tacacs_hosts
      roles:
        - nexcess.tacacs

## License

MIT
