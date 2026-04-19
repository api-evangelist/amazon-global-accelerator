# Amazon Global Accelerator (amazon-global-accelerator)
Amazon Global Accelerator is a networking service that improves the performance and availability of applications with local or global users. It provides static IP addresses that act as a fixed entry point to your applications and uses the AWS global network to optimize the path from users to applications, improving performance by up to 60%.

**URL:** [https://aws.amazon.com/global-accelerator/](https://aws.amazon.com/global-accelerator/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Availability, AWS, CDN, Global, Load Balancing, Networking, Performance

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon Global Accelerator API
The Amazon Global Accelerator API enables programmatic access to create and manage accelerators, listeners, and endpoint groups. You can configure traffic routing, health checks, and client IP address preservation to optimize application performance across AWS Regions.

**Human URL:** [https://aws.amazon.com/global-accelerator/](https://aws.amazon.com/global-accelerator/)

#### Tags:

 - Global, Networking, Performance, Traffic Management

#### Properties

- [Documentation](https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html)
- [OpenAPI](openapi/amazon-global-accelerator-openapi.yml)
- [Pricing](https://aws.amazon.com/global-accelerator/pricing/)
- [GettingStarted](https://aws.amazon.com/global-accelerator/getting-started/)
- [FAQ](https://aws.amazon.com/global-accelerator/faqs/)
- [APIReference](https://docs.aws.amazon.com/global-accelerator/latest/api/Welcome.html)
- [Authentication](https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html)
- [JSONSchema](json-schema/global-accelerator-accelerator-schema.json)
- [JSONLD](json-ld/amazon-global-accelerator-context.jsonld)

## Common Properties

- [Portal](https://console.aws.amazon.com/)
- [Documentation](https://docs.aws.amazon.com/global-accelerator/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/networking-and-content-delivery/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/globalaccelerator)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Static Anycast IP Addresses | Provides two static IP addresses as fixed entry points to applications, simplifying DNS management and whitelisting. |
| AWS Global Network Routing | Routes user traffic through the AWS global network backbone for up to 60% performance improvement over public internet. |
| Intelligent Traffic Distribution | Automatically routes traffic to the closest healthy endpoint based on geography, health, and routing policies. |
| Health Checking | Continuously monitors endpoint health and instantly reroutes traffic away from unhealthy endpoints. |
| Client IP Preservation | Preserves the original client IP address for application endpoints that need it. |
| Custom Routing | Enables deterministic routing of connections to specific EC2 instances using port mappings. |

## Use Cases

| Name | Description |
|------|-------------|
| Global Application Performance | Improve latency and throughput for globally distributed users by routing through AWS edge locations. |
| Multi-Region Failover | Automatically failover traffic to healthy endpoints across regions without DNS changes. |
| Gaming Applications | Reduce latency for real-time gaming applications using the AWS global network. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Elastic Load Balancing | Route traffic to Application, Network, or Classic Load Balancers as endpoints. |
| Amazon EC2 | Use EC2 instances directly as Global Accelerator endpoints. |
| Amazon CloudWatch | Monitor accelerator metrics and set alarms for traffic and health status. |
| AWS CloudFormation | Provision Global Accelerator resources using infrastructure templates. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Global Accelerator OpenAPI](openapi/amazon-global-accelerator-openapi.yml)

### JSON Schema

192 schema files in [json-schema/](json-schema/)

### JSON Structure

192 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon Global Accelerator Context](json-ld/amazon-global-accelerator-context.jsonld)

### Examples

192 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Global Accelerator](capabilities/shared/amazon-global-accelerator.yaml) — 13 operations for network traffic management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon Global Accelerator Network Operations](capabilities/amazon-global-accelerator-network-operations.yaml) | Amazon Global Accelerator | 11 | Network Engineer, DevOps Engineer |

## Vocabulary

- [Amazon Global Accelerator Vocabulary](vocabulary/amazon-global-accelerator-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflow, and 2 personas

## Rules

- [Amazon Global Accelerator Spectral Rules](rules/amazon-global-accelerator-spectral-rules.yml) — 14 rules across 6 categories enforcing Amazon Global Accelerator API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
