---
title: Configuration Wizard won’t connect to a provided server and database.
description: >-
  This article explains how to handle issue when Configuration Wizard is not
  able to connect to a provided server and database.
author: Mia Tomaić
date: 19/5/2017
---

# Configuration Wizard -Connect to server and database

## Problem:

The SQL Server Browser service is not running. When this service is not running you cannot connect to named instances.

## Solution:

The SQL Server Browser service needs to be up and running.

1. Open **SQL Server Configuration Manager** on your SQL server.
2. Click on SQL Server Services. Find the **SQL Server** Browser service, right-click on it and press **Start**.
3. Do not forget to [allow inbound traffic on TCP Port 1434](https://github.com/SysKitTeam/docs-spdockit/tree/8b06dc9182659a72e14285486dc7b3af590ff348/faq/faq/troubleshooting-sql-server-connection/inbound-traffic.md).
