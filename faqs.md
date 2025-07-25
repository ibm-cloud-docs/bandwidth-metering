---

copyright:
  years: 2022, 2025
lastupdated: "2025-07-25"

keywords: bandwidth metering, bandwidth pools

subcollection: bandwidth-metering

---

{{site.data.keyword.attribute-definition-list}}

# FAQ for Classic bandwidth metering
{: #faqs}

You can review answers to some frequently asked questions about bandwidth metering.
{: shortdesc}

## How is bandwidth metering priced?
{: #price-points}
{: faq}

Public bandwidth egress (or bandwidth allocation) pricing depends on regions. Public bandwidth usage over GB allocation is charged per GB. Inbound data transfers are included for free. 

Data transfer between zones and nodes is included for free only when the private network is used, not the public network.
{: note}

The Charge metrics for Public bandwidth usage for classic are listed in the following table:

| Data Type | Charge Metric | Cost |
|---------------|-----------|
| VSI | 250 GB | $0 (included) |
| VSI | 1000 GB GB | $45.00 |
| VSI | 5000 GB | $370.00 |
| VSI | 10000 GB | $682.00 |
| VSI | 20000 GB | $999.00 |
| VSI | Overage Rate (per GB) | $0.09/GB |
| Bare Metal | 250 GB | $0 (included) |
| Bare Metal | 1000 GB GB | $0 (included) |
| Bare Metal | 5000 GB | $0 (included) |
| Bare Metal | 10000 GB | $0 (included) |
| Bare Metal | 20000 GB | $0 (included) |
| Bare Metal | Overage Rate (per GB) | $0.09/GB |
{: caption="Charge Metric for Public bandwidth usage in North America" caption-side="top"}
{: #northamerica}
{: tab-title="North America"}
{: tab-group="charge-metrics"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Data Type | Charge Metric | Cost |
|---------------|-----------|
| VSI | 250 GB | $0 (included) |
| VSI | 1000 GB | $90.00 |
| VSI | 5000 GB | $740.00 |
| VSI | 10000 GB | $1,364.00 |
| VSI | 20000 GB | $1,998.00 |
| VSI | Overage Rate (per GB) | $0.18/GB |
| Bare Metal | 250 GB | $0 (included) |
| Bare Metal | 1000 GB | $0 (included) |
| Bare Metal | 5000 GB | $0 (included) |
| Bare Metal | 10000 GB | $725.00 |
| Bare Metal | 20000 GB | $1,550.00 |
| Bare Metal | Overage Rate (per GB) | $0.18/GB |
{: caption="Charge Metric for Public bandwidth usage in South America" caption-side="top"}
{: #southamerica}
{: tab-title="South America"}
{: tab-group="charge-metrics"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Data Type | Charge Metric | Cost |
|---------------|-----------|
| VSI data | 250 GB | $0 (included) |
| VSI data | 1000 GB | $45.00 |
| VSI data | 5000 GB | $370.00 |
| VSI data | 10000 GB | $682.00 |
| VSI data | 20000 GB | $999.00 |
| VSI | Overage Rate (per GB) | $0.09/GB |
| Bare Metal | 250 GB | $0 (included) |
| Bare Metal | 1000 GB | $0 (included) |
| Bare Metal | 5000 GB | $0 (included) |
| Bare Metal | 10000 GB | $0 (included) |
| Bare Metal | 20000 GB | $0 (included) |
| Bare Metal | Overage Rate (per GB) | $0.09/GB |
{: caption="Charge Metric for Public bandwidth usage in Europe" caption-side="top"}
{: #europe}
{: tab-title="Europe"}
{: tab-group="charge-metrics"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Data Type | Charge Metric | Cost |
|---------------|-----------|
| VSI | 250 GB | $0 (included) |
| VSI | 1000 GB | $60.00 |
| VSI | 5000 GB | $492.00 (included) |
| VSI | 10000 GB | $907.00 |
| VSI | 20000 GB | $1,329.00 |
| VSI | Overage Rate (per GB) | $0.11/GB |
| Bare Metal | 250 GB | $0 (included) |
| Bare Metal | 1000 GB | $0 (included) |
| Bare Metal | 5000 GB | $0 (included) |
| Bare Metal | 10000 GB | $450.00 |
| Bare Metal | 20000 GB | $950.00 |
| Bare Metal | Overage Rate (per GB) | $0.11/GB |
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
