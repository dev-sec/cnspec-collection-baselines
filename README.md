# cnspec DevSec Baseline Collection

## Description

This repository provides the DevSec Baselines for [cnspec](github.com/mondoohq/cnspec) and includes the following DevSec Baselines:

| Baseline                       | Version | Status                    |
| ------------------------------ | ------- | ------------------------- |
| DevSec Linux Security Baseline | 2.9.0   | in progress, 99% complete |

## Installation

- Install [cnspec](https://github.com/mondoohq/cnspec#installation)
- minimum required `cnspec`-version is 8.8.0. 

## Using the DevSec Baselines

Scan local workstation or server:

```bash
cnspec scan local -f linux-baseline.mql.yaml
```

Scan a running docker container:

```bash
cnspec scan docker 537f7fca28b9 -f linux-baseline.mql.yaml
```

Scan a remote VM:

```bash
cnspec scan ssh user@hostip -f linux-baseline.mql.yaml
```

## Roadmap

| Baseline                         | Status  |
| -------------------------------- | ------- |
| DevSec SSH Baseline              | planned |
| DevSec Windows Security Baseline | planned |
| DevSec Nginx Baseline            | planned |
| DevSec SSL/TLS Baseline          | planned |
| DevSec MySQL Baseline            | planned |
| DevSec Apache Baseline           | planned |

## Release Notes

See the [release notes](https://github.com/dev-sec/cnspec-collection-baselines/releases).

## Kudos

We like to thank all maintainers of the InSpec baselines. This implementation of the DevSec Baselines for cnspec is based on the collective knowledge of the Apache 2 - Licensed DevSec Baselines for InSpec.

## Licensing

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
