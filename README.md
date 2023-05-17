# ansible_playbooks

This repository is meant to gather useful independent and idempotent playbooks that you can copy and use in your Ansible environment.
All playbooks will use built-in roles.

# Playbook list

 - docker_install.yml: Installs docker-ce and the docker-compose plugin on your hosts, following the official requirements(https://docs.docker.com/engine/install/). OS supported Debian and Ubuntu.
 - tailscale_install.yml: Installs tailscale on your hosts, following the official tailscale requirements (https://tailscale.com/kb/1031/install-linux/). OS supported Debian and Ubuntu.