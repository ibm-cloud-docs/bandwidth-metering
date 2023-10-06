---

copyright:
  years: 2022, 2023
lastupdated: "2023-10-06"

keywords: bandwidth metering, bandwidth pools

subcollection: bandwidth-metering

---

{{site.data.keyword.attribute-definition-list}}

# Deleting bandwidth pools
{: #how-to-delete-bw-pools}
{: ui}

To delete a bandwidth pool by using the UI, follow these steps:

1. From your browser, open the [{{site.data.keyword.cloud_notm}} console](/login){: external} and log in to your account.
1. Select the Navigation menu ![Navigation menu](../icons/icon_hamburger.svg), then click **Classic Infrastructure**.
1. Select **Network > Bandwidth > Pools**.
1. Locate the bandwidth pool that you want to cancel. Use the **Region** and **Overage Status** filters as necessary.
1. Click the Actions menu ![Actions menu](../icons/action-menu-icon.svg) for the bandwidth pool and select **Delete**.
1. Acknowledge the scheduled cancellation date, and click **Delete**.

   The pool remains active and continues to meter until it is permanently deleted at the end of your billing cycle. 
   {: note}

1. Select the icon tooltip next to the device name in your bandwidth pool's device table to check the scheduled cancellation date of the bandwidth pool or to unschedule the bandwidth pool deletion. For more information, see [Unscheduling deletion of bandwidth pools](/docs/bandwidth-metering?topic=bandwidth-metering-how-to-unschedule-deletion-bw-pools&interface=ui).

Alternatively, you can access the bandwidth pool's details page to delete a bandwidth pool. In the upper right of the bandwidth pool's details page, click the **Actions** menu ![Actions menu](../icons/action-menu-icon.svg), then click **Delete**.
{: note}
