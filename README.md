# hetzner-dns-action

Setup Hetzner's DNS server for systemd.

Usage:

```yaml
steps:
    - uses: self-actuated/hetzner-dns-action@master
```

With an overridden DNS entry:

```yaml
steps:
  - name: Setup DNS
    uses: self-actuated/hetzner-dns-action@master
    with:
      dns: 8.8.8.8
```
