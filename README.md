# Sample Playbook For Nginx / PHP-FPM Tuning

- Built for CentOS 7.x
- Nginx 1.6.2 from official Nginx repo
- PHP 5.6 from Remi's repo

# Performance tweaks:

- PHP opcode cache enabled

Note: This playbook does not necessarily follow best practices or make any attempt at reusable roles. It is merely a simple way of demonstrating some of my performance and scalability tips.

# How to use it

* Clone this repository locally
* Spin up the machines you want to test (use CentOS 7)
* Edit `inventory/hosts_production with the IP's of your machines

```bash
ansible-playbook -u root -i inventory/hosts_production playbooks/site.yml
```
