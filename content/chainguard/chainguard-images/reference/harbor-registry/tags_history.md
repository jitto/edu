---
title: "harbor-registry Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the harbor-registry Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-06 00:48:16
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/harbor-registry/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/harbor-registry/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/harbor-registry/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/harbor-registry/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 5th     | `sha256:c74050b27410cba503c043c417abfffdc5398a471d0eaaca533f987a9c6fe7a6` |
|  `latest`     | June 5th     | `sha256:b0a4c307c3c3dd89468c8dc38ef4bfe7cfebd798b890db521dfae22c7be6490e` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                            | Last Changed | Digest                                                                    |
|----------------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` `3-dev` `3.0.0_alpha1-dev` `3.0-dev` | June 5th     | `sha256:aef5e54ee0a18f22570fda562c6fff6a151a2ff40f9622883b49ea20e730cfde` |
|  `3.0.0_alpha1` `3.0` `3` `latest`                 | June 5th     | `sha256:5efd7ea5a8783f3d1c89dda9bdac088a55639f69a2f0eb2fe4c061e5371d6c17` |

