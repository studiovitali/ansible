# Ansible Collection

Opinionated set of roles to configure reasonable defaults for newly provisioned Debian / Ubuntu VMs running Docker. The repository provides:
- An Ansible Collection (`studio.ansible`) containing reusable roles. Use with ansible-galaxy's `requirements.yml`.
- A ready-to-use playbook configured by passing CLI vars `--extra-vars "ansible_host=${HOST_IP}` e.g. through CI / CD.
