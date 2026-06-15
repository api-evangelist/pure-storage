# Pure Storage (pure-storage)

Pure Storage is an American publicly traded technology company specializing in all-flash data storage hardware and software products. The company provides enterprise data storage platforms including FlashArray, FlashBlade, and Pure1 fleet management, along with Portworx for Kubernetes data services. Pure Storage offers REST APIs, SDKs, CRDs, and developer tooling that enable programmatic management of storage infrastructure and integration with automation workflows across block, file, and object storage.

**APIs.json:** [https://github.com/api-evangelist/pure-storage/blob/main/apis.yml](https://github.com/api-evangelist/pure-storage/blob/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Storage
- Data Storage
- Flash Storage
- Enterprise Storage
- Cloud Storage
- Object Storage
- File Storage
- Block Storage
- Kubernetes Storage
- Infrastructure

## Timestamps

- **Created:** 2026-05-04
- **Modified:** 2026-05-19

## APIs

### FlashArray REST API

REST API for managing Pure Storage FlashArray, the company's all-flash storage array platform. Provides programmatic control over arrays, volumes, hosts, snapshots, replication, protection groups, pods, and other storage resources.

- **Human URL:** [https://code.purestorage.com/swagger](https://code.purestorage.com/swagger)

#### Tags

- FlashArray
- REST API
- Block Storage
- Storage Management

#### Properties

- [API Reference](https://code.purestorage.com/swagger)
- [Documentation](https://code.purestorage.com)
- [OpenAPI](openapi/flasharray-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flasharray-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flasharray-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://pypi.org/project/py-pure-client/)
- [SDK](https://github.com/PureStorage-OpenConnect/PureStorage.Pure1)
- [SDK](https://github.com/PureStorage-OpenConnect/powershell-toolkit-3)
- [SDK](https://github.com/PureStorage-OpenConnect/rest-client)
- [Code Examples](https://github.com/PureStorage-OpenConnect/ansible-playbook-examples)
- [Code Examples](https://github.com/PureStorage-OpenConnect/python-scripts)
- [Code Examples](https://github.com/PureStorage-OpenConnect/sqlserver-scripts)
- [Code Examples](https://github.com/PureStorage-OpenConnect/oracle-scripts)
- [Code Examples](https://github.com/PureStorage-OpenConnect/VMware-Scripts)
- [Integrations](https://github.com/PureStorage-OpenConnect/terraform-provider-flash)
- [Integrations](https://github.com/PureStorage-OpenConnect/pure-fa-openmetrics-exporter)
- [JSON Schema](json-schema/flasharray-rest-api-array-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flasharray-rest-api-volume-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flasharray-rest-api-host-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flasharray-rest-api-array-structure.json)
- [JSON Structure](json-structure/flasharray-rest-api-volume-structure.json)
- [JSON-LD](json-ld/pure-storage-flasharray-rest-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/flasharray-rest-api-volume-example.json)
- [Example](examples/flasharray-rest-api-array-example.json)

### FlashBlade REST API

REST API for managing Pure Storage FlashBlade, the unified fast file and object storage platform. Provides programmatic access to file systems, S3-compatible object stores, buckets, network configuration, policies, snapshots, and platform management.

- **Human URL:** [https://code.purestorage.com/swagger](https://code.purestorage.com/swagger)

#### Tags

- FlashBlade
- REST API
- Object Storage
- File Storage

#### Properties

- [API Reference](https://code.purestorage.com/swagger)
- [Documentation](https://code.purestorage.com)
- [OpenAPI](openapi/flashblade-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flashblade-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flashblade-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://pypi.org/project/py-pure-client/)
- [SDK](https://github.com/PureStorage-OpenConnect/flashblade-powershell)
- [SDK](https://github.com/purestorage/purity_fb_python_client)
- [Code Examples](https://github.com/PureStorage-OpenConnect/ansible-playbook-examples)
- [Code Examples](https://github.com/PureStorage-OpenConnect/python-scripts)
- [Integrations](https://github.com/PureStorage-OpenConnect/pure-fb-openmetrics-exporter)
- [Tools](https://github.com/PureStorage-OpenConnect/flashblade-mcp-server)
- [JSON Schema](json-schema/flashblade-rest-api-file-system-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flashblade-rest-api-bucket-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flashblade-rest-api-array-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flashblade-rest-api-file-system-structure.json)
- [JSON Structure](json-structure/flashblade-rest-api-bucket-structure.json)
- [JSON-LD](json-ld/pure-storage-flashblade-rest-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/flashblade-rest-api-file-system-example.json)
- [Example](examples/flashblade-rest-api-bucket-example.json)

### Pure1 Public REST API

REST API for the Pure1 SaaS fleet management platform. Provides cross-array reporting, telemetry, capacity and performance metrics, alerts, audits, sustainability data, support contracts, and subscription information across the entire Pure Storage fleet.

- **Human URL:** [https://code.purestorage.com/swagger](https://code.purestorage.com/swagger)

#### Tags

- Pure1
- Cloud
- Fleet Management
- Telemetry
- REST API

#### Properties

- [API Reference](https://static.pure1.purestorage.com/api-swagger/index.html)
- [Documentation](https://support.purestorage.com/Pure1/Pure1_Manage/Pure1_Manage_-_REST_API/Pure1_Manage_-_REST_API__Reference)
- [OpenAPI](openapi/pure1-cloud-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pure1-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pure1-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://pypi.org/project/py-pure-client/)
- [SDK](https://github.com/PureStorage-OpenConnect/PureStorage.Pure1)
- [Code Examples](https://github.com/PureStorage-OpenConnect/python-scripts)
- [JSON Schema](json-schema/pure1-cloud-api-array-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pure1-cloud-api-metric-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pure1-cloud-api-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/pure1-cloud-api-array-structure.json)
- [JSON-LD](json-ld/pure-storage-pure1-cloud-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/pure1-cloud-api-array-example.json)

### Portworx Kubernetes API

Kubernetes-native data services platform from Pure Storage. Portworx exposes its API surface through Custom Resource Definitions managed by the libopenstorage operator and the portworx/apis CRDs, enabling declarative management of storage clusters, storage nodes, diagnostics, and volume populators on Kubernetes.

- **Human URL:** [https://docs.portworx.com](https://docs.portworx.com)

#### Tags

- Portworx
- Kubernetes
- CRD
- Data Services
- Cloud Native

#### Properties

- [Documentation](https://docs.portworx.com)
- [GitHub Repository](https://github.com/libopenstorage/operator)
- [GitHub Repository](https://github.com/portworx/apis)
- [Kubernetes C R D](crd/pure-storage-portworx-storagecluster.yaml)
- [Kubernetes C R D](crd/pure-storage-portworx-storagenode.yaml)
- [Kubernetes C R D](crd/pure-storage-portworx-portworxdiag.yaml)
- [Kubernetes C R D](crd/pure-storage-portworx-xcopyvolumepopulator.yaml)
- [SDK](https://github.com/PureStorage-OpenConnect/fusion-python-sdk)
- [Tools](https://github.com/portworx/helm)
- [Tools](https://github.com/PureStorage-OpenConnect/px-deploy)
- [Integrations](https://github.com/libopenstorage/stork)
- [Integrations](https://github.com/portworx/kdmp)
- [Postman Collection](collections/flasharray-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flasharray-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/flashblade-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flashblade-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pure1-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pure1-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/purestorage)
- [Website](https://www.purestorage.com)
- [Developer Portal](https://code.purestorage.com)
- [Documentation](https://code.purestorage.com)
- [API Reference](https://code.purestorage.com/swagger)
- [SDK](https://github.com/PureStorage-OpenConnect/py-pure-client)
- [Tools](https://github.com/PureStorage-OpenConnect/swagger)
- [Tools](https://github.com/PureStorage-OpenConnect/flashblade-mcp-server)
- [C L I](https://github.com/PureStorage-OpenConnect/px-deploy)
- [Support](https://support.purestorage.com)
- [Knowledge Center](https://supportcenter.purestorage.com)
- [GitHub Organization](https://github.com/PureStorage-OpenConnect)
- [GitHub Organization](https://github.com/purestorage)
- [GitHub Organization](https://github.com/portworx)
- [GitHub Organization](https://github.com/libopenstorage)
- [Integrations](https://galaxy.ansible.com/purestorage)
- [Spectral Rules](rules/pure-storage-rules.yml)
- [Vocabulary](vocabulary/pure-storage-vocabulary.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** API Evangelist
**URL:** https://apievangelist.com
