# hetzner-dns-action

Setup Hetzner's DNS server for systemd on an Ubuntu 20.04 or 22.04 host.

Usage:

```yaml
steps:
    - uses: self-actuated/hetzner-dns-action@v1
```

With an overridden DNS entry, (if it is reachable from your host):

```yaml
steps:
  - name: Setup DNS
    uses: self-actuated/hetzner-dns-action@v1
    with:
      dns: 8.8.8.8
```
