# Autodeploy
Ansible tool to autodeploy my current environment.

Use ansible-pull or Run the ansible-run script to install ansible and autodeploy the environment

You can use --tags or --skip-tags with ansible-playbook to skip or install only selected tasks
## Sandbox
There is a sandbox environment using docker to make changes without destroying my configs.
- Setup: Run the setup script
- Test: Run the run-sandbox script. When inside run the setup script
