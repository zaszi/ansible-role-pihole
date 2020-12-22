# Ansible Role: Pihole

Deploys and configures [Pi-hole](https://pi-hole.net/).

## Requirements

To install Arch Linux packages, this role relies on the pacman module of the community general collection. Install it with `ansible-galaxy collection install community.general`.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      become: true
      roles:
         - ansible-role-pihole

## License

Ansible-role-pihole is licensed under the [MIT license](https://github.com/zaszi/ansible-role-pihol/blob/master/LICENSE).
