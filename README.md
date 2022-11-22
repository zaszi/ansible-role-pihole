# Ansible Role: Pihole

Deploys and configures [Pi-hole](https://pi-hole.net/).

## Requirements

To install Arch Linux packages, this role relies on the pacman module of the community general collection. Install it with `ansible-galaxy collection install community.general`.

## Role Variables

None.

## Dependencies

This role requires my [ansible-role-nginx](https://github.com/zaszi/ansible-role-nginx) to be run previous to this.

## Example Playbook

    - hosts: all
      become: true
      roles:
         - ansible-role-pihole

## License

Ansible-role-pihole is licensed under the [MIT license](LICENSE).
