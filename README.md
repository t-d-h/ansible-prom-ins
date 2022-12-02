# ansible-ins-prom
This is a ansible playbook to install a Prometheus on debian11, amd64 architecture

# Run:

ansible-playbook main.yaml -i inventory --extra-vars "prom_ver"='2.30.3'
