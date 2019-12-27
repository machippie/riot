
## Default Variables

### riot_started

Restart app if already running

#### Default value

```yaml
riot_started: true
```

### riot_user

User to run user-specific commands

#### Default value

```yaml
riot_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
