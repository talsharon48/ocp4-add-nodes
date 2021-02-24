Review the tasks defined in the playbook. Ansible updates the worker Igntion file with
a new certificate from api-int.ocp4.example.com, copies the PXE files to paths
without the "-NOOP" suffix, and restarts the TFTP socket. The final playbook tasks
update the HAProxy configuration to include the new workers
