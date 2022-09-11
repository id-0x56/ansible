## Ansible playbook

- *kubelet, kubeadm, kubectl*
- *docker, docker-compose*
- *curl, git, mc*

### Installation
```
sudo apt update && sudo apt install -y ansible sshpass
```
```
export ANSIBLE_HOST_KEY_CHECKING=False
```

### Configure
```
ansible-playbook main.yml --user=ubuntu --ask-pass --ask-become-pass
```

### Ping
```
ansible all -m ping --user=ubuntu --ask-pass
```

### Usage
*Try it now!*
