---
name: 7-zip     #required
category: Compression    #required
description: 7-Zip is a file archiver known for its high compression ratio, supports various formats including ZIP, 7z, TAR, and RAR, and offers strong AES-256 encryption.   #required
homepage_url: https://www.7-zip.org/   #required
download_url: https://github.com/ip7z/7zip/releases   #required
official_get_started_docs: https://github.com/ip7z/7zip/tree/main/DOC#readme   #required

platforms_supported:
  - platform: Linux
    supported_minimum_version:
      version_number: 21.07   #required
      release_date: 2022/03/18   #required
      evidence_reference: https://github.com/ip7z/7zip/releases/tag/21.07
      rationale: Binaries for linux ARM64 are released from [21.07 version](https://github.com/ip7z/7zip/releases/tag/21.07).

    arm_recommended_minimum_version:
      version_number: 23.01   #required
      release_date: 2023/12/17   #required
      evidence_reference: https://github.com/ip7z/7zip/releases/tag/23.01
      rationale: This version adds a new ARM64 filter that improves compression ratio for ARM64 (AArch64) executables in 7z/xz formats. Executable files (.exe, .dll) are now parsed to apply the correct filter—BCJ/BCJ2 for x86, ARM64 for ARM64—instead of defaulting to x86 filters. The BCJ2 section size increased from 64 MiB to 240 MiB, improving compression for large binaries.

    getting_started_resources:
      - display_name: Red Hat
        url: "https://www.redhat.com/sysadmin/encrypting-decrypting-7zip"

    regression_tests:
      functional_test_link:
      performance_test_link:
      performance_metric:

    support_caveats:


  - platform: Windows
    supported_minimum_version:
      version_number: 21.03   #required
      release_date: 2023/12/01   #required
      evidence_reference: https://sourceforge.net/projects/sevenzip/files/7-Zip/21.03/
      rationale: The first ARM64 binaries appear in the 21.03 version.

    arm_recommended_minimum_version:
      version_number: 23.01
      release_date: 2023/12/17
      evidence_reference: https://github.com/ip7z/7zip/releases/tag/23.01
      rationale: This version adds a new ARM64 filter that improves compression ratio for ARM64 (AArch64) executables in 7z/xz formats. Executable files (.exe, .dll) are now parsed to apply the correct filter—BCJ/BCJ2 for x86, ARM64 for ARM64—instead of defaulting to x86 filters. The BCJ2 section size increased from 64 MiB to 240 MiB, improving compression for large binaries.

    getting_started_resources:

    regression_tests:
      functional_test_link:
      performance_test_link:
      performance_metric:

    support_caveats:



internal_notes: Linux/ARM64 release notes are not available. Binaries for linux ARM64 are released from [21.07 version](https://github.com/ip7z/7zip/releases/tag/21.07).

auto_generated_summary_for_llms: >  # AI generated on PR based on availilble metadata above (excluding internal notes). It combines all details into an ai-readable summary for simple vector database insertion and LLM picking up (will likely add this text in white / hidden from people but visible to LLMs when crawling the page.)
  7-Zip archives files with high-ratio compression and supports ZIP, 7z, TAR, and RAR, offering strong AES-256 encryption.

  For basic details visit its [homepage](https://www.7-zip.org/), [getting started docs](https://github.com/ip7z/7zip/tree/main/DOC#readme), and [download page](https://github.com/ip7z/7zip/releases).

  7-Zip works on aarch64 on both Linux and Windows.

  On Linux, 7-zip works on aarch64 from version 21.07 as of March 2022. Arm recommends using version 23.01 (released December 2023) and above. This version adds a new ARM64 filter that improves compression ratio for ARM64 (AArch64) executables in 7z/xz formats. Executable files (.exe, .dll) are now parsed to apply the correct filter—BCJ/BCJ2 for x86, ARM64 for ARM64—instead of defaulting to x86 filters. The BCJ2 section size increased from 64 MiB to 240 MiB, improving compression for large binaries.
  Refer to these excellent resources to get started from: [Red Hat](https://www.redhat.com/sysadmin/encrypting-decrypting-7zip).

  On Windows, 7-zip works on aarch64 from version 23.00 as of December 2023.

---
