---

copyright:
  years: 2022, 2023
lastupdated: "2023-12-08"

keywords: bandwidth metering

subcollection: bandwidth-metering

---

{{site.data.keyword.attribute-definition-list}}

# Managing bare metal server bandwidth
 {: #how-to-add-and-upgrsade-bare-metal-server-bw}

You can add bandwidth when you provision Bare Metal Servers for Classic. You can purchase larger allocations at a reduced cost compared to the overage rate.
{: shortdesc}

## Selecting bandwidth while provisioning bare metal servers
{: #how-to-add-bw-to-bare-metal}
{: ui}

To add bandwidth when you provision a bare metal server in the UI, follow these steps:

1. From your browser, open the [{{site.data.keyword.cloud_notm}} console](/login){: external} and log in to your account.
1. Select **Catalog** from the menu bar on the header.
1. Select the **Bare Metal Servers for Classic** tile and provision your new virtual server instance. To learn more, see [Selecting from the most popular servers](/docs/bare-metal?topic=bare-metal-bm-select-popular-servers).
1. In the Network interface section, find the **Public egress - bandwidth** option. Then, select the amount of bandwidth that you want to add to your server's allocation. Bandwidth is offered in tiers.

   Public bandwidth usage over GB allocation is charged per GB. Also, public bandwidth egress (or bandwidth allocation) pricing depends on regions as indicated in **Pricing plans by region** on the [Bandwidth packages from IBM Cloud](https://www.ibm.com/cloud/bandwidth){: external} website.
   {: important}

## Upgrading bandwidth while provisioning bare metal servers
{: #how-to-upgrade-bw-bare-metal}
{: ui}

To upgrade bandwidth on a bare metal server by using the UI, follow these steps:

1. From your browser, open the [{{site.data.keyword.cloud_notm}} console](/login){: external} and log in to your account.
1. Select the Navigation menu ![Navigation menu](../icons/icon_hamburger.svg), then click **Classic Infrastructure**.
1. Select **Devices > Device list**.
1. Click the name of the bare metal server that you are modifying.
1. On the device's details page, find the VLAN Trunking section, then the Public bandwidth allocation section. Next to the Current billing cycle bandwidth allocation details, click **Modify**. 
1. Select a bandwidth upgrade option, then select if you want to update the device immediately or schedule the update for a later date and time. 
1. Add any notes, then click **Continue**. 

A 0 GB bandwidth allocation indicates a fully metered device, and an unspecified bandwidth allocation indicates a device with unlimited bandwidth. Both fully metered devices and devices with unlimited bandwidth are ineligible for bandwidth pools.
{: note}

## Pool definitions for bare metal servers
{: #pool-definitions-bw-bare-metal}
{: ui}

The pool definitions are listed in the following table:

| Pool      | Location  |
|------------------|-------|
| Brazil | SAO01 |
| | SAO04 |
| | SAO05 |
| Dallas  | DAL05 |
| | DAL06 |
| | DAL09 |
| | DAL10 |
| | DAL12 |
| | DAL13 |
| Mexico         | MEX01 |
| Montreal       | MON01 |
| San Jose       | SJC01 |
|       | SJC03 |
|       | SJC04 |
| Toronto        | TOR01 |
| | TOR04 |
| | TOR05 |
| Washington DC | WDC01 |
|  | WDC04 |
|  | WDC06 |
|  | WDC07 |
{: caption="Table 1. Pool definitions North and South America" caption-side="top"}
{: #americas}
{: tab-title="Americas"}
{: tab-group="pool-locations"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Pool  | Location  |
|--------------|-------|
|Amsterdam  | AMS01 |
|           | AMS03 |
| Frankfurt | FRA02 |
| | FRA04 |
| | FRA05 |
| London  | LON02 |
| | LON04 |
| | LON05 |
| | LON06 |
| Madrid | MAD02 |
| | MAD04 |
| | MAD05 |
| Milan | MIL01 |
| Paris | PAR01 |
{: caption="Table 1. Pool definitions Europe" caption-side="top"}
{: #europe}
{: tab-title="Europe"}
{: tab-group="pool-locations"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Pool | Location  |
|--------------|-------|
| Australia | SYD01 |
| | SYD04 |
| | SYD05 |
| Hong Kong S.A.R. of the PRC | HKG02 |
| India | CHE01 |
| Japan         | OSA21 |
| | OSA22 |
| | OSA23 |
| | TOK02 |
| | TOK04 |
| | TOK05 |
| Singapore | SNG01 |
{: caption="Table 1. Pool definitions Asia Pacific" caption-side="top"}
{: #asia-pacific}
{: tab-title="Asia Pacific"}
{: tab-group="pool-locations"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

