# 00 - Introduction

⬅️ [Back to README](./README.md) | **Next:** [01 - Network Visualization and Enable Monitoring](./01-Network-Visualization-and-Enable-Monitoring.md) ➡️

---


## About this lab

In this lab, you'll fix real network problems using only **Azure Network Watcher**. Network Watcher is a set of tools in Azure that helps you monitor, diagnose and view metrics for the resources in your virtual networks.

You'll play the role of an engineer who has just inherited an Azure environment. Things are broken, inventory is being partially monitored, and customers are reporting problems. Over four scenarios, you'll map the environment, turn on monitoring, find and fix two outages, investigate Private Link traffic and tighten your security rules.

---

## The tools you'll use

| Tool | What it does | Used in |
|---|---|---|
| **Topology** | Shows every resource in your network, how they connect and their health and key metrics in one view | Module 01 |
| **Connection Monitor** | Continuously tests connectivity between endpoints and shows where and why it fails | Modules 01, 02 |
| **Connection Troubleshoot** | Runs a one-time check between a source and destination and finds the potential failure cause | Module 02 |
| **VNet flow logs** | Captures information about IP traffic flowing through a virtual network | Module 03 |
| **Traffic Analytics** | Enriches flow logs and makes them easy to query and visualize | Modules 03, 04 |
| **Security Rule Recommendation** | Uses real traffic data to recommend tighter network security group (NSG) rules | Module 04 |

---


## Before you start

### If you're in the lab room

1. Sign in to the lab virtual machine with the password shown in your lab environment.
2. Sign in with the username and Temporary Access Pass (TAP) shown in the **Resources** tab of your lab environment when the Sign In popup comes.
3. Open the Azure portal at [https://portal.azure.com](https://portal.azure.com/#home).
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
