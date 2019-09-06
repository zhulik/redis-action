# Redis GitHub Action

This [GitHub Action](https://github.com/features/actions) sets up Redis database.

# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: zhulik/redis-action@v1
  with:
    redis version: '5'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
