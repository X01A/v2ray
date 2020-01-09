## indexyz.v2ray

Deploy v2ray quickly

### Requirements

Systemd should using systemd as init. If tls enabled, the port 80 should not used.

### Role Variables

> TODO

## Example Playbook
----------------
```yaml
- hosts: servers
  roles:
    - role: indexyz.v2ray
      users:
      - email: indexyz@protonmail.com
        alterId: 2
        id: fb9afa10-5818-4903-bd15-e819197db2ef
        level: 0

      port: 32567
      network: tcp
      tls:
        enable: true
        hostname: example.com
```

### License
MIT
