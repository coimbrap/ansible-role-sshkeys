# Ansible Role - SSH Keys

Clé privée temporaire encryptée dans `ssh/id_ed25519`

Liste des clés publique

### group_vars/lxc.yml
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
