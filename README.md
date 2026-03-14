# 41834, 41835, 41836

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

The updates are not being proposed and errors are being logged for invalid version.

The command being run is:

```shell
LOG_LEVEL=debug npx renovate --platform=local > test.log
```

## Expected behavior

i expect the following:

- opentelemetry-helpers-mysql 0.3.0 updated to 0.4.0
- opentelemetry-api 1.7 updated to 1.8
- opentelemetry-common 0.21 updated to 0.23

## Link to the Renovate issue or Discussion

- [Ruby custom manager not handling Pessimistic Version Constraint](https://github.com/renovatebot/renovate/discussions/41834)
- [Ruby custom manager not handling Minimum Version Constraint](https://github.com/renovatebot/renovate/discussions/41835)
- [Custom manager encoding > when in version](https://github.com/renovatebot/renovate/discussions/41836)
