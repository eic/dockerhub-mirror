# DockerHub Mirror
DockerHub Mirror on Github powered by Github Actions and [Crane](https://github.com/google/go-containerregistry/tree/main/cmd/crane)

[![GitHub Workflow Status (branch)][github-actions-badge]][github-actions-link]

GitHub Actions scheduled to run daily at Midnight UTC to mirror some images to [GHCR.io](https://ghcr.io), bypassing rate limits

Mirrored Images:
* [`alpine`](https://ghcr.io/eic/alpine)
* [`busybox`](https://ghcr.io/eic/busybox)
* [`curl`](https://ghcr.io/eic/curl)
* [`debian`](https://ghcr.io/eic/debian)
* [`docker`](https://ghcr.io/eic/docker)
* [`golang`](https://ghcr.io/eic/golang)
* [`node`](https://ghcr.io/eic/node)
* [`mysql`](https://ghcr.io/eic/mysql)
* [`openjdk`](https://ghcr.io/eic/openjdk) **DEPRECATED** - docker-library/openjdk#505
* [`postgres`](https://ghcr.io/eic/postgres)
* [`python`](https://ghcr.io/eic/python)
* [`rust`](https://ghcr.io/eic/rust)

[github-actions-badge]: https://img.shields.io/github/actions/workflow/status/eic/dockerhub-mirror/mirror.yml?branch=master "Github Workflow Status (master)"
[github-actions-link]: https://github.com/eic/dockerhub-mirror/actions?query=workflow%3AMirror%20Dockerhub
