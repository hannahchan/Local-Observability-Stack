# Local Observability Stack

The _Local Observability Stack_ is based around an [OpenTelemetry Collector](https://opentelemetry.io/docs/collector) and is meant to help you develop and test observable applications on your local machine.

Spin up the local stack using [Docker Compose](https://docs.docker.com/compose) and then configure your application to send telemetry (currently only metrics and traces) to the OpenTelemetry Collector.

Then view your collected telemetry using Grafana at <http://localhost:3000>.

The stack uses [Prometheus](https://prometheus.io) for storing metrics and [Jaeger](https://www.jaegertracing.io/) for storing traces.

You will probably need to configure the OpenTelemetry Collector or the rest of the local stack to suit your application.

## Quick Links

- [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector)
- [OpenTelemetry Collector Contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib)
- [OpenTelemetry Collector Releases](https://github.com/open-telemetry/opentelemetry-collector-releases)
