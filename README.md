# ansible-server-provisioning

This playbook installs and configures the following on Ubuntu:

Graylog sidecar (Graylog)
Node exporter (prometheus)
Filebeats (for Graylog)

Usage:
Enter Required variables in `provisioning-variables.yml` and hosts in `provisioning-hosts.yaml`. Use `ansible-playbook -i provision-hosts.yaml provision-servers.yml -K`

