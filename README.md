# k8s lab installation
`ansible-galaxy collection install kubernetes.core`
`ansible-galaxy install -r ~/personal-env/k8s_lab/ansible-requirements.yml`
`ansible-playbook ~/personal-env/k8s_lab/site.yml -i ~/personal-env/k8s_lab/inventory.ini -k -K -u vagrant`
