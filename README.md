# go-dep-cli-docker
Go dependency management tool cli docker images

## About this project
In my work, I want to build the application develop by go programming language via [Google Cloud Build](https://cloud.google.com/cloud-build/) but cannot install project dependency with ["dep"](https://github.com/golang/dep/).

## Available Go version tags
- 1.11-apline3.7
- 1.11-apline3.8
- 1.11-apline3.9
- 1.11-stretch
- 1.12-apline3.9
- 1.12-stretch

## Example `cloudbuild.yaml` file
```yaml
steps:
- name: 'divergentthinking/go-dep-cli-docker:$GO_VERSION_TAG'
  args: ['ensure']
```
