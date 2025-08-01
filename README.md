# This is about to Configuration As Code job on AWX

```bash
# Clone the git repository 
git clone https://github.com/srinivassrinu842/aap-demo.git
cd aap-demo
```

```bash
# review the vars files
cd vars
ls -lrt
```

```bash
# Run the awx-launch playbook
ansible-playbook awx-launch.yaml -J  # provide the vault password for controller.yaml
```
