# Ansible Role - SSH Keys

Ansible role to import an SSH key ring

Temporary private key in `ssh/id_ed25519`

### Example
```
keystodeploy:
  - name: Pierre C
    sshkey: ssh-ed25519 AAAAC3Nz...
  - name: Mablr
    sshkey: ssh-rsa AAAAB3Nz...
```

### License

GPLv3 - Elukerio

### Author Information

Pierre Coimbra
