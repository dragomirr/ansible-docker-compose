# Ansible docker-compose role

## Requirements

None.

## Role Variables

  * `docker_compose_version` -- version of docker-compose to install

## Dependencies

None.

## Example Playbook

```yaml
- hosts: docker
  become: yes

  roles:
    - dragomirr.docker_compose
```

## License

GPLv3
