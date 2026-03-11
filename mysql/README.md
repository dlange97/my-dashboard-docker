# my-dashboard-docker/mysql

## Overview

MySQL setup for local development.

## Contents

- `init.sql` — database initialization script for all required service databases.

## Behavior

`init.sql` is mounted by Docker Compose into `/docker-entrypoint-initdb.d/` and executed automatically on the first MySQL container startup.
