# Ocracle Cloud Infrastractue (OCI)

> Price \* 730 = X (Monthly Expense)

> Price in OCI = 0.03 $ * 730 = 21.9 $

## Data Transfer Cost

- Data-in is Free (ingress)
- Data Going-out Costs Money (egress)
- Data Transfer With in the same availability Domain is FREE. - (With in the AD between Subnets or VNCs is free)
- Data Transfer between Availability domain's in the Same region is Free. - (Between 3 AD of a Region is free)
- Data Transfer between Regions will Result in a Charge for Data leaving the region - (Between Different Region From Phoenix to Mumbai)

---

> ### Block Volume Pricing

There are two thing that needs to be considered with Block Vloume Pricing

```
VPU stands for Volume Performance Unit

1. Storage Cost
2. Performance Cost

Storage Cost
--------------------------------------------
 GB Stored Capacity / Month
	 $ 0.255

Performance Cost
--------------------------------------------
 Performance Units Per GB / Month
	 0  VPU at $ 0 Lower Cost
	 10 VPU at $ 0.017 for Balanced
	 20 VPU at $ 0.034 for High Performance
```

> ### Resource Tag

You Can Tag Resource Such as Compute, Storage & Database. Tagging allows us to filter resource and can be used in cost analysis to quickly determine cost

![ResourceTagImage](https://i.ibb.co/F5NHHpt/resorce-Tag.png)

# Cost Analysis

OCI Cost analysis will help you visualize your onging cost.

You can Filter based on Compartments, Tagged Resources and Start and End date.

> <div align="center">Amount Used</div>

![costUsed](https://i.ibb.co/cgpndjf/costUsed.png)

> <div align="center">Breakdown of Useage</div>

![costUsed](https://i.ibb.co/yQymC5D/cost-Break-Down.png)

> ### Useage Report

Get a Granular view of your Spending or Find ways to save. Download a **CSV** or Use the **OCI API** to access detailed billing information.

Cost report is automatically generated Daily, and is Stored in an _Oracle-Owned_ Sobject Storage Bucket.

Cost Report Generally Contain _24 Hours of Useage Data,_ although occasionally a cost report may Contain Late-Arriving data that is older than 24 Hours.

![useageReportFull](https://i.ibb.co/hfBfXMd/useage-Report.png)

# Free Tiers

> ### Always Free

- 2 Oracle Autonomous DataBases.
- 2 OCI Compute VMs and 1/8 OCPUand 1GB.
- 2 Block Volumes 100GB Total.
- Object Storage 10GB.
- Archive Storage 10GB.
- Load Balancer.
- Data-In (ingress) is Free.
- Monitoring and notification.
- OCI Developer - Automated CI/CD Workflow.

> ### 30-Day Free Tier

- 300\$ Credit Valid for 30Day.
- Upto Eight Instances across all available Services.
- Upto 5TB of Storage

All the SServices are Listed Below
![30DayFreeTier](https://i.ibb.co/Vt2hFJ9/30day-Free-Tier.png)

> ### Oracle Market Place

_Oracle Market Place_ are Managed VM Images or Stacks from **Third-Party** Vendors that are _Free or Paid_ that you can Launch.

![oracleMarketPlace](https://i.ibb.co/xgypbJq/market-Place.png)

# Oracle SLA

**Oracle's Service Level Agreement (SLA)** is guarantee of _Performance, Availability, Manageability_ of Service.

> ### Availability SLAs

- 99.99% uptime Computer running in One AD Region with Measurements of Region Unavailability.
- 99.95% uptime Computer in Multiple FDs in a Single AD.

| Category      | 10% Region Unavailability | 25% Region Unavailability | 10% Ad Unavailability | 25% Ad Unavailability |
| ------------- | ------------------------- | ------------------------- | --------------------- | --------------------- |
| Compute       | 99.9%                     | 99.9%                     | 99.95%                | 99%                   |
| Block Vloumes | 99.9%                     | 99%                       |                       |                       |

---

| Category       | SLA Breach 10% | SLA Breach 25% |
| -------------- | -------------- | -------------- |
| Object Storage | 99.9%          | 99%            |
| Fast Connect   | 99.9%          | 99%            |

> ### Manageability SLAs

| Category      | SLA Breach 10% | SLA Breach 25% |
| ------------- | -------------- | -------------- |
| Compute       | 99.9%          | 99%            |
| Block Vloumes | 99.9%          | 99%            |
| DataBase      | 99.9%          | 99%            |

> ### Performance SLAs

| Category      | SLA Breach 10% | SLA Breach 25% |
| ------------- | -------------- | -------------- |
| Compute       | 99.9%          | 99%            |
| Block Vloumes | 99.9%          | 99%            |
| DataBase      | 99.9%          | 99%            |

> ## Service Limits
>
> When you sign-up for OCI, **a Set of Service Limits is configured for your tenancy.** The service limits is the quota or allowance set on a resource.

- eg Your Tenancy is allowed a Maximum Number of Compute Instances per AD.

These Limits are generally Established with your Oracle sales representative when your purchase _Oracle Cloud Infrastructure_. If you didn't Establish your limits with your oracle sales representative, or if you signed up through the Oracle Store, Default or Trail limits are set for your tenancy.

These limits may be increased for you automatically based on your Oracle Cloud Infrastructure resource useage and account standing. **You can also request a service limit increase.**

# Support

Oracle has a Support Plan called as **Premier Support**
Rapid Resolution through _24/7 access to the Oracle Knowledgebase, Techinical Support, Auto Service Request (ASR)_, Priority Request Handling, Remote Dignostics, and Two Hour Onsite Hardware Service.

Oracle has a live chat in the oracle Console.

> You have to talk to a sales person to get a quote, The premier Support pricing is not clear or easily accessible.\*
