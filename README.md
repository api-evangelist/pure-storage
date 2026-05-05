# Pure Storage (pure-storage)
Pure Storage is an American publicly traded technology company specializing in all-flash data storage hardware and software products. The company provides enterprise data storage platforms including FlashArray, FlashBlade, and Pure1 fleet management, along with Portworx for Kubernetes data services. Pure Storage offers REST APIs, SDKs, CRDs, and developer tooling that enable programmatic management of storage infrastructure and integration with automation workflows across block, file, and object storage.

**URL:** [Visit APIs.json URL](https://github.com/api-evangelist/pure-storage/blob/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Storage, Data Storage, Flash Storage, Enterprise Storage, Cloud Storage, Object Storage, File Storage, Block Storage, Kubernetes Storage, Infrastructure

## Timestamps

- **Created:** 2026-05-04
- **Modified:** 2026-05-05

## APIs

### FlashArray REST API
REST API for managing Pure Storage FlashArray, the company's all-flash storage array platform. Provides programmatic control over arrays, volumes, hosts, snapshots, replication, protection groups, pods, and other storage resources.

**Human URL:** [https://code.purestorage.com/swagger](https://code.purestorage.com/swagger)

#### Tags:

 - FlashArray, REST API, Block Storage, Storage Management

#### Properties

- [APIReference](https://code.purestorage.com/swagger)
- [Documentation](https://code.purestorage.com)
- [OpenAPI](openapi/flasharray-rest-api-openapi.yml)
- [Python SDK (py-pure-client)](https://pypi.org/project/py-pure-client/)
- [PowerShell Module](https://github.com/PureStorage-OpenConnect/PureStorage.Pure1)
- [PowerShell Toolkit 3.x](https://github.com/PureStorage-OpenConnect/powershell-toolkit-3)
- [Python REST 1.x Client (legacy)](https://github.com/PureStorage-OpenConnect/rest-client)
- [Ansible Playbook Examples](https://github.com/PureStorage-OpenConnect/ansible-playbook-examples)
- [Python Sample Scripts](https://github.com/PureStorage-OpenConnect/python-scripts)
- [SQL Server Scripts](https://github.com/PureStorage-OpenConnect/sqlserver-scripts)
- [Oracle Scripts](https://github.com/PureStorage-OpenConnect/oracle-scripts)
- [VMware Scripts](https://github.com/PureStorage-OpenConnect/VMware-Scripts)
- [Terraform Provider for FlashArray](https://github.com/PureStorage-OpenConnect/terraform-provider-flash)
- [FlashArray OpenMetrics Exporter](https://github.com/PureStorage-OpenConnect/pure-fa-openmetrics-exporter)
- [Array JSON Schema](json-schema/flasharray-rest-api-array-schema.json)
- [Volume JSON Schema](json-schema/flasharray-rest-api-volume-schema.json)
- [Host JSON Schema](json-schema/flasharray-rest-api-host-schema.json)
- [Array JSON Structure](json-structure/flasharray-rest-api-array-structure.json)
- [Volume JSON Structure](json-structure/flasharray-rest-api-volume-structure.json)
- [FlashArray JSON-LD Context](json-ld/pure-storage-flasharray-rest-api-context.jsonld)
- [Volume Example](examples/flasharray-rest-api-volume-example.json)
- [Array Example](examples/flasharray-rest-api-array-example.json)
- [FlashArray Shared Capability](capabilities/shared/flasharray-rest-api.yaml)

### FlashBlade REST API
REST API for managing Pure Storage FlashBlade, the unified fast file and object storage platform. Provides programmatic access to file systems, S3-compatible object stores, buckets, network configuration, policies, snapshots, and platform management.

**Human URL:** [https://code.purestorage.com/swagger](https://code.purestorage.com/swagger)

#### Tags:

 - FlashBlade, REST API, Object Storage, File Storage

#### Properties

- [APIReference](https://code.purestorage.com/swagger)
- [Documentation](https://code.purestorage.com)
- [OpenAPI](openapi/flashblade-rest-api-openapi.yml)
- [Python SDK (py-pure-client)](https://pypi.org/project/py-pure-client/)
- [FlashBlade PowerShell Module](https://github.com/PureStorage-OpenConnect/flashblade-powershell)
- [Purity//FB Python Client (legacy)](https://github.com/purestorage/purity_fb_python_client)
- [Ansible Playbook Examples](https://github.com/PureStorage-OpenConnect/ansible-playbook-examples)
- [Python Sample Scripts](https://github.com/PureStorage-OpenConnect/python-scripts)
- [FlashBlade OpenMetrics Exporter](https://github.com/PureStorage-OpenConnect/pure-fb-openmetrics-exporter)
- [FlashBlade MCP Server](https://github.com/PureStorage-OpenConnect/flashblade-mcp-server)
- [File System JSON Schema](json-schema/flashblade-rest-api-file-system-schema.json)
- [Bucket JSON Schema](json-schema/flashblade-rest-api-bucket-schema.json)
- [Array JSON Schema](json-schema/flashblade-rest-api-array-schema.json)
- [File System JSON Structure](json-structure/flashblade-rest-api-file-system-structure.json)
- [Bucket JSON Structure](json-structure/flashblade-rest-api-bucket-structure.json)
- [FlashBlade JSON-LD Context](json-ld/pure-storage-flashblade-rest-api-context.jsonld)
- [File System Example](examples/flashblade-rest-api-file-system-example.json)
- [Bucket Example](examples/flashblade-rest-api-bucket-example.json)
- [FlashBlade Shared Capability](capabilities/shared/flashblade-rest-api.yaml)

### Pure1 Public REST API
REST API for the Pure1 SaaS fleet management platform. Provides cross-array reporting, telemetry, capacity and performance metrics, alerts, audits, sustainability data, support contracts, and subscription information across the entire Pure Storage fleet.

**Human URL:** [https://code.purestorage.com/swagger](https://code.purestorage.com/swagger)

#### Tags:

 - Pure1, Cloud, Fleet Management, Telemetry, REST API

#### Properties

- [APIReference](https://static.pure1.purestorage.com/api-swagger/index.html)
- [Documentation](https://support.purestorage.com/Pure1/Pure1_Manage/Pure1_Manage_-_REST_API/Pure1_Manage_-_REST_API__Reference)
- [OpenAPI](openapi/pure1-cloud-api-openapi.yml)
- [Python SDK (py-pure-client)](https://pypi.org/project/py-pure-client/)
- [Pure1 PowerShell Module](https://github.com/PureStorage-OpenConnect/PureStorage.Pure1)
- [Pure1 Python Samples](https://github.com/PureStorage-OpenConnect/python-scripts)
- [Array JSON Schema](json-schema/pure1-cloud-api-array-schema.json)
- [Metric JSON Schema](json-schema/pure1-cloud-api-metric-schema.json)
- [Alert JSON Schema](json-schema/pure1-cloud-api-alert-schema.json)
- [Array JSON Structure](json-structure/pure1-cloud-api-array-structure.json)
- [Pure1 JSON-LD Context](json-ld/pure-storage-pure1-cloud-api-context.jsonld)
- [Array Example](examples/pure1-cloud-api-array-example.json)
- [Pure1 Shared Capability](capabilities/shared/pure1-cloud-api.yaml)

### Portworx Kubernetes API
Kubernetes-native data services platform from Pure Storage. Portworx exposes its API surface through Custom Resource Definitions managed by the libopenstorage operator and the portworx/apis CRDs, enabling declarative management of storage clusters, storage nodes, diagnostics, and volume populators on Kubernetes.

**Human URL:** [https://docs.portworx.com](https://docs.portworx.com)

#### Tags:

 - Portworx, Kubernetes, CRD, Data Services, Cloud Native

#### Properties

- [Documentation](https://docs.portworx.com)
- [GitHubRepository - libopenstorage/operator](https://github.com/libopenstorage/operator)
- [GitHubRepository - portworx/apis](https://github.com/portworx/apis)
- [StorageCluster CRD](crd/pure-storage-portworx-storagecluster.yaml)
- [StorageNode CRD](crd/pure-storage-portworx-storagenode.yaml)
- [PortworxDiag CRD](crd/pure-storage-portworx-portworxdiag.yaml)
- [PortworxXcopyVolumePopulator CRD](crd/pure-storage-portworx-xcopyvolumepopulator.yaml)
- [Pure Fusion Python SDK](https://github.com/PureStorage-OpenConnect/fusion-python-sdk)
- [Portworx Helm Charts](https://github.com/portworx/helm)
- [px-deploy](https://github.com/PureStorage-OpenConnect/px-deploy)
- [Stork Storage Orchestration Runtime](https://github.com/libopenstorage/stork)
- [Kubernetes Data Management Platform](https://github.com/portworx/kdmp)

## Common Properties

- [Website](https://www.purestorage.com)
- [DeveloperPortal](https://code.purestorage.com)
- [Documentation](https://code.purestorage.com)
- [APIReference](https://code.purestorage.com/swagger)
- [py-pure-client (Unified Python SDK)](https://github.com/PureStorage-OpenConnect/py-pure-client)
- [Swagger UI for FA / FB / Pure1](https://github.com/PureStorage-OpenConnect/swagger)
- [FlashBlade MCP Server](https://github.com/PureStorage-OpenConnect/flashblade-mcp-server)
- [px-deploy CLI](https://github.com/PureStorage-OpenConnect/px-deploy)
- [Support](https://support.purestorage.com)
- [KnowledgeCenter](https://supportcenter.purestorage.com)
- [GitHubOrganization - PureStorage-OpenConnect](https://github.com/PureStorage-OpenConnect)
- [GitHubOrganization - purestorage](https://github.com/purestorage)
- [GitHubOrganization - portworx](https://github.com/portworx)
- [GitHubOrganization - libopenstorage](https://github.com/libopenstorage)
- [Ansible Galaxy Collections](https://galaxy.ansible.com/purestorage)
- [Pure Storage Spectral Ruleset](rules/pure-storage-rules.yml)
- [Pure Storage Vocabulary](vocabulary/pure-storage-vocabulary.yml)
- [Pure Storage Fleet Management Workflow](capabilities/storage-fleet-management.yaml)

## Features

| Name | Description |
|------|-------------|
| All-Flash Storage | Enterprise all-flash storage hardware (FlashArray, FlashBlade) with consistent low-latency performance. |
| Unified File and Object Storage | FlashBlade provides scale-out file and S3-compatible object storage from a single platform. |
| Cross-Array Fleet Management | Pure1 SaaS provides telemetry, analytics, alerting, and capacity planning across the entire Pure fleet. |
| Kubernetes Data Services | Portworx delivers persistent storage, data protection, DR, and migration for Kubernetes workloads. |
| Active Cluster Replication | Synchronous replication for zero-RPO active-active configurations across data centers. |
| Snapshot and Cloning | Space-efficient snapshots and instant clones for backup, dev/test, and database refresh. |
| Sustainability Reporting | Pure1 sustainability metrics expose energy, carbon, and efficiency data per array. |
| OAuth 2.0 Token Exchange | All Pure Storage REST APIs authenticate via the OAuth 2.0 token-exchange flow with JWT subject tokens. |

## Use Cases

| Name | Description |
|------|-------------|
| Database Storage | High-performance storage for SQL Server, Oracle, SAP HANA, PostgreSQL, and other database workloads. |
| VMware and Virtualization | Storage backend for VMware vSphere, Hyper-V, KVM, and Nutanix virtualization platforms. |
| AI and Machine Learning Pipelines | FlashBlade powers training datasets, vector search, embedding pipelines, and RAG architectures. |
| Backup and Disaster Recovery | Snapshot-based backup, replication, and SafeMode immutable snapshots for ransomware recovery. |
| Cloud Block Storage | Cloud Block Store extends Pure Storage to AWS, Azure, and other public clouds. |
| Container and Kubernetes Storage | Portworx provides dynamic provisioning, snapshots, and DR for Kubernetes stateful workloads. |
| Fleet Capacity Planning | Pure1 telemetry feeds capacity forecasting, performance analysis, and lifecycle management. |

## Integrations

| Name | Description |
|------|-------------|
| VMware vSphere | First-class integration with vSphere via vCenter plugins, vVols, and SRM workflows. |
| Ansible | Official Ansible collections for FlashArray, FlashBlade, and Pure1 published on Ansible Galaxy. |
| Terraform | Terraform providers for FlashArray and Cloud Block Store. |
| Kubernetes | CSI drivers, the libopenstorage operator, Portworx, Stork, and the Pure Service Orchestrator (PSO). |
| OpenStack | Cinder and Manila drivers for FlashArray and FlashBlade. |
| Splunk | Splunk apps and TAs ingest Pure Storage telemetry for security and operations dashboards. |
| Prometheus / Grafana | OpenMetrics exporters for FlashArray and FlashBlade feed Prometheus-based observability stacks. |
| ServiceNow / Jira | Support and incident integrations through Pure1 alerts and webhooks. |

## Solutions

| Name | Description |
|------|-------------|
| FlashArray | All-flash block storage arrays for tier-1 enterprise workloads. |
| FlashBlade | Unified fast file and object storage for unstructured data and modern analytics. |
| Pure1 | SaaS-based AI-driven fleet management, analytics, and support platform. |
| Portworx | Kubernetes data services platform offering storage, DR, security, and migration. |
| Cloud Block Store | FlashArray-as-a-service running natively on AWS and Azure. |
| Evergreen Storage | Subscription model for non-disruptive controller and capacity upgrades. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [FlashArray REST API (FA 2.52)](openapi/flasharray-rest-api-openapi.yml)
- [FlashBlade REST API (FB 2.26)](openapi/flashblade-rest-api-openapi.yml)
- [Pure1 Public REST API (1.5)](openapi/pure1-cloud-api-openapi.yml)

### JSON Schema

35 JSON Schema files under [json-schema/](json-schema/) covering core resources for FlashArray, FlashBlade, and Pure1 - arrays, volumes, hosts, file systems, buckets, object store accounts, alerts, metrics, subscriptions, and more.

### JSON Structure

35 JSON Structure files under [json-structure/](json-structure/) - strict-typed equivalents of the JSON Schemas.

### JSON-LD

- [FlashArray JSON-LD Context](json-ld/pure-storage-flasharray-rest-api-context.jsonld)
- [FlashBlade JSON-LD Context](json-ld/pure-storage-flashblade-rest-api-context.jsonld)
- [Pure1 JSON-LD Context](json-ld/pure-storage-pure1-cloud-api-context.jsonld)

### Examples

35 example JSON payloads under [examples/](examples/), one per JSON Schema.

## Kubernetes CRDs

Kubernetes Custom Resource Definitions defining the declarative API surface for Portworx data services.

| Kind | Group | Version | Scope | File |
|------|-------|---------|-------|------|
| StorageCluster | core.libopenstorage.org | v1, v1alpha1 | Namespaced | [pure-storage-portworx-storagecluster.yaml](crd/pure-storage-portworx-storagecluster.yaml) |
| StorageNode | core.libopenstorage.org | v1, v1alpha1 | Namespaced | [pure-storage-portworx-storagenode.yaml](crd/pure-storage-portworx-storagenode.yaml) |
| PortworxDiag | portworx.io | v1 | Namespaced | [pure-storage-portworx-portworxdiag.yaml](crd/pure-storage-portworx-portworxdiag.yaml) |
| PortworxXcopyVolumePopulator | portworx.io | v1beta1 | Namespaced | [pure-storage-portworx-xcopyvolumepopulator.yaml](crd/pure-storage-portworx-xcopyvolumepopulator.yaml) |

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [FlashArray REST API](capabilities/shared/flasharray-rest-api.yaml) - 72 operations across 12 FlashArray resource groups
- [FlashBlade REST API](capabilities/shared/flashblade-rest-api.yaml) - 72 operations across 12 FlashBlade resource groups
- [Pure1 Public REST API](capabilities/shared/pure1-cloud-api.yaml) - 26 operations across 10 Pure1 resource groups

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Pure Storage Fleet Management](capabilities/storage-fleet-management.yaml) | FlashArray + FlashBlade + Pure1 | 12 | Storage Administrator |

## Vocabulary

- [Pure Storage Vocabulary](vocabulary/pure-storage-vocabulary.yml) - Unified taxonomy mapping 129 resources, 6 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Pure Storage Spectral Ruleset](rules/pure-storage-rules.yml) - 23 rules across 12 categories enforcing Pure Storage API conventions (snake_case schema/parameter naming, "Pure Storage" summary prefix, OpenAPI 3.0 conformance, Title Case tags, response/security requirements).

## Maintainers

**FN:** API Evangelist

**URL:** https://apievangelist.com
