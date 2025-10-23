---
name: Heketi
category: Storage
description: Heketi is a REST-based volume management service that automates the provisioning and lifecycle of GlusterFS volumes across distributed storage nodes.
download_url: https://github.com/heketi/heketi/releases
works_on_arm: true

platforms-supported:
  - platform: Linux
    supported_minimum_version:
      version_number: 4.0.0
      release_date: 2017/02/15

    arm_recommended_minimum_version:
      version_number:
      release_date:
      reference_content:
      rationale:

    getting_started_resources:
      arm_content:
      partner_content:
      official_docs: "https://github.com/heketi/heketi/tree/master/docs/"

optional_info:
    homepage_url: https://github.com/heketi/heketi
    support_caveats: 
    alternative_options:

optional_hidden_info:
    release_notes__supported_minimum: https://github.com/heketi/heketi/releases/tag/v4.0.0
    release_notes__recommended_minimum:
    other_info: The release notes in version 4.0.0 mentions "Supports builds for Raspberry Pi as well as other architectures". Linux-arm64 heketi binaries are first rolled out in this version.

---
