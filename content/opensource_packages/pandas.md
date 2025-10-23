---
name: Pandas
category: Miscellaneous
description: Pandas is a powerful open-source Python library used for data manipulation and analysis.
download_url: https://github.com/pandas-dev/pandas/releases
works_on_arm: true

platforms-supported:
  - platform: Linux
    supported_minimum_version: 
      version_number: 1.1.5
      release_date: 2020/12/07

    arm_recommended_minimum_version:
      version_number:
      release_date:
      reference_content:
      rationale:

    getting_started_resources:
      arm_content: 
      partner_content: 
      official_docs: "https://pandas.pydata.org/docs/getting_started/install.html"

  - platform: Windows
    supported_minimum_version: 
      version_number:
      release_date:

    arm_recommended_minimum_version:
      version_number:
      release_date:
      reference_content:
      rationale:

    getting_started_resources:
      arm_content: 
      partner_content: 
      official_docs:

optional_info:
    homepage_url: https://pandas.pydata.org/
    support_caveats:
    alternative_options: 

optional_hidden_info:
    release_notes__supported_minimum: 
    release_notes__recommended_minimum: 
    other_info: There are no release notes or binaries present for Linux/ARM64. Pandas version 1.1.5 is installed and tested on the Neoverse N1, using steps mentioned [here](https://pandas.pydata.org/docs/getting_started/install.html). [This PR](https://github.com/pandas-dev/pandas/pull/30641) confirms the support for Linux/ARM64.

---
