# Roger Oliveira

**Platform Engineering · Site Reliability Engineering · Kubernetes**

I build reliable platforms through automation, observability, and changes that can be tested and safely reversed. My public work focuses on practical Linux and Kubernetes learning, repeatable reliability experiments, and evidence-driven incident analysis.

## Selected Engineering Work

### [Kubernetes From Scratch](https://github.com/roger-oliveira86/kubernetes-from-scratch)

A hands-on Linux, Kubernetes, and Platform Engineering learning track, progressing from operating-system fundamentals to Kubernetes workload troubleshooting.

- [Deployment, Service, rollout and rollback](https://github.com/roger-oliveira86/kubernetes-from-scratch/tree/main/01-fundamentals-and-workloads/lab-01-deployment-and-rollout) — deploy an application, inspect a stalled rollout, and roll back.
- [Workload configuration and readiness](https://github.com/roger-oliveira86/kubernetes-from-scratch/tree/main/01-fundamentals-and-workloads/lab-02-workload-configuration) — use a ConfigMap and a fictional Secret, then investigate readiness and EndpointSlice behavior.
- GitHub Actions validates manifests in strict mode against pinned Kubernetes 1.35.0 schemas.

### [Platform Reliability Lab](https://github.com/roger-oliveira86/platform-reliability-lab)

An independent reliability laboratory combining an observable Python HTTP service, secure container delivery examples, Kubernetes manifests, and deterministic incident reporting.

- **Service signals:** `/healthz`, Prometheus-compatible `/metrics`, structured JSON logs, and opt-in failure simulation.
- **Build and verification:** Python tests, a non-root container, smoke checks, Kubernetes schema validation, Trivy scanning, and separately authorized manual GHCR publication.
- **[POC-001 — deterministic readiness investigation](https://github.com/roger-oliveira86/platform-reliability-lab/tree/main/poc_001):** fictional Kubernetes snapshots, an immutable evidence catalog, explicit `collection_quality` reporting, and no LLM or live-cluster access in Mode A.
- GHCR publication remains paused. Publication under the renamed repository requires separate authorization; Kubernetes runtime deployment remains unverified in this lab.
- GitOps, tracing, dashboards, and AI-assisted Mode B are future possibilities, **not implemented capabilities**.

## Technical Writing

- [From LLM Tool Calling to Deterministic AIOps: Lessons from Kubernetes Troubleshooting](https://dev.to/rogeroliveira86/from-llm-tool-calling-to-deterministic-aiops-lessons-from-kubernetes-troubleshooting-57jb)
- [Running Doesn't Mean Ready: A Kubernetes Troubleshooting Lab](https://dev.to/rogeroliveira86/running-doesnt-mean-ready-a-kubernetes-troubleshooting-lab-2dg0)

[DEV.to](https://dev.to/rogeroliveira86) · [LinkedIn](https://www.linkedin.com/in/oliveiraroger/)

## Engineering Principles

Understand the system. Verify the signals. Make changes you can safely reverse.
