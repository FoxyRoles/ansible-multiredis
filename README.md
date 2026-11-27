# ansible-multiredis

Setups multiple Redis instances on same system.

## Requirements

- `ansible-core` 2.19 or newer.

### Example playbook
```yaml
---
- hosts: myserver
  roles:
    - role: sunfoxcz.multiredis
      redis_instances:
        - name: redis1
          port: 6379
        - name: redis2
          port: 6380
```

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
