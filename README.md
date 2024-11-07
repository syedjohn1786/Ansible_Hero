# Ansible_Hero
This Repository will have Ansible related information and tasks

Password-less authentication:
1. On the control node, log in as root user i.e sudo su
2. Next , run the command : ssh-copy-id -f "-o IdentityFile <path_to_pem_file>" ubuntu@<ip-address-managed-node>
3. You will be connected to the managed node.
4. give exit, and now try to login using command : ssh ubuntu@<ip-address-managed-node>



