**Languages:** [English](README.md) · [Español](README.es.md)

# statsd-fork

Historical copy of StatsD 0.8.0.

<!-- BEGIN project-context -->

## Historical dates and evidence

**Reference year for this version: 2017.** This uses the most recent source or configuration file with a recoverable historical date; the exact creation date could not be confirmed.

- Most recent datable file: **2017-11-26**, [`statsd/test/set_tests.js`](statsd/test/set_tests.js); preserved modification timestamp.
- First record in the original Git repository containing this code: **2010-12-30**. This may be an import and does not establish when the code was first written.

## Why this is worth exploring

The receive metrics → aggregate → periodically send to backends flow captures the service's central idea. It is a good way to understand counters, timers, and gauges without relying on a complete observability platform.

Code entry points:

- [`stats.js`](statsd/stats.js)
- [`lib`](statsd/lib/)
- [`backends`](statsd/backends/)

<!-- END project-context -->

## Contents

| Directory | Function |
| --- | --- |
| [`statsd/`](statsd/) | Copy of StatsD 0.8.0, a Node.js service that receives metrics, aggregates counters/timers/gauges, and sends results to configurable backends. |

Imported derivative of etsy/statsd. LICENSE is retained. The previous local history is not published.

## Requirements and setup

Node.js and npm.

This is a historical copy. Consult each component's project files and README for versions and dependencies. Restore NuGet/npm from the appropriate folder; internal libraries may need rebuilding. Prepare databases and external services using your own accounts.

Main JavaScript packages:

- `statsd/package.json`

## Configuration and security

Original secrets have been removed or replaced with `REPLACE_WITH_YOUR_VALUE`. Search for this marker before running and provide values through local configuration or environment variables. Sessions, private keys, signing certificates, databases, logs, deployment profiles, and binary packages are not published. The `.gitignore` protects these local files.

A fresh history is published: old commits remain only in the original local copy. Example values cannot connect to the original services.

## Validation status

A static review and secret scan were performed before publication. Applications, trading operations, deployments, and tests contacting external services were not run. Building with current tools is not guaranteed. Some projects need historical dependencies and assets that are not included.

## Licenses and provenance

Third-party licenses and attributions present in the code are retained. No blanket license is added to components that lacked one. This import preserves local sources and does not claim to be a current version of the original project.

Upstream project: [original source](https://github.com/etsy/statsd). This is an independent import of the local copy, with a fresh history.
