# Steps to Deploy Prometheus Using Ansible
**1. Clone the Repository:**
```
git clone https://github.com/your_username/prometheus-ansible.git
cd prometheus-ansible
```
**2. Configure Inventory:**

* Edit inventory/production to include the IP addresses or hostnames of the target machines.

**3. Set Up Group Variables:**

* Modify group_vars/prometheus.yml as per your environment's requirements.

**4. Run the Playbook:**
```
ansible-playbook playbooks/site.yml
```