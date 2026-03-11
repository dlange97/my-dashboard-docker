# my-dashboard-docker/nginx

## Overview

Nginx configuration used as the API gateway layer.

## Contents

- `default.conf` — primary reverse-proxy config for `/api/*` routes.
- `default.conf.simple` — simplified fallback/reference config.

## Purpose

Nginx routes requests to backend microservices and exposes a single API entrypoint on port `8081`.
