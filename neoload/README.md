# NeoLoad integration

## Overview

[Tricentis NeoLoad][1] simplifies and scales performance testing for APIs and microservices, as well as end-to-end application testing through protocol and browser-based capabilities.

With the NeoLoad integration, you can track performance metrics of NeoLoad tests to:

- Correlate application performance with load testing metrics.
- Analyze and visualize NeoLoad metrics using the NeoLoad Datadog Dashboard or Metrics Explorer.

## Setup

### Configuration

The Datadog agent is not needed to use the integration.
For the detailed instructions on NeoLoad configuration, follow the [NeoLoad documentation][2].
Additionally, the first time Datadog detects the NeoLoad.Controller.User.Load metric, the NeoLoad integration tile is installed automatically, and the default NeoLoad dashboard is added to your dashboard list.

![NeoLoad Dashboard][7]

## Data Collected

### Metrics

See [metadata.csv][3] for a list of metrics provided by this integration.

### Service Checks

NeoLoad does not include any service checks.

### Events

All NeoLoad performance tests events are sent to your [Datadog Events Explorer][4].
NeoLoad sends events to the Datadog API when a performance test starts and ends.

## Troubleshooting

Need help? Contact [Datadog support][5] or [Tricentis NeoLoad support][6].

[1]: https://www.tricentis.com/products/performance-testing-neoload
[2]: https://documentation.tricentis.com/neoload/latest/en/WebHelp/#Datadog.htm
[3]: https://github.com/DataDog/integrations-extras/blob/master/neoload/metadata.csv
[4]: https://docs.datadoghq.com/events/
[5]: https://docs.datadoghq.com/help/
[6]: https://support-hub.tricentis.com/
[7]: https://raw.githubusercontent.com/DataDog/integrations-extras/master/neoload/images/neoload-dashboard.png

