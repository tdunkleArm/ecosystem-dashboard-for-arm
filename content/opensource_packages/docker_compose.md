---
name: Docker-Compose
category: Containers and Orchestration
description: Docker Compose is a tool that uses a single configuration file to define and run multi-container applications.
download_url: https://github.com/docker/compose/releases
works_on_arm: true

platforms-supported:
  - platform: Linux
    supported_minimum_version:
      version_number: 2.0.0
      release_date: 2021/09/28

    arm_recommended_minimum_version:
      version_number: null
      release_date: null
      reference_content: null
      rationale: null

    getting_started_resources:
      arm_content: null
      partner_content:
      official_docs: https://docs.docker.com/compose/install/

  - platform: Windows
    supported_minimum_version:
      version_number:
      release_date:

    arm_recommended_minimum_version:
      version_number: null
      release_date: null
      reference_content: null
      rationale: null

    getting_started_resources:
      arm_content: null
      partner_content:
      official_docs:

optional_info:
  homepage_url: https://docs.docker.com/compose/
  support_caveats: null
  alternative_options: null
optional_hidden_info:
  release_notes__supported_minimum: null
  release_notes__recommended_minimum: null
  other_info: There are no release notes for Linux/ARM64. However, the first docker compose binary for Linux/ARM64 is available in version 2.0.0 at GitHub releases [here](https://github.com/docker/compose/releases/tag/v2.0.0).
---
