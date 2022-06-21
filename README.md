# Jenkins-to-Buildkite Environment Variable Mapping Plugin

Maps some Buildkite env vars to their Jenkins equivilents, so that they can be referenced from Jenkins build scripts that you're migrating over.

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - command: "./build.sh"
    plugins:
      - mkmrgn/jenkins-env-vars#v1.0.0: ~
```

## Contributing

1. Fork the repo
2. Make the changes
3. Commit and push your changes
4. Send a pull request
