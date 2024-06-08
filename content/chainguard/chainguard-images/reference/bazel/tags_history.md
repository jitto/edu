---
title: "bazel Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the bazel Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-08 00:48:55
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/bazel/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/bazel/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/bazel/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/bazel/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest`     | June 7th     | `sha256:21ea1a60c741f7db6dbfdfce619c1627fc3a2bb9b259e790bad023aa9a79a785` |
|  `latest-dev` | June 7th     | `sha256:243becbe120dab22f996df025c54b93594d5e513aa9d4a3b3a64fea8cd1eca05` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                     | Last Changed | Digest                                                                    |
|---------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `5.4.1-dev` `5-dev` `5.4-dev`              | June 7th     | `sha256:f6c115fc0301ac05d7dcd1295db95d1a87a82b17c56559bfe8e25ba3f69afd74` |
|  `7.1-dev` `7-dev` `latest-dev` `7.1.2-dev` | June 7th     | `sha256:ad1d623ae54ed575270247487b56496457b8de3c9f4da9a51f611912b3a60e08` |
|  `7.1` `latest` `7` `7.1.2`                 | June 7th     | `sha256:b094b23e7542a403738a9c44a4b26c008f0e10748e2db0943d8b782e9c769fdd` |
|  `6` `6.5` `6.5.0`                          | June 7th     | `sha256:6d4b59d3ec473c3412a741c073753feee27ba75d161afadd907b5f1697a17409` |
|  `6-dev` `6.5.0-dev` `6.5-dev`              | June 7th     | `sha256:01b30fc0275a813d85e8f804c524d6f5d6320979dfb014d84dbb9e316a39c96a` |
|  `5.4.1` `5` `5.4`                          | June 7th     | `sha256:8f9a44cb499424af6f933bd5b988a710ce019ad2bc9eea0bc90407739a8e4a06` |

