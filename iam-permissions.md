---

copyright:
  years: 2022, 2023
lastupdated: "2023-03-15"

keywords: bandwidth metering, bandwidth pools

subcollection: bandwidth-metering

---

{{site.data.keyword.attribute-definition-list}}

# Managing permissions 
{: #bw-metering-required-permissions}

The **BANDWIDTH_MANAGE** IMS infrastructure classic permission is the only required permission for bandwidth metering. Certain actions for bandwidth pools, including visibility, can be constrained based on device level permission. Reconcile your device level permissions on specific devices to manage their bandwidth and membership in pools.
{: shortdesc}

## IMS infrastructure classic required permission
{: #bw-metering-required-ims-permission}

One infrastructure classic permission is required for bandwidth metering. The **BANDWIDTH_MANAGE** permission is required to permit a user to complete the following actions:
- Create a bandwidth pool
- Move a device into or out of a pool
- Void a device’s move into a pool
- Cancel a pool

The BANDWIDTH_MANAGE IMS infrastructure classic permission is the only required permission for bandwidth metering. 
{: important}

## IAM permissions 
{: #bw-metering-optional-iam-permissions}

To grant a user permission to complete different actions on a device, follow these steps:

1. Log in to the [Access (IAM)](/iam/users){: external} page in the {{site.data.keyword.cloud}} console.
1. Select the user's name and edit their permissions. 

A user's account permissions determine what actions that they can complete on a device. 
{: important}
