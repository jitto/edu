---
title: "git Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the git Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-08 00:48:55
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/git/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/git/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/git/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/git/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)                  | Last Changed | Digest                                                                    |
|--------------------------|--------------|---------------------------------------------------------------------------|
|  `latest-root`           | June 7th     | `sha256:0dde5e240871a275a4338f4a21cc8d0cd75e9bb4ace2a95d23b45dd11b327426` |
|  `latest`                | June 7th     | `sha256:e997fbfd8fffa0d2101dfb827815af52f22c10414e561f600cb6357a327d8eb4` |
|  `latest-dev`            | June 7th     | `sha256:2432ca10915c0a05df0305589d03baa72c2745af88930ce3107439c82eccc75f` |
|  `latest-root-dev`       | June 7th     | `sha256:ba6d7344ea902b6b19706690774113f96a92cf84ea0ee5e0cc84526f6c63ea6f` |
|  `latest-glibc-root`     | June 5th     | `sha256:76602dcf3b1ccd18b84daa7de94cfb78225d3a731f7fa21df314ab06770fc62a` |
|  `latest-glibc-root-dev` | June 5th     | `sha256:c2512b90d829c9902f1d9a0bbcd8d08b7857d13ffcf04e1852579dc6c83afcdb` |
|  `latest-glibc-dev`      | June 5th     | `sha256:e3ffb8ddfa4c0e77084502839d8effd3a8945717e570777ee2b2edf6ed16788d` |
|  `latest-glibc`          | June 5th     | `sha256:f47585c02270b5c600d6b7a8696818ccaad0eb0135ac558c2e5b39353b66b7e9` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                                                                                                                                    | Last Changed | Digest                                                                    |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `2` `glibc-2.45` `latest` `latest-glibc` `2.45.2` `2.45` `glibc-2.45.2` `glibc-2`                                                                         | June 5th     | `sha256:5a5c10f7896d6f228698bf007faceec1cc2e1a3a9a07413318d5b5443db68735` |
|  `latest-glibc-dev` `glibc-2.45-dev` `2.45.2-dev` `2-dev` `2.45-dev` `glibc-2.45.2-dev` `latest-dev` `glibc-2-dev`                                         | June 5th     | `sha256:cf80e339edbbf2988a06090e5ebd35e949f4101db526749e5c1a491acf732b13` |
|  `latest-glibc-root` `glibc-root-2` `latest-root` `root-2.45` `root-2.45.2` `glibc-root-2.45` `root-2` `glibc-root-2.45.2`                                 | June 5th     | `sha256:6e20f69b45128e6cd61129d3641a2631c85046297b5a6606391dd782d5d267a8` |
|  `glibc-root-2.45.2-dev` `latest-root-dev` `glibc-root-2-dev` `root-2.45-dev` `root-2-dev` `latest-glibc-root-dev` `glibc-root-2.45-dev` `root-2.45.2-dev` | June 5th     | `sha256:1f59b6afe2d9804260f09992fa3273b26f5e5006abfb64e2202eb7511f7441a3` |

