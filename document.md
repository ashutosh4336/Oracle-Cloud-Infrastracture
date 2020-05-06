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

## Block Volume Pricing

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

## Resource Tag

You Can Tag Resource Such as Compute, Storage & Database. Tagging allows us to filter resource and can be used in cost analysis to quickly determine cost

![ResourceTagImage](https://i.ibb.co/F5NHHpt/resorce-Tag.png)

# Cost Analysis

OCI Cost analysis will help you visualize your onging cost.

You can Filter based on Compartments, Tagged Resources and Start and End date.

> <div align="center">Amount Used</div>

![costUsed](https://i.ibb.co/cgpndjf/costUsed.png)

> <div align="center">Breakdown of Useage</div>

![costUsed](https://i.ibb.co/yQymC5D/cost-Break-Down.png)
