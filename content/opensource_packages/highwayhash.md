---
name: Highwayhash
category: Crypto
description: HighwayHash is a fast, secure hash function designed for speed and security, suitable for use in checksums, hash tables and fingerprinting.
download_url: https://github.com/minio/highwayhash/releases
works_on_arm: true

platforms-supported:
  - platform: Linux
    supported_minimum_version:
      version_number: 1.0.2
      release_date: 2021/03/25

    arm_recommended_minimum_version:
      version_number: 1.0.3
      release_date: 2024/07/04
      reference_content: "https://github.com/minio/highwayhash/releases/tag/v1.0.3"
      rationale: This version adds support for Arm SVE instructions, resulting in the performance improvements over existing NEON implementation.

    getting_started_resources:
      arm_content:
      partner_content:
      official_docs: "https://github.com/minio/highwayhash#installation"

optional_info:
    homepage_url: https://github.com/minio/highwayhash
    support_caveats:
    alternative_options:

optional_hidden_info:
    release_notes__supported_minimum: https://github.com/minio/highwayhash/releases/tag/v1.0.2
    release_notes__recommended_minimum:
    other_info:

---
