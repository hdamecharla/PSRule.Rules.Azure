---
severity: Important
pillar: Security
category: Identity and access management
resource: Azure Kubernetes Service
online version: https://github.com/Microsoft/PSRule.Rules.Azure/blob/main/docs/rules/en/Azure.AKS.UseRBAC.md
ms-content-id: 61ff3a23-9bfd-4e91-8959-798b43237775
---

# AKS clusters use RBAC

## SYNOPSIS

Deploy AKS cluster with role-based access control (RBAC) enabled.

## DESCRIPTION

AKS supports granting access to cluster resources using role-based access control (RBAC).
Additionally Azure Active Directory (AAD) integration with AKS allows, RBAC to be granted based on AAD user or group.

## RECOMMENDATION

Azure AD integration with AKS provides granular access control for Kubernetes resources using RBAC.

RBAC is a deployment time configuration.
Consider redeploying the AKS cluster with RBAC enabled.

## LINKS

- [Access and identity options for Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/concepts-identity#azure-active-directory-integration)
- [Best practices for authentication and authorization in Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-identity#use-azure-active-directory)
- [Using RBAC Authorization](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)
- [Azure template reference](https://docs.microsoft.com/en-us/azure/templates/microsoft.containerservice/2020-04-01/managedclusters#managedclusterproperties-object)
