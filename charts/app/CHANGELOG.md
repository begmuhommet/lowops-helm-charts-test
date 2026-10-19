# Changelog

## [0.5.0](https://github.com/cinaq/helm-charts/compare/app-generic-v0.4.2...app-v0.5.0) (2026-10-19)

* Single app chart. `app-generic`, `app-nextjs`, and `app-mendix` are replaced by `app`.
* `workload.kind` selects Deployment or StatefulSet.
* Probe thresholds and extra container ports come from values.
