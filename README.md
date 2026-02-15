# Basic Linux Configuration

## Features

- Block all INPUT chain ports using iptables, leaving only icmp, 22, 80, and 443 open.
- Create two users: admin user and ans user. Subsequent playbooks will be executed through ans. Grant them the sudo role.
- Pass the SSH key to the admin.
- Install Docker from its repository.
