---
description: >-
  We've all heard of DevOps, and Infrastructure as Code is at the core of DevOps
  practices.  This site helps you understand these concepts and how you can
  apply them to building out SharePoint farms.
---

# Overview

### Using Infrastructure as Code

Your goal should be to automate the entire provisioning and configuration management of SharePoint Farms.  This will entail using non-Microsoft tooling.  [HashiCorp Terraform](https://www.terraform.io/) is a leading tool to help provision infrastructure in AWS and Azure as well as Google Cloud.



{% tabs %}
{% tab title="Infrastructure as Code" %}
Define infrastructure as code to increase operator productivity and transparency.  Now you're SharePoint Farm uses IaC.  Therefore, you can adopt the typical development workflow.



![Infrastructure as Code - deploy to multiple clouds](.gitbook/assets/image%20%283%29.png)
{% endtab %}

{% tab title="Collaborate & Share" %}
Terraform configuration can be stored in version control, shared, and collaborated on by teams of operators.

Most companies have more than one person managing their SharePoint Farm\(s\).  This approach enables for efficient, repeatable and reliable deployments and/or updates to a Farm Topology by more than one person.
{% endtab %}

{% tab title="Automation Friendly" %}
If it is code, you can run it through a CI/CD Pipeline, no matter what build server you use.  It could be Jenkins, or a hosted service like Azure DevOps.  Whatever your organization is using.



\[INSERT CI/CD PIPELINE SAMPLE FOR SP FARM HERE\]
{% endtab %}

{% tab title="Version your Infrastructure" %}
Since you are using a `source control` repository such as Git, GitHub, BitBucket; you are able to version your infrastructure and follow the typical `Developer Workflow` including submitting Pull Requests for changes to be reviewed prior to applying said changes.
{% endtab %}
{% endtabs %}

![With a single command, provision a farm to AWS, Azure or GCP](.gitbook/assets/terminal.png)

{% hint style="success" %}
Be a Hero at your company.
{% endhint %}

