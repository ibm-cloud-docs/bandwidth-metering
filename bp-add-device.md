---

copyright:
  years: 2022, 204
lastupdated: "2024-02-12"

keywords: bandwidth metering

subcollection: bandwidth-metering

---

{{site.data.keyword.attribute-definition-list}}

# Adding devices to bandwidth pools
{: #how-to-add-devices-to-ibm-cloud-bandwidth-pools}
{: ui}

You can add devices to bandwidth pools from the bandwidth summary page or from an individual bandwidth pool's details page.

## Adding devices to bandwidth pools from the bandwidth pools page
{: #how-to-add-devices-bandwidth-pools-page}
{: ui}

If you want to add devices to a bandwidth pool from the bandwidth pools page, follow these steps by using the UI:

1. From your browser, open the [{{site.data.keyword.cloud_notm}} console](/login){: external} and log in to your account.
1. Select the Navigation menu ![Navigation menu](../icons/icon_hamburger.svg), then click **Classic Infrastructure**.
1. Select **Network > Bandwidth > Pools**.
1. In the Bandwidth pools table, locate the Bandwidth pool in which you want to add to add a device. Use the **Region** and **Current Usage** filters as necessary.
1. Click the name of the bandwidth pool to view and edit its details.
1. In the top right of the Devices table, click the **Add** button.
1. In the list of Available devices, locate the device that you want to add to a bandwidth pool. Use the **Type** and **Location** filters as necessary.
   Each device that you add to a bandwidth pool incurs a cost to the pool. For more information, see [FAQs for bandwidth services](/docs/bandwidth-metering?topic=bandwidth-metering-faqs&interface=ui).
   {: note}
1. Check the box beside the devices you want to add to your pool.
1. In the **Summary** section:
    - Review the cost of adding your devices to the pool.
    - Agree to the Terms and Conditions.
    - Click **Add devices to pool**.

## Adding devices to bandwidth pools from the bandwidth summary page
{: #how-to-add-devices-bandwidth-summary-page}
{: ui}

If you want to add devices to a bandwidth pool from the bandwidth summary page, follow these steps by using the UI:

1. From your browser, open the [{{site.data.keyword.cloud_notm}} console](/login){: external} and log in to your account.
1. Select the Navigation menu ![Navigation menu](../icons/icon_hamburger.svg), then click **Classic Infrastructure**.
1. Select **Network > Bandwidth > Summary**.
1. Locate the device that you want to add to a bandwidth pool. Use the **Location** and **Pool** filters as necessary.
   Each device that you add to a bandwidth pool incurs a cost to the pool. For more information, see [FAQs for bandwidth services](/docs/bandwidth-metering?topic=bandwidth-metering-faqs).
   {: note}
1. Under the **Pool** column of the device table, select **Add to pool**.
   Devices that are billed hourly (fully metered) and devices with unlimited allocation are not eligible for bandwidth pools.
   {: note}
1. In the **Add device to a Bandwidth pool** page, view the list of eligible pools.
1. Select an eligible bandwidth pool to add your device to that pool.
1. In the **Summary** section:
    - Review the cost of adding your devices to the pool.
    - Agree to the Terms and Conditions.
    - Click **Add devices to pool**.
