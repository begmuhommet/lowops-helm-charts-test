# Changelog

## [0.5.1](https://github.com/begmuhommet/lowops-helm-charts-test/compare/app-0.5.0...app-v0.5.1) (2026-10-21)


### Bug Fixes

* fall back to the default 8000 port ([e2b4769](https://github.com/begmuhommet/lowops-helm-charts-test/commit/e2b4769ab69066e1a52de9f6c612a83b43f24943))

## [0.5.0](https://github.com/cinaq/helm-charts/compare/app-generic-v0.4.2...app-v0.5.0) (2026-10-19)

* Single app chart. `app-generic`, `app-nextjs`, and `app-mendix` are replaced by `app`.
* `workload.kind` selects Deployment or StatefulSet.
* Probe thresholds and extra container ports come from values.
