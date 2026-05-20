# Reliability (reliability)
An index and topic collection covering site reliability engineering (SRE), reliability platforms, service level objectives (SLOs), error budgets, chaos engineering, resilience testing, and incident response. Reliability platforms help teams define and measure reliability targets, intentionally inject failure to validate resilience, manage on-call rotations and alerting, coordinate incident response, and run blameless post-incident reviews. This collection includes SLO management platforms like Nobl9 and Chronosphere, chaos engineering tools like Gremlin, Chaos Mesh, Litmus, and AWS Fault Injection Simulator, internal developer platforms with reliability scoring like OpsLevel and Cortex, and incident response platforms like PagerDuty, OpsGenie, Incident.io, FireHydrant, Rootly, Blameless, Squadcast, and Zenduty.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - SRE, Reliability, SLO, Chaos Engineering, Incident Response, Error Budget, On-Call, Resilience

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - SLO Schema](https://raw.githubusercontent.com/api-evangelist/reliability/refs/heads/main/json-schema/reliability-slo-schema.json)
- [JSONSchema - Chaos Experiment Schema](https://raw.githubusercontent.com/api-evangelist/reliability/refs/heads/main/json-schema/reliability-chaos-experiment-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/reliability/refs/heads/main/json-ld/reliability-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/reliability/refs/heads/main/vocabulary/reliability-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Service Level Objectives and Error Budgets | Reliability platforms let teams define SLIs, set SLOs, and track error budgets to balance reliability work against feature delivery. |
| Chaos Engineering and Fault Injection | Chaos tools deliberately inject failures into systems to validate resilience and uncover hidden weaknesses before they cause incidents. |
| Incident Response and On-Call Orchestration | Platforms orchestrate on-call rotations, alert routing, escalation policies, and incident war rooms across distributed teams. |
| Runbook Automation and Response Workflows | Reliability platforms automate runbooks that trigger on incidents, capture context, and guide responders through remediation. |
| Blast Radius Reduction and Safety Controls | Chaos and incident tools include halt conditions, scope limits, and automated rollback to contain the blast radius of experiments and incidents. |
| Blameless Post-Incident Reviews | Platforms structure post-incident analysis to extract learning, capturing timelines, contributing factors, and follow-up actions. |
| Service Standards and Reliability Scoring | Internal developer platforms score services against reliability standards such as ownership, on-call coverage, SLO adoption, and runbook completeness. |
| Status Pages and Customer Communication | Status page platforms communicate incident state and maintenance windows to customers and stakeholders in real time. |

## Use Cases

| Name | Description |
|------|-------------|
| SLO-Based Alerting | Replace threshold alerts with SLO burn-rate alerts that fire only when error budget is being consumed faster than sustainable. |
| Pre-Production Resilience Testing | Teams inject faults in staging environments to validate retries, timeouts, circuit breakers, and failover before production deploys. |
| Game Days and Continuous Verification | SRE teams run scheduled game days and continuous chaos experiments to verify runbooks, alerting, and failover behavior still work. |
| Incident Coordination at Scale | Platforms coordinate large incidents across multiple teams with auto-created channels, scribes, roles, and timeline capture. |
| Error Budget Policy Enforcement | When a service exhausts its error budget, policies can freeze deploys, page leadership, or trigger reliability investment. |
| On-Call Schedule Management | Manage rotation schedules, overrides, and escalation policies across global teams with chat and ticketing integrations. |
| Service Catalog and Reliability Standards | Track service ownership, tier, and adherence to reliability standards across the organization. |
| Customer-Facing Status Communication | Publish incident updates, scheduled maintenance, and component health to customers and subscribers. |

## Integrations

| Name | Description |
|------|-------------|
| Nobl9 | SLO platform that consolidates SLIs from observability sources into managed objectives with error budget tracking. |
| Gremlin | Chaos engineering platform for safely injecting CPU, memory, network, and dependency failures with built-in halt conditions. |
| PagerDuty | Incident response and on-call platform with rotation scheduling, escalation, event intelligence, and broad integrations. |
| Incident.io | Slack-native incident response platform that automates channel creation, roles, comms, and post-mortems. |
| FireHydrant | Incident management combining runbooks, retrospectives, status pages, and service catalog for reliability programs. |
| Chaos Mesh | Open-source CNCF chaos engineering platform for Kubernetes that injects pod, network, IO, and time faults. |
| OpsLevel | Internal developer portal that scores services against reliability standards such as SLOs, on-call, and runbooks. |
| Statuspage | Hosted status page platform for communicating incidents, maintenance, and component health to customers. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [SLO Schema](json-schema/reliability-slo-schema.json)
- [Chaos Experiment Schema](json-schema/reliability-chaos-experiment-schema.json)

### JSON Structure

- [SLO Structure](json-structure/reliability-slo-structure.json)
- [Chaos Experiment Structure](json-structure/reliability-chaos-experiment-structure.json)

### JSON-LD

- [Reliability Context](json-ld/reliability-context.jsonld)

## Vocabulary

- [Reliability Vocabulary](vocabulary/reliability-vocabulary.yaml) — Unified taxonomy mapping reliability resources, actions, workflows, and personas across SLO, chaos engineering, and incident response platforms

## Network

This index references the following reliability, chaos engineering, and incident response repositories:

- [Amazon Fault Injection Simulator](https://github.com/api-evangelist/amazon-fault-injection-simulator)
- [Better Stack](https://github.com/api-evangelist/betterstack)
- [Blameless](https://github.com/api-evangelist/blameless)
- [Chaos Mesh](https://github.com/api-evangelist/chaos-mesh)
- [Chronosphere](https://github.com/api-evangelist/chronosphere)
- [Cortex](https://github.com/api-evangelist/cortex)
- [FireHydrant](https://github.com/api-evangelist/firehydrant)
- [Gremlin](https://github.com/api-evangelist/gremlin)
- [Harness](https://github.com/api-evangelist/harness)
- [Incident.io](https://github.com/api-evangelist/incident-io)
- [Lightstep](https://github.com/api-evangelist/lightstep)
- [Litmus](https://github.com/api-evangelist/litmus)
- [Moogsoft](https://github.com/api-evangelist/moogsoft)
- [Nobl9](https://github.com/api-evangelist/nobl9)
- [OneUptime](https://github.com/api-evangelist/oneuptime)
- [OpsGenie](https://github.com/api-evangelist/opsgenie)
- [OpsLevel](https://github.com/api-evangelist/opslevel)
- [PagerDuty](https://github.com/api-evangelist/pagerduty)
- [Rootly](https://github.com/api-evangelist/rootly)
- [SIGNL4](https://github.com/api-evangelist/signl4)
- [Splunk On-Call (VictorOps)](https://github.com/api-evangelist/victorops)
- [Squadcast](https://github.com/api-evangelist/squadcast)
- [Statuspage](https://github.com/api-evangelist/statuspage)
- [xMatters](https://github.com/api-evangelist/xmatters)
- [Zenduty](https://github.com/api-evangelist/zenduty)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
