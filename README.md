# Setup age

This action sets up [age](https://github.com/FiloSottile/age) and adds it to the PATH.

## Usage

Basic:

```yaml
steps:
  - uses: Xestrada/setup-age-action@v1.0.4
```

Specific version:

```yaml
steps:
  - uses: Xestrada/setup-age-action@v1.0.4
    with:
      version: 1.0.0-rc.3
```
