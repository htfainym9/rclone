---
title: "OpenStack Swift"
description: "Rclone docs for OpenStack Swift"
---

# OpenStack Swift

Paths are specified as `remote:container` (or `remote:` for the list of containers).

## Configuration

Here is an example of configuring an OpenStack Swift remote.

First run:

    rclone config

This will guide you through an interactive setup process.

### Options

- `user`: User name for authentication.
- `key`: API key or password.
- `auth`: Authentication URL for your service.
- `tenant`: Tenant name (v1 auth / v2 auth).
- `domain`: Domain name for Identity v3 API.
- `region`: Region name (optional).

For more details on connecting to Swift object storage, refer to your provider's API credentials guide.