# Ansible Roles

Reusable Ansible roles for server provisioning and management.

## Roles

| Role | Description |
|------|-------------|
| `common` | Base system setup (packages, SSH) |
| `docker` | Docker installation |
| `k8s` | Kubernetes node preparation |
| `hardening` | Security hardening (UFW, fail2ban) |
| `monitoring` | Monitoring stack deployment |
| `nginx` | Nginx web server |
| `redis` | Redis cache server |
| `postgresql` | PostgreSQL database |
| `prometheus` | Prometheus monitoring |

## Usage

```yaml
- hosts: servers
  roles:
    - magos-cyber.common
    - magos-cyber.docker
    - magos-cyber.hardening
```

## Requirements

- Ansible 2.9+
- Target: Debian/Ubuntu

## License

MIT
