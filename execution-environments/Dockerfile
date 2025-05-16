FROM registry.redhat.io/ansible-automation-platform-25/ee-supported-rhel9:latest

COPY *.tar.gz .

RUN ansible-galaxy collection install community.vmware:4.8.3
RUN ansible-galaxy collection install cloud-vmware_ops-1.9.0.tar.gz

