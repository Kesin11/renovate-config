# renovate-config
My renovate config

## USAGE
### My OSS common config.

```json
{
  "extends": [
    "github>Kesin11/renovate-config:oss",
    ":prConcurrentLimit10",
    "schedule:weekends"
  ]
}
```

### Deno
**DEPRECATED** Use https://github.com/Omochice/renovate-config instead.

```json
{
  "extends": [
    "github>Kesin11/renovate-config:deno"
  ]
}
```
