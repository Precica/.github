**Turn massive, fragmented datasets into instantly queryable, analytics-ready data — without the infrastructure overhead.**

Nutshell is a cloud-native SaaS platform that applies workload-aware AI compression at ingestion, so data stays cheap to store, fast to retrieve, and ready for analytics and ML — at tera and petabyte scale.

## The Problem

Organisations generate data continuously — from enterprise systems, connected devices, and large-scale simulations. That data arrives in structured, semi-structured, and unstructured formats, and it accumulates fast. As volumes grow, three constraints emerge consistently:

- **Cost** — archival and operational burden scales with data volume: power, storage footprint, and governance overhead.
- **Speed** — querying and retrieval slow down as data becomes fragmented across storage tiers and tooling.
- **Accessibility** — AI and ML development stalls when training pipelines require high-throughput, low-friction data access that existing infrastructure cannot reliably provide.

The bottleneck is not storage capacity. It is the ability to make large, fragmented data estates fast, affordable, and analytically useful.

## Why Nutshell exists

Nutshell connects to your cloud and enterprise data stores, ingests datasets, and compresses them using a workload-aware lossy pipeline. The output is an active dataset — one that remains queryable, ML-ready, and auditable without ever requiring full decompression.

**Core capabilities:**

- **Fast search and querying** — query compressed datasets directly, across multiple sources, without unpacking.
- **ML feature retrieval** — efficient sampling and feature access for model training and inference pipelines.
- **Configurable loss policies** — set acceptable distortion thresholds by dataset, field, or workload type.
- **Quality verification** — built-in metrics and guardrails so teams can trust and audit outputs.
- **Cloud interoperability** — designed to work across major IaaS providers and common data stacks.

## How it works

Nutshell uses a multi-modal ML engine that learns the underlying structure and patterns within structured data. It encodes datasets into a compressed format that retains the signals that matter for analytics and AI — discarding only what the configured loss policy permits.

Think of it as a zip file you never have to open: one you can query directly, join with other compressed sources across your organisation, and interrogate in real time.

A by-product of the encoding is high-grade encryption. Data cannot be decoded without knowing what was originally encoded.

## Who is it for

Nutshell is built for data-intensive organisations that manage large, high-dimensional datasets and depend on fast, reliable analytics:

- Energy utilities and consultancies
- Meteorological and environmental agencies
- Cloud and HPC users
- Advanced engineering and industrial enterprises
- Financial services organisations with high-volume structured data

## Status

The core technology has been validated on large, high-dimensional scientific datasets. Current development is focused on productising it into a standalone deployment application with robust integrations and an accessible interface for industry adoption.

Nutshell is a University of Manchester spinout, supported by the UoM Innovation Factory and backed by Northern Gridstone VC and Deep Tech Labs.


## Get involved

- **Pilots and collaboration** — if you are working with large structured datasets and want to explore what Nutshell can do, open an Issue or get in touch directly.
- **Contributions** — proposals for connectors, benchmarks, or quality metrics are welcome via Issues or PRs.
