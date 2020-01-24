# Docker Image for the Docker Publish Semver Github Action

This is a the actual implementation of the [Flownative Github Action for tagging semver Docker images](https://github.com/flownative/action-docker-publish-semver).
The actual Github action refers to a pre-built image in its `Dockerfile`, so that the action image does not have to be
re-built on every use.
