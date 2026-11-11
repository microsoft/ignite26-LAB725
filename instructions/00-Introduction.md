# 00 - Introduction

⬅️ [Back to README](./README.md) | **Next:** [01 - Network Visualization and Enable Monitoring](./01-Network-Visualization-and-Enable-Monitoring.md) ➡️

---

## 🎬 Demo video

<!-- TODO: Replace the link below with the demo video URL -->
[Watch the introduction video](VIDEO_LINK_00_INTRODUCTION)

---

## About this lab

In this lab, you'll fix real network problems using only **Azure Network Watcher**. Network Watcher is a set of tools in Azure that helps you monitor, diagnose and view metrics for the resources in your virtual networks.

You'll play the role of an engineer who has just inherited an Azure environment. Things are broken, nothing is being monitored, and customers are reporting problems. Over four scenarios, you'll map the environment, turn on monitoring, find and fix two outages, investigate Private Link traffic and tighten your security rules.

---

## The tools you'll use

| Tool | What it does | Used in |
|---|---|---|
| **Topology** | Shows every resource in your network, how they connect and their health and key metrics in one view | Module 01 |
| **Connection Monitor** | Continuously tests connectivity between endpoints and shows where and why it fails | Modules 01, 02 |
| **Connection Troubleshoot** | Runs a one-time check between a source and destination and finds the hop that fails | Module 02 |
| **VNet flow logs** | Captures information about IP traffic flowing through a virtual network | Module 03 |
| **Traffic Analytics** | Enriches flow logs and makes them easy to query and visualize | Modules 03, 04 |
| **Security Rule Recommendation** | Uses real traffic data to recommend tighter network security group (NSG) rules | Module 04 |

---

## Lab environment

<!-- TODO: Add a lab architecture diagram -->
![Lab architecture](./media/00-lab-architecture.png)

The lab environment includes these key resources:

| Resource | Type | Used in |
|---|---|---|
| `agw-storefront-waf` | Application Gateway | Module 01 |
| `vnet-internet-client` | Virtual network | Module 01 |
| `law-connection-monitor` | Log Analytics workspace | Module 01 |
| `cm-snatrepro-firewall-snat` | Connection Monitor | Module 02 |
| `afw-snatrepro` | Azure Firewall | Module 02 |
| `vm-udr-blocked`, `vm-udr-target` | Virtual machines | Module 02 |
| `rt-udr-blocked` | Route table | Module 02 |
| `customervnet`, `partnervnet`, `vendorvnet` | Customer virtual networks connecting to a Private Link Service | Module 03 |
| `IgniteWB` | Azure workbook | Module 03 |
| `nsg10` | Subnet scope for rule recommendations | Module 04 |

Resources are deployed in the **Denmark East** and **Sweden Central** regions.

---

## Before you start

### If you're in the lab room

1. Sign in to the lab virtual machine with the password shown in your lab environment.
2. Open the Azure portal at [https://portal.azure.com](https://portal.azure.com/#home).
3. Sign in with the username and Temporary Access Pass (TAP) shown in the **Resources** tab of your lab environment.

> [!NOTE]
> Some steps use a URL that includes your **lab instance ID**, for example `http://checkout-<lab-instance-id>.swedencentral.cloudapp.azure.com`. In the lab environment, these links are filled in for you.

### If you're following along online

Watch the demo video at the top of each module and follow the screenshots. To run the scenarios in your own subscription, you need the resources listed in [Lab environment](#lab-environment).

---

## How each scenario works

- Each scenario starts with the **problem**, your **goal** and the **tools** you'll use.
- Each ✅ **Check** tells you what you should see. If you don't see it, follow the **Troubleshooting** tip under that step.
- Each scenario takes about **5-10 minutes**. You can do them in order, at your own pace.

---

## Lab outline

### Part 1: Connectivity monitoring and troubleshooting

- [01 - Network Visualization and Enable Monitoring](./01-Network-Visualization-and-Enable-Monitoring.md)
- [02 - Monitor and Troubleshoot Connectivity Issues](./02-Monitor-and-Troubleshoot-Connectivity-Issues.md)

### Part 2: Traffic monitoring

- [03 - Intro to Flow Logs and PLS Support](./03-Intro-to-Flow-Logs-and-PLS-Support.md)
- [04 - Traffic Analytics for Rule Recommendations](./04-Traffic-Analytics-for-Rule-Recommendations.md)

---

⬅️ [Back to README](./README.md) | **Next:** [01 - Network Visualization and Enable Monitoring](./01-Network-Visualization-and-Enable-Monitoring.md) ➡️
