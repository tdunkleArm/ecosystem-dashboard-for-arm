---
name: MySQL
category: Database
description: MySQL is an open-source relational database management system.
download_url: https://dev.mysql.com/downloads/
works_on_arm: true

platforms-supported:
  - platform: Linux
    supported_minimum_version:
      version_number: 8.0.23
      release_date: 2021/01/18

    arm_recommended_minimum_version:
      version_number: 8.0.38
      release_date: 2024/07/01
      reference_content: https://dev.mysql.com/doc/relnotes/mysql/8.0/en/news-8-0-38.html
      rationale: From this verson onwards, Linux aarch64 platform binaries are built using patchelf --page-size=65536 for compatibility with systems using either 4k or 64k for the page size.

    getting_started_resources:
      arm_content: https://learn.arm.com/learning-paths/servers-and-cloud-computing/mysql/install_mysql/
      partner_content:
      official_docs: https://dev.mysql.com/doc/mysql-apt-repo-quick-guide/en/

  - platform: Windows
    supported_minimum_version:
      version_number:
      release_date:

    arm_recommended_minimum_version:
      version_number: 8.0.38
      release_date: 2024/07/01
      reference_content: https://dev.mysql.com/doc/relnotes/mysql/8.0/en/news-8-0-38.html
      rationale: From this verson onwards, Linux aarch64 platform binaries are built using patchelf --page-size=65536 for compatibility with systems using either 4k or 64k for the page size.

    getting_started_resources:
      arm_content:
      partner_content:
      official_docs:

optional_info:
  homepage_url: https://www.mysql.com/
  support_caveats: On Oracle Linux 7, ARM64 requires the Oracle Linux 7 Software Collections Repository which can be installed following the commands as mentioned [here](https://dev.mysql.com/doc/mysql-repo-excerpt/8.3/en/linux-installation-yum-repo.html)
  alternative_options: null
optional_hidden_info:
  release_notes__supported_minimum: https://dev.mysql.com/doc/relnotes/mysql/8.0/en/news-8-0-23.html
  release_notes__recommended_minimum: null
  other_info: null
---
