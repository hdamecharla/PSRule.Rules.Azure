---
severity: Awareness
pillar: Operational Excellence
category: Deployment
resource: All resources
online version: https://github.com/Microsoft/PSRule.Rules.Azure/blob/main/docs/rules/en/Azure.Template.UseVariables.md
---

# Remove unused template variables

## SYNOPSIS

Each Azure Resource Manager (ARM) template variable should be used or removed from template files.

## DESCRIPTION

ARM templates can optionally define variables that can be reused throughout the template.
Variables that are not used may add template complexity for no benefit.

## RECOMMENDATION

Consider removing unused variables from Azure template files.

## LINKS

- [ARM template best practices](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-best-practices#variables)
