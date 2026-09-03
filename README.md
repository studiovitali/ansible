# Ansible Collection

Opinionated set of roles to configure reasonable defaults for newly provisioned virtual machines. The repository provides:
- An Ansible Collection (`studio.ansible`) containing reusable roles. Use with ansible-galaxy's `requirements.yml`.
- A ready-to-use playbook configured by passing CLI vars `--extra-vars "ansible_host=${HOST_IP}` locally or through CI / CD.

Currently only supports Debian-based systems.

