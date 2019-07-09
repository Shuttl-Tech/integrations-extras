# CHANGELOG - Logstash


0.0.2/ 2019-07-09
==================
This is a custom release from `Shuttl-Tech` organisation.

### Changes
* [BUGFIX] adds `MANIFEST.in` file in `logstash` integration to package the `data/` directory with the wheel. A bugfix in datadog agent version 6.12.0 broke installation of this integration because its wheel didn't include `data/` dir due to absence of the MANIFEST.in.

0.1.0/ Unreleased
==================

### Changes

* [FEATURE] adds logstash integration.
