# OIDC Token

A [Buildkite plugin](https://buildkite.com/docs/plugins) to request a Buildkite OIDC token.

## Usage

Use the plugin in your steps like this:

```yaml
steps:
  - command: script/test
    plugins:
    - sj26/oidc-token
```

This will make a `$BUILDKITE_OIDC_TOKEN` available in your job's command, or subsequent plugins.
