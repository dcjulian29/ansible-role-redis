# Ansible Role: redis

[![Lint](https://github.com/dcjulian29/ansible-role-redis/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-redis/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-redis.svg)](https://github.com/dcjulian29/ansible-role-redis/issues)

This an Ansible role to install a container running Redis.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.redis
  src: https://github.com/dcjulian29/ansible-role-redis.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
