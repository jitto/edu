---
title: "prometheus-logstash-exporter Image Variants"
type: "article"
unlisted: true
description: "Detailed information about the public prometheus-logstash-exporter Chainguard Image variants"
date: 2024-02-08 00:18:32
lastmod: 2024-02-08 00:18:32
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 550
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/prometheus-logstash-exporter/" >}}
{{< tab title="Variants" active=true url="/chainguard/chainguard-images/reference/prometheus-logstash-exporter/image_specs/" >}}
{{< tab title="Tags History" active=false url="/chainguard/chainguard-images/reference/prometheus-logstash-exporter/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/prometheus-logstash-exporter/provenance_info/" >}}
{{</ tabs >}}

This page shows detailed information about all public variants of the Chainguard **prometheus-logstash-exporter** Image.

## Variants Compared
The **prometheus-logstash-exporter** Chainguard Image currently has 2 public variants: 

- `latest-dev`
- `latest`

The table has detailed information about each of these variants.

|              | latest-dev                   | latest                       |
|--------------|------------------------------|------------------------------|
| Default User | `nonroot`                    | `nonroot`                    |
| Entrypoint   | `/usr/bin/logstash-exporter` | `/usr/bin/logstash-exporter` |
| CMD          | not specified                | not specified                |
| Workdir      | not specified                | not specified                |
| Has apk?     | yes                          | no                           |
| Has a shell? | yes                          | no                           |

Check the [tags history page](/chainguard/chainguard-images/reference/prometheus-logstash-exporter/tags_history/) for the full list of available tags.

## Packages Included
The table shows package distribution across variants.

|                          | latest-dev | latest |
|--------------------------|------------|--------|
| `apk-tools`              | X          |        |
| `bash`                   | X          |        |
| `busybox`                | X          |        |
| `ca-certificates-bundle` | X          | X      |
| `git`                    | X          |        |
| `glibc`                  | X          | X      |
| `glibc-locale-posix`     | X          | X      |
| `ld-linux`               | X          | X      |
| `libbrotlicommon1`       | X          |        |
| `libbrotlidec1`          | X          |        |
| `libcrypt1`              | X          |        |
| `libcrypto3`             | X          |        |
| `libcurl-openssl4`       | X          |        |
| `libexpat1`              | X          |        |
| `libidn2`                | X          |        |
| `libnghttp2-14`          | X          |        |
| `libpcre2-8-0`           | X          |        |
| `libpsl`                 | X          |        |
| `libssl3`                | X          |        |
| `libunistring`           | X          |        |
| `logstash-exporter`      | X          | X      |
| `ncurses`                | X          |        |
| `ncurses-terminfo-base`  | X          |        |
| `openssl-config`         | X          |        |
| `wolfi-baselayout`       | X          | X      |
| `zlib`                   | X          |        |
