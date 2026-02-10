# Basic Linux Configuration

## Possibilities

- Block all INPUT chain ports using iptables, leaving only icmp, 22, 80, and 443 open.
- Create two users: admin and ans. Subsequent playbooks will be executed through ans. Grant them the sudo role.
- Pass the SSH key to the admin.
- Install Docker from its repository.
