# renovate-test

dry-run

```
LOG_LEVEL=debug \
      RENOVATE_CONFIG_FILE=renovate.json \
      renovate \
        --token $GH_TOKEN \
        --dry-run \
        --schedule= \
        --require-config=ignored \
        karahiyo/renovate-test
```
