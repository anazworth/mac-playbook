# Run locally

1. `ansible-galaxy install -r requirements.yml`

2. `ansible-playbook main.yaml -K`

# Run locally without cloning the repository

1. Ensure Ansible is installed.

2. Install dependencies:

   ```
   ansible-galaxy install elliotweiser.osx-command-line-tools
   ansible-galaxy collection install geerlingguy.mac
   ```

3. Run `ansible-pull -U https://github.com/anazworth/mac-playbook.git main.yaml -K`
