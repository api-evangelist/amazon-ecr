# Amazon ECR (amazon-ecr)
Amazon Elastic Container Registry (ECR) is a fully managed container registry that makes it easy to store, manage, share, and deploy container images and artifacts. ECR eliminates the need to operate your own container repositories or worry about scaling the underlying infrastructure, and integrates with Amazon ECS and Amazon EKS for simplified development to production workflows.

**URL:** [Visit APIs.json URL](https://aws.amazon.com/ecr/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, AWS, Container Images, Container Registry, Containers, Docker, ECR, OCI

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon ECR API
API for managing Amazon ECR repositories, images, and related resources.

**Human URL:** [https://aws.amazon.com/ecr/](https://aws.amazon.com/ecr/)

#### Properties

- [Documentation](https://docs.aws.amazon.com/AmazonECR/latest/userguide/)
- [OpenAPI](openapi/amazon-ecr-openapi.yml)
- [OpenAPI](https://api.apis.guru/v2/specs/amazonaws.com/ecr/2015-09-21/openapi.yaml)
- [JSONSchema](json-schema/amazon-ecr-repository-schema.json)
- [JSONLD](json-ld/amazon-ecr-context.jsonld)
- [Pricing](https://aws.amazon.com/ecr/pricing/)
- [GettingStarted](https://aws.amazon.com/ecr/getting-started/)
- [FAQ](https://aws.amazon.com/ecr/faqs/)
- [Documentation](https://docs.aws.amazon.com/AmazonECR/latest/userguide/)
- [APIReference](https://docs.aws.amazon.com/AmazonECR/latest/APIReference/)
- [Documentation](https://docs.aws.amazon.com/cli/latest/reference/ecr/)
- [Security](https://docs.aws.amazon.com/AmazonECR/latest/userguide/security.html)
- [JSONStructure](json-structure/amazon-ecr-repository-structure.json)
- [Example](examples/amazon-ecr-repository-example.json)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/)
- [Documentation](https://docs.aws.amazon.com/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/support/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://status.aws.amazon.com/)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-web-services)
- [Contact](https://aws.amazon.com/contact-us/)
- [Security](https://aws.amazon.com/security/)
- [Compliance](https://aws.amazon.com/compliance/)
- [SpectralRules](rules/amazon-ecr-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-ecr-vocabulary.yaml)
- [NaftikoCapability](capabilities/ecr-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Fully Managed Registry | Eliminate the need to operate your own container repositories or worry about scaling infrastructure. |
| Image Vulnerability Scanning | Automated vulnerability assessment via Amazon Inspector integration for continuous image security. |
| Lifecycle Policies | Automatically expire and delete images based on rules to reduce storage costs. |
| Cross-Account Replication | Replicate images to registries in other AWS accounts and regions for availability. |
| OCI Artifact Support | Store and manage OCI-compliant artifacts including Helm charts and SBOMs. |
| Image Signing | Sign and verify container images automatically without additional infrastructure. |
| Pull Through Cache | Cache upstream public registry images in ECR for reduced egress costs and improved availability. |

## Use Cases

| Name | Description |
|------|-------------|
| CI/CD Pipeline Integration | Store container images in ECR and deploy to ECS or EKS as part of automated pipelines. |
| Security and Compliance | Automated vulnerability scanning and image signing for security-compliant container deployments. |
| Multi-Region Deployments | Replicate images across regions for low-latency pulls and improved resilience. |
| Helm Chart Repository | Store Helm charts as OCI artifacts for Kubernetes application deployment management. |
| Image Lifecycle Management | Manage image retention policies to keep registries clean and reduce storage costs. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon ECS | Natively integrated with ECS for pulling container images to run tasks and services. |
| Amazon EKS | Authenticate and pull container images from ECR for Kubernetes workloads. |
| Amazon Inspector | Continuous vulnerability scanning of images stored in ECR for security compliance. |
| AWS CodeBuild | Build and push container images to ECR as part of CI/CD build processes. |
| AWS IAM | Resource-based policies control who can push, pull, and manage images in ECR. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Ecr](openapi/amazon-ecr-openapi.yml)

### JSON Schema

- [Amazon Ecr Repository](json-schema/amazon-ecr-repository-schema.json)
- [Ecr Openapi Create Repository Response](json-schema/ecr-openapi-create-repository-response-schema.json)
- [Ecr Openapi Describe Repositories Response](json-schema/ecr-openapi-describe-repositories-response-schema.json)
- [Ecr Openapi Repository](json-schema/ecr-openapi-repository-schema.json)

### JSON Structure

- [Amazon Ecr Repository](json-structure/amazon-ecr-repository-structure.json)
- [Ecr Openapi Create Repository Response](json-structure/ecr-openapi-create-repository-response-structure.json)
- [Ecr Openapi Describe Repositories Response](json-structure/ecr-openapi-describe-repositories-response-structure.json)
- [Ecr Openapi Repository](json-structure/ecr-openapi-repository-structure.json)

### JSON-LD

- [Amazon Ecr](json-ld/amazon-ecr-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Ecr](capabilities/shared/ecr.yaml) — 22 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Ecr Management](capabilities/ecr-management.yaml) | 6 | managing ECR repositories, container images, and lifecycle policies for DevOps engineers |

## Vocabulary

- [Amazon ECR Vocabulary](vocabulary/amazon-ecr-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 6 actions, 1 workflows, and 1 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Ecr Spectral Rules](rules/amazon-ecr-spectral-rules.yml) — 28 rules enforcing Amazon ECR API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com