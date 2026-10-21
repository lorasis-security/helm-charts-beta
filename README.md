# Lorasis beta Helm repository

**BETA**

**FOR TECHNICAL REVIEW. NOT YET QUALIFIED FOR DEPLOYMENT.**

This repository distributes the sanitized Lorasis Sense `0.3.4-beta` chart for
technical review. Catalogue availability and beta branding do not establish
deployment qualification. Defaults start no workloads.

Helm repository: https://lorasis-security.github.io/helm-charts-beta/

Download only, without installing:

```sh
helm pull lorasis-sense --repo https://lorasis-security.github.io/helm-charts-beta/ --version 0.3.4-beta
```

Verify the archive against `SHA256SUMS`. Read the chart's `README.md` and
`PHASES.md` before review. Images, wheels, companion bundles, credentials,
installation authority and deployment qualification are not included.

The beta is a metadata-and-documentation derivative of `0.3.4-unqualified`.
Application version `0.2.0`, functional templates, defaults, image references,
permissions and safety gates are unchanged. It does not replace or qualify
any separately controlled delivery candidate.
