# Awesome BEAM Monitoring with stars

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

The curated list of tools for monitoring, instrumenting, and tracing
applications that run on BEAM. Inspired by many of such lists over the GitHub.

## Blog posts

* [Logs and Metrics and Graphs, Oh My!](https://grafana.com/blog/2016/01/05/logs-and-metrics-and-graphs-oh-my/)
* [Operable software](https://ferd.ca/operable-software.html) by [@ferd](https://github.com/ferd)

## Logging

* [`lager`](https://github.com/erlang-lager/lager) ⭐ 1,130 | 🐛 52 | 🌐 Erlang | 📅 2025-08-26 - popular logging framework
  with broad features set
* [`logger`](http://www.erlang.org/doc/man/logger.html) - OTP 21+ built-in
  pluggable logger module
* [`Logger`](https://hexdocs.pm/logger/Logger.html) - Elixir's built-in
  pluggable logger module that in recent Elixir versions also synchronises with
  Erlang's `logger` module

## Metrics

* [Telemetry](https://github.com/beam-telemetry/telemetry) ⭐ 915 | 🐛 8 | 🌐 Erlang | 📅 2026-05-11 - dynamic dispatcher for Erlang metrics and instrumentations
* [Elixometer](https://github.com/pinterest/elixometer) ⭐ 825 | 🐛 11 | 🌐 Elixir | 📅 2023-07-10 - thin Elixir wrapper over Exometer
* [Folsom](https://github.com/boundary/folsom) ⭐ 583 | 🐛 14 | 🌐 Erlang | 📅 2018-11-07 - expose Erlang events as metrics
* [Prometheus](https://github.com/deadtrickster/prometheus.erl) ⭐ 354 | 🐛 13 | 🌐 Erlang | 📅 2026-07-27 - Prometheus integration for Erlang
* [Statix](https://github.com/lexmag/statix) ⭐ 286 | 🐛 17 | 🌐 Elixir | 📅 2024-06-10 - fast and reliable Elixir client for StatsD-compatible servers with some DogStatsD extensions (namely tags)
* [vmstats](https://github.com/ferd/vmstats) ⭐ 256 | 🐛 1 | 🌐 Erlang | 📅 2025-09-11 - tiny Erlang app to generate information on the Erlang VM
* [Exometer](https://github.com/Feuerlabs/exometer_core) ⭐ 194 | 🐛 22 | 🌐 Erlang | 📅 2025-08-26 - Erlang instrumentation package
* [Telemetry.Poller](https://github.com/beam-telemetry/telemetry_poller) ⭐ 127 | 🐛 0 | 🌐 Erlang | 📅 2025-10-17 - periodically gather measurements and publish them as Telemetry events
* [Fluxter](https://github.com/lexmag/fluxter) ⭐ 106 | 🐛 7 | 🌐 Elixir | 📅 2025-05-21 - InfluxDB writer for Elixir
* [`metrics`](https://github.com/benoitc/erlang-metrics) ⭐ 70 | 🐛 3 | 🌐 Erlang | 📅 2018-09-12 - generic interface to to a different metrics systems in Erlang

## Tracing

* [Spandex](https://github.com/spandex-project/spandex) ⭐ 347 | 🐛 19 | 🌐 Elixir | 📅 2023-10-16 - tracing library for
  Elixir which supports DataDog APM. Integrations:
  * [Phoenix](https://github.com/spandex-project/spandex_phoenix) ⭐ 85 | 🐛 8 | 🌐 Elixir | 📅 2023-02-10
  * [Ecto](https://github.com/spandex-project/spandex_ecto) ⭐ 32 | 🐛 5 | 🌐 Elixir | 📅 2024-02-29
* [AppSignal](https://github.com/appsignal/appsignal-elixir) ⭐ 292 | 🐛 16 | 🌐 Elixir | 📅 2026-07-09 - AppSignal
  Elixir integration package for gathering metrics, errors, and traces
* [New Relic](https://github.com/newrelic/elixir_agent) ⭐ 268 | 🐛 8 | 🌐 Elixir | 📅 2026-07-20 - New Relic's Elixir agent supports metrics, errors and distributed tracing
* [OpenCenus](https://github.com/census-instrumentation/opencensus-erlang) ⚠️ Archived -
  implementation of Google's [OpenCensus.io](https://opencensus.io) tracing and
  monitoring with broad range of integrations:
  * [Elixir](https://github.com/opencensus-beam/opencensus_elixir) ⭐ 39 | 🐛 5 | 🌐 Elixir | 📅 2022-05-10
  * [Absinthe](https://github.com/opencensus-beam/opencensus_absinthe) ⭐ 20 | 🐛 12 | 🌐 Elixir | 📅 2020-07-30
  * [Prometheus](https://github.com/opencensus-beam/prometheus) ⭐ 18 | 🐛 1 | 🌐 Erlang | 📅 2019-01-15
  * [Telemetry](https://github.com/opencensus-beam/opencensus_telemetry) ⭐ 17 | 🐛 1 | 🌐 Erlang | 📅 2019-06-18
  * [Plug](https://github.com/opencensus-beam/opencensus_plug) ⭐ 14 | 🐛 4 | 🌐 Elixir | 📅 2021-06-01
  * [Honeycomb](https://github.com/opencensus-beam/opencensus_honeycomb) ⭐ 10 | 🐛 2 | 🌐 Elixir | 📅 2022-10-19
  * [DataDog APM & DogStatsD](https://github.com/opencensus-beam/opencensus_datadog) ⭐ 8 | 🐛 1 | 🌐 Erlang | 📅 2019-07-15
  * [Elli](https://github.com/opencensus-beam/opencensus_elli) ⭐ 4 | 🐛 0 | 🌐 Erlang | 📅 2019-08-16
  * [Jaeger](https://github.com/opencensus-beam/opencensus-jaeger) ⭐ 4 | 🐛 3 | 🌐 Erlang | 📅 2020-10-21
  * [Google Reporter](https://github.com/opencensus-beam/oc_google_reporter) ⭐ 3 | 🐛 1 | 🌐 Erlang | 📅 2020-03-26
  * [InfluxDB](https://github.com/opencensus-beam/opencensus_influxdb) ⭐ 1 | 🐛 1 | 🌐 Erlang | 📅 2019-10-28
* [Otter](https://github.com/Bluehouse-Technology/otter) ⭐ 105 | 🐛 2 | 🌐 Erlang | 📅 2021-06-18 - OpenTracing
  integration library for Erlang
* [tracelog](https://github.com/opencensus-beam/tracelog) ⭐ 25 | 🐛 1 | 🌐 Erlang | 📅 2019-07-22 - logging handler that
  can transform structured logs into distributed tracing spans (for now supports
  only OpenCensus backend library)

## Errors logging

* [Sentry](https://github.com/getsentry/sentry-elixir) ⭐ 694 | 🐛 16 | 🌐 Elixir | 📅 2026-08-21 - official Elixir SDK for Sentry.io
* [Rollbar](https://github.com/ForzaElixir/rollbax) ⭐ 240 | 🐛 8 | 🌐 Elixir | 📅 2024-08-01 - exception tracking and logging from Elixir to Rollbar
* [Bugsnag](https://github.com/jarednorman/bugsnag-elixir) ⭐ 93 | 🐛 13 | 🌐 Elixir | 📅 2022-07-30 - Elixir interface to Bugsnag API
* [Aibrakex](https://github.com/fazibear/airbrakex) ⭐ 29 | 🐛 6 | 🌐 Elixir | 📅 2023-11-15 - Elixir client for Airbrake

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-21._
