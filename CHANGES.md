1.9.0 (2023-03-22)
==================

VERSIONING NOTE: From this release onwards rageshake will be versioned in `x.y.z` format, not `x.y`.

Features
--------

- Add a zero-dependency python script to cleanup old rageshakes. ([\#61](https://github.com/matrix-org/rageshake/issues/61))


Internal Changes
----------------

- Update deployment process to automatically build docker containers and binaries. ([\#70](https://github.com/matrix-org/rageshake/issues/70))


1.8 (2023-01-13)
================

Features
--------

- Add config option to block unknown appplication names. ([\#67](https://github.com/matrix-org/rageshake/issues/67))


Internal Changes
----------------

- Reimplement buildkite linting and changelog in GHA. ([\#64](https://github.com/matrix-org/rageshake/issues/64))


1.7 (2022-04-14)
================

Features
--------

- Pass the prefix as a unique ID for the rageshake to the generic webhook mechanism. ([\#54](https://github.com/matrix-org/rageshake/issues/54))


1.6 (2022-02-22)
================

Features
--------

- Provide ?format=tar.gz option on directory listings to download tarball. ([\#53](https://github.com/matrix-org/rageshake/issues/53))


1.5 (2022-02-08)
================

Features
--------

- Allow upload of Files with a .json postfix. ([\#52](https://github.com/matrix-org/rageshake/issues/52))


1.4 (2022-02-01)
================

Features
--------

- Allow forwarding of a request to a webhook endpoint. ([\#50](https://github.com/matrix-org/rageshake/issues/50))


1.3 (2022-01-25)
================

Features
--------

- Add support for creating GitLab issues. Contributed by @tulir. ([\#37](https://github.com/matrix-org/rageshake/issues/37))
- Support element-android submitting logs with .gz suffix. ([\#40](https://github.com/matrix-org/rageshake/issues/40))


Bugfixes
--------

- Prevent timestamp collisions when reports are submitted within 1 second of each other. ([\#39](https://github.com/matrix-org/rageshake/issues/39))


Internal Changes
----------------

- Update minimum Go version to 1.16. ([\#37](https://github.com/matrix-org/rageshake/issues/37), [\#42](https://github.com/matrix-org/rageshake/issues/42))
- Add documentation on the types and formats of files submitted to the rageshake server. ([\#44](https://github.com/matrix-org/rageshake/issues/44))
- Build and push a multi-arch Docker image on the GitHub Container Registry. ([\#47](https://github.com/matrix-org/rageshake/issues/47))
- Add a /health endpoint that always replies with a 200 OK. ([\#48](https://github.com/matrix-org/rageshake/issues/48))


1.2 (2020-09-16)
================

Features
--------

- Add email support. ([\#35](https://github.com/matrix-org/rageshake/issues/35))


1.1 (2020-06-04)
================

Features
--------

- Add support for Slack notifications. Contributed by @awesome-manuel. ([\#28](https://github.com/matrix-org/rageshake/issues/28))


Internal Changes
----------------

- Update minimum go version to 1.11. ([\#29](https://github.com/matrix-org/rageshake/issues/29), [\#30](https://github.com/matrix-org/rageshake/issues/30))
- Replace vendored libraries with `go mod`. ([\#31](https://github.com/matrix-org/rageshake/issues/31))
- Add Dockerfile. Contributed by @awesome-manuel. ([\#32](https://github.com/matrix-org/rageshake/issues/32))
