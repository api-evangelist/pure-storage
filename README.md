# Pure Storage (pure-storage)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
