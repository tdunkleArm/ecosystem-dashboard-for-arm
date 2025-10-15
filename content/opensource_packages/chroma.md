---
name: Chroma 
category: Database 
description: Chroma is the AI-native open-source vector database. Chroma makes it easy to build LLM apps by making knowledge, facts, and skills pluggable for LLMs. 
download_url: https://github.com/chroma-core/chroma/releases 
works_on_arm: true

platforms_supported:
  - platform: Linux
    supported_minimum_version:
      version_number: 0.3.27
      release_date: 2023/07/10

    arm_recommended_minimum_version:
      version_number: 1.0.0
      release_date: 2025/04/04
      reference_content: https://www.trychroma.com/project/1.0.0
      rationale: This version introduced new core written in rust, that made the local Chroma 4× faster for common write and query workflows. This isn't Arm-specific, but surely going to benefit all platforms, including Linux/ARM64.

    getting_started_resources:
      arm_content:
      partner_content:
      official_docs: https://docs.trychroma.com/

optional_info:
    homepage_url: https://www.trychroma.com/
    support_caveats:
    alternative_options:

optional_hidden_info:
    release_notes__supported_minimum:
    release_notes__recommended_minimum:
    other_info:
---
