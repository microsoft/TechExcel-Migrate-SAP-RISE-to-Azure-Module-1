---
title: Introduction
layout: home
nav_order: 1
---

# TechExcel: Migrate SAP RISE to Azure

## Architecture

![vqqvwh7n.jpg](/media/vqqvwh7n.jpg)

SAP provides the Gateway Demo system so that users can experiment and interact with SAP data. For this lab, you'll connect to the SAP Gateway Demo system by using the GWSAMPLE_BASIC OData service. The service includes a simple data model with entities like Products, Sales Orders, and Business Partners. 

You'll create a Microsoft Fabric pipeline that uses the Copy Data assistant to copy data from the SAP demo system to an Azure SQL database. 
Then, you'll create a Copilot agent that uses the database as a knowledge source to answer questions.


## Exercises

This lab has the following exercises:
 - Create an SAP account and configure SAP resources
 - Create and configure Microsoft Fabric resources
 - Create, configure, and test a Copilot agent

## Prerequisites

To run this lab you'll need:

- Access to a work or personal email account 
- An SAP account and access to the SAP Gateway Demo system
- Access to Microsoft Fabric and Fabric capacity licensing
- Access to Azure and the ability to create resources including an Azure OpenAI Service instance
- Access to Copilot Studio to create Copilot agents
