---

copyright:
  years: 2022, 2025
lastupdated: "2025-07-14"

keywords: bandwidth metering, bandwidth pools

subcollection: bandwidth-metering

---

{{site.data.keyword.attribute-definition-list}}

# FAQ for bandwidth metering
{: #faqs}

You can review answers to some frequently asked questions about bandwidth metering.
{: shortdesc}

## How is bandwidth metering priced?
{: #price-points}
{: faq}

Public bandwidth egress (or bandwidth allocation) pricing depends on regions. Public bandwidth usage over GB allocation is charged per GB. Inbound data transfers are free.

The Charge metrics for Public bandwidth usage for classic are listed in the following table:

| Charge Metric    | Cost  |
|---------------|-----------|
| Data transfer within zone | Provided |
| Data transfer between zones in the same region | Provided |
| Data transmitted: 250 GB | Provided |
| Data transmitted: 1000 GB GB | Provided |
| Data transmitted: 5000 GB | Provided |
| Data transmitted: 10000 GB | Provided |
| Data transmitted: 20000 GB | Provided |
| Overage Rate (per GB) | $0.09/GB |
{: caption="Charge Metric for Public bandwidth usage in North America" caption-side="top"}
{: #northamerica}
{: tab-title="North America"}
{: tab-group="charge-metrics"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Charge Metric    | Cost  |
|---------------|-----------|
| Data transfer within zone | Provided |
| Data transfer between zones in the same region | Provided |
| Data transmitted: 250 GB | Provided |
| Data transmitted: 1000 GB | Provided |
| Data transmitted: 5000 GB | Provided |
| Data transmitted: 10000 GB | $725.00 |
| Data transmitted: 20000 GB | $1,550.00 |
| Overage Rate (per GB) | $0.18/GB |
{: caption="Charge Metric for Public bandwidth usage in South America" caption-side="top"}
{: #southamerica}
{: tab-title="South America"}
{: tab-group="charge-metrics"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Charge Metric    | Cost  |
|---------------|-----------|
| Data transfer within zone | Provided |
| Data transfer between zones in the same region | Provided |
| Data transmitted: 250 GB | Provided |
| Data transmitted: 1000 GB | Provided |
| Data transmitted: 5000 GB | Provided |
| Data transmitted: 10000 GB | Provided |
| Data transmitted: 20000 GB | Provided |
| Overage Rate (per GB) | $0.09/GB |
{: caption="Charge Metric for Public bandwidth usage in Europe" caption-side="top"}
{: #europe}
{: tab-title="Europe"}
{: tab-group="charge-metrics"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Charge Metric    | Cost  |
|---------------|-----------|
| Data transfer within zone | Provided |
| Data transfer between zones in the same region | Provided |
| Data transmitted: 250 GB | Provided |
| Data transmitted: 1000 GB | Provided |
| Data transmitted: 5000 GB | Provided |
| Data transmitted: 10000 GB | $450.00 |
| Data transmitted: 20000 GB | $950.00 |
| Overage Rate (per GB) | $0.11/GB |
{: caption="Charge Metric for Public bandwidth usage in Asia Pacific and Australia" caption-side="top"}
{: #asia-pacific}
{: tab-title="Asia Pacific"}
{: tab-group="charge-metrics"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

## What IMS permissions do I need to view and change bandwidth allocations (or add and remove devices to and from bandwidth pools)?
{: #bw-permissions}
{: faq}

The `BANDWIDTH_MANAGE` IMS infrastructure classic permission is the only required permission for bandwidth metering. After you allow this permission, you can complete the following actions:
 - Create a bandwidth pool
 - Move a device into or out of a pool
 - Void a device’s move into a pool
 - Cancel a pool

Certain actions pertaining to bandwidth pools, including visibility, might be constrained based on device-level permission. Reconcile your device-level permissions on specific devices to manage their bandwidth and membership in pools.
{: note}

## Why don't I see the same number of devices as displayed on the devices count?
{: #bw-device-count}
{: faq}

This issue might be due to permission restrictions because some users do not have permission to view specific devices. This issue might also be the result of devices that were reclaimed in the middle of the billing cycle, but are still contributing to the cost of the pool.

## What kind of devices generate bandwidth?
{: #bw-devices-generating-bandwidth}
{: faq}

Compute devices use bandwidth. For example, devices that generate bandwidth include bare metal servers, virtual servers, firewalls (FSA 10G), and Netscaler devices.

## Why doesn't the allocation display the same value that I ordered?
{: #bw-allocation-value-differs}
{: faq}

The allocation that is shown is related to the proration policy. For example, imagine that you order 20 TB of bandwidth on the 15th of the month. The allocation that is shown on the bandwidth summary page will show 10 TB until the next billing cycle. Then, the allocation displays the full amount of what was ordered.

## What is the maximum number of devices that I can attach to a bandwidth pool?
{: #bw-max-number-vsi}
{: faq}

You can attach an unlimited number of devices to a bandwidth pool.

## Is there a charge for traffic on the Classic Private Network?
{: #bw-classic-traffic-charge}
{: faq}

There is no charge for traffic between Virtual Servers for Classic or Bare Metal Servers for Classic, on the Classic Private network, within the same Classic account.

## Where do I find detailed analytics about my bandwidth usage on particular devices?
{: #bw-usage-analytics}
{: faq}

There are bandwidth graphs per device in the {{site.data.keyword.cloud_notm}} console, but these graphs only shows bandwidth use over time. They don't provide information about which IP addresses or ports are using bandwidth. Depending on your operating system or device, you can install tools or utilize pre-installed tools to monitor the per-IP and per-port details of your traffic.

If you need help installing or using these tools, or if you can't locate the bandwidth graphs per device in the portal, contact {{site.data.keyword.cloud_notm}} support.
