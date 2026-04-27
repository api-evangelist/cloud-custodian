# Cloud Custodian (cloud-custodian)
Cloud Custodian is an open-source rules engine for cloud security, compliance, and cost-optimization governance now stewarded by Stacklet. Operators express policies as YAML files that select a cloud resource type, apply filters, and execute actions; the engine then runs those policies against AWS, Azure, and GCP via provider-specific plugins. Custodian does not expose a developer REST API of its own - integration is via the c7n CLI, the policy YAML schema, c7n-org for multi-account fan-out, and c7n-mailer for SQS-driven notifications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cloud-custodian/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** Open Source

## Tags

- Cloud Security, Compliance, Cost Optimization, Multi-Cloud, Policy as Code

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-27

## APIs

### Cloud Custodian
Cloud Custodian provides rules-engine capabilities for managing cloud resources with security, compliance, and cost optimization policies.

**Human URL:** [https://cloudcustodian.io/](https://cloudcustodian.io/)


#### Tags:

 - Cloud Security, Policy as Code

#### Properties

- [Documentation](https://cloudcustodian.io/docs/)
- [Getting Started](https://cloudcustodian.io/docs/quickstart/index.html)
- [Reference](https://cloudcustodian.io/docs/overview/capabilities.html)
- [GitHubRepository](https://github.com/cloud-custodian/cloud-custodian)
- [JSONSchema](json-schema/cloud-custodian-policy-schema.json)

### Cloud Custodian AWS Provider
The Cloud Custodian AWS provider enables policy-as-code management of Amazon Web Services resources including EC2, S3, IAM, RDS, Lambda, and hundreds of other AWS service resource types. Policies can be run in multiple execution modes including serverless Lambda functions, AWS Config rules, and scheduled CloudWatch Events.

**Human URL:** [https://cloudcustodian.io/docs/aws/gettingstarted.html](https://cloudcustodian.io/docs/aws/gettingstarted.html)


#### Tags:

 - AWS, Cloud Security, Policy as Code, Compliance

#### Properties

- [Getting Started](https://cloudcustodian.io/docs/aws/gettingstarted.html)
- [Reference](https://cloudcustodian.io/docs/aws/resources/index.html)
- [Documentation](https://cloudcustodian.io/docs/aws/examples/index.html)

### Cloud Custodian Azure Provider
The Cloud Custodian Azure provider enables policy-as-code management of Microsoft Azure resources including virtual machines, storage accounts, network security groups, and other Azure services. Policies can enforce security requirements, tagging standards, and cost controls across Azure subscriptions.

**Human URL:** [https://cloudcustodian.io/docs/azure/gettingstarted.html](https://cloudcustodian.io/docs/azure/gettingstarted.html)


#### Tags:

 - Azure, Cloud Security, Policy as Code, Compliance

#### Properties

- [Getting Started](https://cloudcustodian.io/docs/azure/gettingstarted.html)
- [Reference](https://cloudcustodian.io/docs/azure/policy/resources/index.html)

### Cloud Custodian GCP Provider
The Cloud Custodian GCP provider enables policy-as-code management of Google Cloud Platform resources including Compute Engine instances, GCS buckets, Cloud SQL instances, and other GCP services. Policies can be used to enforce security, compliance, and cost governance standards across GCP projects.

**Human URL:** [https://cloudcustodian.io/docs/gcp/gettingstarted.html](https://cloudcustodian.io/docs/gcp/gettingstarted.html)


#### Tags:

 - GCP, Cloud Security, Policy as Code, Compliance

#### Properties

- [Getting Started](https://cloudcustodian.io/docs/gcp/gettingstarted.html)
- [Reference](https://cloudcustodian.io/docs/gcp/resources/index.html)

### Cloud Custodian c7n-org
c7n-org is a Cloud Custodian tool for running policies across multiple cloud accounts, projects, or subscriptions in parallel. It uses an accounts configuration file with assumed roles to orchestrate Custodian execution at scale across AWS Organizations, Azure subscriptions, or GCP projects.

**Human URL:** [https://cloudcustodian.io/docs/tools/c7n-org.html](https://cloudcustodian.io/docs/tools/c7n-org.html)


#### Tags:

 - Multi-Account, Orchestration, Cloud Security

#### Properties

- [Documentation](https://cloudcustodian.io/docs/tools/c7n-org.html)

### Cloud Custodian c7n-mailer
c7n-mailer is a Cloud Custodian notification tool that subscribes to an SQS queue populated by policy actions and sends notifications via SES email, Slack messages, or integrations with DataDog and Splunk. It enables teams to alert resource owners when Custodian policies detect policy violations.

**Human URL:** [https://cloudcustodian.io/docs/tools/c7n-mailer.html](https://cloudcustodian.io/docs/tools/c7n-mailer.html)


#### Tags:

 - Notifications, Email, Slack, Alerting

#### Properties

- [Documentation](https://cloudcustodian.io/docs/tools/c7n-mailer.html)
- [AsyncAPI](asyncapi/cloud-custodian-mailer-asyncapi.yml)

## Common Properties

- [Website](https://cloudcustodian.io/)
- [Documentation](https://cloudcustodian.io/docs/)
- [GitHub Organization](https://github.com/cloud-custodian/cloud-custodian)
- [Getting Started](https://cloudcustodian.io/docs/quickstart/index.html)
- [Community](https://cloudcustodian.io/community/)
- [GitHubRepository](https://github.com/cloud-custodian/cloud-custodian)
- [Change Log](https://github.com/cloud-custodian/cloud-custodian/releases)
- [JSON-LD Context](json-ld/cloud-custodian-context.jsonld)
- [Policy JSON Schema](json-schema/cloud-custodian-policy-schema.json)
- [Mailer AsyncAPI](asyncapi/cloud-custodian-mailer-asyncapi.yml)
- [Naftiko Capabilities](capabilities/cloud-custodian-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
