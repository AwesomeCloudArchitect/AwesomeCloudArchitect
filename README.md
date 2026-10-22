# Cloud Architect Wiki

A community-maintained, cloud-provider-independent encyclopedia of cloud architecture knowledge: principles, patterns, best practices, and trade-offs.

> **Status:** skeleton - most pages are placeholders open for contribution. See [CONTRIBUTING.md](CONTRIBUTING.md) to get involved.

## Table of Contents

### 01. [Foundations](01-foundations/index.md)

- [Architecture Principles](01-foundations/architecture-principles.md)
- [Landing Zones](01-foundations/landing-zones.md)
- [Hybrid & Multicloud](01-foundations/hybrid-multicloud.md)
- [Compliance & Risk](01-foundations/compliance-risk.md)

### 02. [Core Domains](02-core-domains/index.md)

- **Data Storage**
  - [Object Storage](02-core-domains/data-storage/object-storage.md)
  - [Block Storage](02-core-domains/data-storage/block-storage.md)
  - [File Storage](02-core-domains/data-storage/file-storage.md)
  - [Storage Tiering & Lifecycle](02-core-domains/data-storage/storage-tiering-lifecycle.md)
- **Databases**
  - [Relational (RDBMS)](02-core-domains/databases/relational.md)
  - [Key-Value](02-core-domains/databases/key-value.md)
  - [Document](02-core-domains/databases/document.md)
  - [Column-Family (Wide-Column)](02-core-domains/databases/column-family.md)
  - [Graph](02-core-domains/databases/graph.md)
  - [Time-Series](02-core-domains/databases/time-series.md)
  - [Search / Full-Text](02-core-domains/databases/search.md)
  - [Choosing a Database & Polyglot Persistence](02-core-domains/databases/choosing-a-database.md)
- **Applications**
  - [Monolithic](02-core-domains/applications/monolithic.md)
  - [Containers](02-core-domains/applications/containers.md)
  - [Container Orchestration](02-core-domains/applications/container-orchestration.md)
  - [Kubernetes](02-core-domains/applications/kubernetes.md)
  - [Microservices](02-core-domains/applications/microservices.md)
  - [Event-Driven Architecture](02-core-domains/applications/event-driven.md)
  - [Serverless / Functions](02-core-domains/applications/serverless-functions.md)
- [Networking](02-core-domains/networking.md)
- [Identity & Security](02-core-domains/identity-security.md)
- [Governance](02-core-domains/governance.md)
- **Monitoring**
  - [Logging](02-core-domains/monitoring/logging.md)
  - [Metrics](02-core-domains/monitoring/metrics.md)
  - [Tracing](02-core-domains/monitoring/tracing.md)
  - [Alerting](02-core-domains/monitoring/alerting.md)

### 03. [Migration & Modernization](03-migration-modernization/index.md)

- [Application Assessment](03-migration-modernization/application-assessment.md)
- **Application Migration**
  - [The 7 Rs](03-migration-modernization/application-migration/7rs.md)
- [Migration Factory](03-migration-modernization/migration-factory.md)
- **Database Migration**
  - [Change Data Capture (CDC)](03-migration-modernization/database-migration/cdc.md)
  - [Replication](03-migration-modernization/database-migration/replication.md)
  - [Cutover](03-migration-modernization/database-migration/cutover.md)

### 04. [Data & AI](04-data-ai/index.md)

- [Data Platforms](04-data-ai/data-platforms.md)
- [Data Governance](04-data-ai/data-governance.md)
- [MLOps](04-data-ai/mlops.md)

### 05. [Operating the Cloud](05-operating-the-cloud/index.md)

- **Scalability**
  - [Autoscaling](05-operating-the-cloud/scalability/autoscaling.md)
  - [Caching](05-operating-the-cloud/scalability/caching.md)
  - [Queues](05-operating-the-cloud/scalability/queues.md)
  - [Backpressure](05-operating-the-cloud/scalability/backpressure.md)
- **Reliability**
  - [High Availability (HA)](05-operating-the-cloud/reliability/high-availability.md)
  - [Disaster Recovery (DR)](05-operating-the-cloud/reliability/disaster-recovery.md)
  - [Recovery Point Objective (RPO)](05-operating-the-cloud/reliability/rpo.md)
  - [Recovery Time Objective (RTO)](05-operating-the-cloud/reliability/rto.md)
- [DevOps](05-operating-the-cloud/devops.md)
- [Platform Engineering](05-operating-the-cloud/platform-engineering.md)

### 06. [Business & Strategy](06-business-strategy/index.md)

- [FinOps](06-business-strategy/finops.md)
- [Sustainability](06-business-strategy/sustainability.md)
- [Executive Strategy](06-business-strategy/executive-strategy.md)

## About This Project

This wiki aims to be a **cloud-provider-independent** reference for cloud architects - principles, patterns, and trade-offs that hold regardless of which cloud you run on. Provider-specific implementation notes are welcome *inside* a page (clearly labeled per provider) but the page's core content should stand on its own.

**Two ways to browse:** [Core Domains](02-core-domains/index.md) is the day-to-day reference (Data Storage, Databases, Applications, Networking, Identity & Security, Governance, Monitoring). [Migration & Modernization](03-migration-modernization/index.md), [Operating the Cloud](05-operating-the-cloud/index.md), and [Business & Strategy](06-business-strategy/index.md) are organized by lifecycle stage instead.

- Style Guide: [STYLE_GUIDE.md](STYLE_GUIDE.md) - formatting and writing conventions
- Page Template: [PAGE_TEMPLATE.md](PAGE_TEMPLATE.md) - the template every page follows
- Contributing Guide: [CONTRIBUTING.md](CONTRIBUTING.md) - how to propose and submit pages
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [License](LICENSE)

