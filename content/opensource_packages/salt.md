---
name: Salt
category: DevOps
description: Salt is an open-source automation tool used for configuration management, remote execution, and infrastructure orchestration. It enables scalable system  control through a master-minion or agentless architecture.
download_url: https://pypi.org/project/salt/#history
works_on_arm: true

platforms-supported:
  - platform: Linux
    supported_minimum_version:
      version_number: 2016.3.0
      release_date: 2016/05/26

    arm_recommended_minimum_version:
      version_number:
      release_date:
      reference_content:
      rationale:

    getting_started_resources:
      arm_content:
      partner_content:
      official_docs: "https://docs.saltproject.io/salt/install-guide/en/latest/topics/other-install-types/platform-agnostic.html"

optional_info:
    homepage_url: https://saltproject.io/
    support_caveats:
    alternative_options:

optional_hidden_info:
    release_notes__supported_minimum:
    release_notes__recommended_minimum:
    other_info: There are no Linux/ARM64 release notes. Salt can be installed via pip from version 2016.3.0. Earlier versions fail to get installed via pip.

---
