# Azure Network Watcher Lab: Instructions

> **Microsoft Ignite lab** | Session code: `[Add session code]`

Welcome! This folder contains the step-by-step instructions for the **Azure Network Watcher** hands-on lab. In this lab you fix real network problems using only **Azure Network Watcher**.

Whether you're sitting in the lab room at Ignite or following along online, start here to see what the lab covers and where to go next.

<!-- TODO: Add a lab overview video or banner image here (optional) -->
<!-- ![Azure Network Watcher Lab](./media/00-lab-banner.png) -->

---

## What you'll do

In this lab, you'll:

- **See** your network and the health of your resources (Topology)
- **Proactively monitor** connectivity with one click (Connection Monitor)
- **Diagnose and fix** connectivity issues (Connection Monitor, Connection Troubleshoot)
- **Investigate** Private Link traffic (VNet flow logs, Traffic Analytics)
- **Tighten** security with recommended rules (Security Rule Recommendation)

---

## Lab contents

| # | Module | What you'll learn | Tools | Time |
|---|---|---|---|---|
| 00 | [Introduction](./00-Introduction.md) | How the lab works, sign-in and conventions | Azure portal | 5 min |
| 01 | [Network Visualization and Enable Monitoring](./01-Network-Visualization-and-Enable-Monitoring.md) | See your network and resource health; turn on monitoring in one click | Topology, Connection Monitor | 5-10 min |
| 02 | [Monitor and Troubleshoot Connectivity Issues](./02-Monitor-and-Troubleshoot-Connectivity-Issues.md) | Find SNAT port exhaustion; find and fix a route that blocks traffic | Connection Monitor, Azure Firewall metrics, Connection Troubleshoot | 10-15 min |
| 03 | [Intro to Flow Logs and PLS Support](./03-Intro-to-Flow-Logs-and-PLS-Support.md) | Find who's overloading a Private Link Service and which connection was dropped | VNet flow logs, Traffic Analytics, Azure Workbooks | 10 min |
| 04 | [Traffic Analytics for Rule Recommendations](./04-Traffic-Analytics-for-Rule-Recommendations.md) | Generate least-privilege NSG rules from real traffic | Security Rule Recommendation (Traffic Analytics) | 5-10 min |

The lab has two parts:

- **Part 1: Connectivity monitoring and troubleshooting** covers modules 01 and 02.
- **Part 2: Traffic monitoring** covers modules 03 and 04.

---

## How to use these instructions

### If you're in the lab room

1. Sign in to the lab virtual machine with the credentials shown in your lab environment.
2. Open [00-Introduction](./00-Introduction.md) and work through the modules in order.
3. Use the credentials in the **Resources** tab of the lab environment to sign in to the Azure portal.

### If you're following along online

You don't need a lab environment to learn from this lab. Each module includes:

- 🎬 A **demo video** that walks through the full scenario
- 🖼️ **Screenshots** of the key steps and expected results
- ✅ **Checks** that describe what you should see at each step

You can watch the videos and read the steps to see what Network Watcher can do. To try the scenarios yourself, you need your own Azure subscription with the resources described in [00-Introduction](./00-Introduction.md#lab-environment).

<!-- TODO: If you publish deployment templates for the lab environment, link them here. -->

---

## Conventions used in these instructions

| Marker | Meaning |
|---|---|
| ✅ **Check** | What you should see after a step. If you don't see it, read the troubleshooting note under that step. |
| **Key concept** note | Background on how a feature works. |
| **Troubleshooting** tip | What to do if a step doesn't work as expected. |
| **Warning** | Something that's expected to be broken at this point in the lab. |
| **Production tip** | How you'd handle the same problem in a real environment. |

---

## Learn more

- [Azure Network Watcher documentation](https://learn.microsoft.com/en-us/azure/network-watcher/)
- [VNet flow logs overview](https://learn.microsoft.com/en-us/azure/network-watcher/vnet-flow-logs-overview)

---

**Next:** [00 - Introduction](./00-Introduction.md) ➡️
