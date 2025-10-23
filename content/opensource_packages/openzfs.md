---
name: OpenZFS
category: Storage
description: OpenZFS is a free, open-source storage solution that ensures data safety and performance with features like snapshots, compression, and replication.
download_url: https://github.com/openzfs/zfs/releases
works_on_arm: true

platforms-supported:
  - platform: Linux
    supported_minimum_version:
      version_number: 0.6.3
      release_date: 2015/04/10

    arm_recommended_minimum_version:
      version_number: 2.2.4
      release_date: 2024/05/03
      reference_content: "https://github.com/openzfs/zfs/releases/tag/zfs-2.2.4"
      rationale: This version adds the BTI elf note to the AArch64 SHA2 assembly.

    getting_started_resources:
      arm_content:
      partner_content:
      official_docs: "https://openzfs.github.io/openzfs-docs/Getting%20Started/Ubuntu/index.html"

optional_info:
    homepage_url: https://openzfs.github.io/openzfs-docs/
    support_caveats:
    alternative_options:

optional_hidden_info:
    release_notes__supported_minimum: https://github.com/openzfs/zfs/releases/tag/zfs-0.6.3
    release_notes__recommended_minimum:
    other_info:
  
---
