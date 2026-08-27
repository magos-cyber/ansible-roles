# Ansible Roles

Collection of Ansible roles for server hardening, Docker, K8s, and monitoring.

## Roles

| Role | Description |
|------|-------------|
| common/ | Base server setup |
| docker/ | Docker installation |
| k8s/ | Kubernetes node preparation |
| hardening/ | Security hardening |
| monitoring/ | Monitoring stack deployment |

## Usage

```yaml
- hosts: servers
  roles:
    - magos-cyber.common
    - magos-cyber.docker
```
