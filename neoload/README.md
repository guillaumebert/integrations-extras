# NeoLoad integration

## Overview

[Tricentis NeoLoad][1] simplifies and scales performance testing for everything, from APIs and microservices, to end-to-end application testing through innovative protocol and browser-based capabilities.

With the NeoLoad bi-directional integration, you will be able to augment your performance engineering analysis by :

- Correlating application performance with NeoLoad load testing Metrics and Events.
- Analyze and visualize NeoLoad metrics using the NeoLoad Datadog Dashboard or Metrics Explorer.
- Filter and facet in Datadog on specific NeoLoad tests tags (Test name, Test id etc.)

## Setup

### Configuration

The Datadog agent is not needed to use the integration. NeoLoad integrates with the Datadog platform directly through APIs.
For the detailed instructions on how to activate and configure the integration, follow the [NeoLoad documentation][2].

Additionally, the first time Datadog detects the NeoLoad.Controller.User.Load metric, the NeoLoad integration tile will be installed automatically, and the default NeoLoad dashboard will be added to your dashboard list.

![NeoLoad Dashboard][7]

## Data Collected

### Metrics

See [metadata.csv][3] for a list of metrics provided by this integration.

### Events

All NeoLoad performance tests events are sent to your [Datadog Event Stream][4].
NeoLoad send events to Datadog via the API when a performance test starts and ends.

### Service Checks

NeoLoad does not include any service checks.

## Troubleshooting

Need help? Contact [Datadog support][5] or [Tricentis NeoLoad support][6].

[1]: https://www.tricentis.com/products/performance-testing-neoload
[2]: https://documentation.tricentis.com/neoload/latest/en/WebHelp/#Datadog.htm
[3]: https://github.com/DataDog/integrations-extras/blob/master/neoload/metadata.csv
[4]: https://docs.datadoghq.com/events/
[5]: https://docs.datadoghq.com/help/
[6]: https://support-hub.tricentis.com/
[7]: https://raw.githubusercontent.com/DataDog/integrations-extras/master/neoload/images/neoload-dashboard.png

