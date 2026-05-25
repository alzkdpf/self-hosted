# self-hosted

Sentry, feature-complete and packaged up for low-volume deployments and proofs-of-concept

## Overview

- Repository: [alzkdpf/self-hosted](https://github.com/alzkdpf/self-hosted)
- Visibility: Public
- Last updated: 2022-01-20
- Main stack: Shell, Docker

## Project Structure

```text
.craft.yml
.editorconfig
.env
.gitattributes
.github/ISSUE_TEMPLATE/config.yml
.github/ISSUE_TEMPLATE/feature-request.yml
.github/ISSUE_TEMPLATE/problem-report.yml
.github/workflows/issue-routing-helper.yml
.github/workflows/issue-status-helper.yml
.github/workflows/lock.yml
.github/workflows/release.yml
.github/workflows/stale.yml
.github/workflows/test.yml
.gitignore
CHANGELOG.md
LICENSE
README.md
_integration-test/custom-ca-roots/docker-compose.test.yml
_integration-test/custom-ca-roots/setup.sh
_integration-test/custom-ca-roots/teardown.sh
_integration-test/custom-ca-roots/test.py
_integration-test/run.sh
certificates/.gitignore
clickhouse/config.xml
cron/Dockerfile
cron/entrypoint.sh
docker-compose.yml
geoip/GeoLite2-City.mmdb.empty
install/_lib.sh
install/_min-requirements.sh
install/_test_setup.sh
install/bootstrap-snuba.sh
install/build-docker-images.sh
install/check-latest-commit.sh
install/check-minimum-requirements.sh
install/create-docker-volumes-test.sh
install/create-docker-volumes.sh
install/create-kafka-topics.sh
install/dc-detect-version.sh
install/ensure-files-from-examples.sh
install/error-handling.sh
install/generate-secret-key.sh
install/geoip-test.sh
install/geoip.sh
install/install-wal2json.sh
```

## Getting Started

Clone the repository and inspect the tracked files for the current workflow.

Run the common development command:

```bash
docker compose up -d
```

## Notes

- This README was generated from the repository metadata and file structure.
- Update this document when setup steps, deployment targets, or project ownership changes.
