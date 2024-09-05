# Ansible For Jenkins Server Configuration

This directory installs and configures Jenkins on a Debian-based system.

## Variables

- `jenkins_version`: Version of Jenkins to install.
- `jenkins_home`: Jenkins home directory.

## Execution
To run the playbook, navigate to the *jenkins-server* directory and execute:
```
ansible-playbook playbooks/install_jenkins.yml
```