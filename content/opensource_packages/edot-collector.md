---
name: Elastic Distribution of OpenTelemetry (EDOT) Collector
category: Monitoring/Observability
description: Elastic Distribution of OpenTelemetry Collector, a component of EDOT, is Elastic’s open-source distribution of the OpenTelemetry Collector, providing production-ready components for collecting, processing, and exporting observability data in Agent or Gateway modes.
download_url: https://www.elastic.co/docs/reference/opentelemetry/edot-collector/download
works_on_arm: true

platforms-supported:
  - platform: Linux
    supported_minimum_version:
      version_number: 7.12.0
      release_date: 2021/03/23

    arm_recommended_minimum_version:
      version_number:
      release_date:
      reference_content:
      rationale:

    getting_started_resources:
      arm_content:
      partner_content:
      official_docs: https://www.elastic.co/docs/reference/opentelemetry/edot-collector/config/

optional_info:
    homepage_url: https://www.elastic.co/docs/reference/opentelemetry/edot-collector
    support_caveats: The Elastic Distribution of OpenTelemetry (EDOT) Collector is embedded in the Elastic Agent package as a separate binary that invokes OpenTelemetry Collector components.
    alternative_options:
 
optional_hidden_info:
    release_notes__supported_minimum:
    release_notes__recommended_minimum:
    other_info: The Elastic Distribution of OpenTelemetry (EDOT) Collector is embedded in the Elastic Agent package as a separate binary that invokes OpenTelemetry Collector components. Elastic agent started rolling out Linux/Arm64 artifacts from version 7.12.0 onwards.
 
---
