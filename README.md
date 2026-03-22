# Cloud Custodian (cloud-custodian)
Cloud Custodian is a rules engine for cloud security, compliance, and cost optimization that enables users to define policies to manage cloud resources across AWS, Azure, and GCP. It helps organizations meet regulatory requirements and demonstrate accountability to stakeholders.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cloud-custodian/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Cloud Security, Compliance, Cost Optimization, Policy as Code, Multi-Cloud

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-18 

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
- [JSON-LD](json-ld/cloud-custodian-context.jsonld)
- [JSONSchema](json-schema/cloud-custodian-policy-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
