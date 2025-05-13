# Ansible playbooks for Uptrace

This repository contains playbooks for deploying Uptrace to bare metal servers using Ansible. There
are following playbooks:

- `bootstrap.yml` performs initial configuration.
- `ch_server.yml` deploys ClickHouse Server.
- `pg.yml` deploys PostgreSQL database.
- `redis.yml` deploys Redis database.
- `uptrace.yaml` deploys Uptrace.

See [**Deploying Uptrace with Ansible**](https://uptrace.dev/get/hosted/ansible) for details.
