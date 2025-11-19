# Ignite25-LAB335-analytics-and-ai-with-azure-databricks-ai-foundry-and-copilot
**The estimated time to complete this lab is 50-60 minutes.**

Azure Databricks in Action: Unified Al & Analytics Across Microsoft
The estimated time to complete this lab is 50-60 minutes.

DISCLAIMER

This presentation, demonstration, and demonstration model are for informational purposes only and (1) are not subject to SOC 1 and SOC 2 compliance audits, and (2) are not designed, intended or made available as a medical device(s) or as a substitute for professional medical advice, diagnosis, treatment or judgment. Microsoft makes no warranties, express or implied, in this presentation, demonstration, and demonstration model. Nothing in this presentation, demonstration, or demonstration model modifies any of the terms and conditions of Microsoft's written and signed agreements. This is not an offer and applicable terms and the information provided are subject to revision and may be changed at any time by Microsoft.

This presentation, demonstration, and demonstration model do not give you or your organization any license to any patents, trademarks, copyrights, or other intellectual property covering the subject matter in this presentation, demonstration, and demonstration model.

The information contained in this presentation, demonstration and demonstration model represents the current view of Microsoft on the issues discussed as of the date of presentation and/or demonstration, for the duration of your access to the demonstration model. Because Microsoft must respond to changing market conditions, it should not be interpreted to be a commitment on the part of Microsoft, and Microsoft cannot guarantee the accuracy of any information presented after the date of presentation and/or demonstration and for the duration of your access to the demonstration model.

No Microsoft technology, nor any of its component technologies, including the demonstration model, is intended or made available as a substitute for the professional advice, opinion, or judgment of (1) a certified financial services professional, or (2) a certified medical professional. Partners or customers are responsible for ensuring the regulatory compliance of any solution they build using Microsoft technologies.

Copyright

© 2024 Microsoft Corporation. All rights reserved. 

By using this demo/lab, you agree to the following terms:

The technology/functionality described in this demo/lab is provided by Microsoft Corporation for purposes of obtaining your feedback and to provide you with a learning experience. You may only use the demo/lab to evaluate such technology features and functionality and provide feedback to Microsoft. You may not use it for any other purpose. You may not modify, copy, distribute, transmit, display, perform, reproduce, publish, license, create derivative works from, transfer, or sell this demo/lab or any portion thereof.

COPYING OR REPRODUCTION OF THE DEMO/LAB (OR ANY PORTION OF IT) TO ANY OTHER SERVER OR LOCATION FOR FURTHER REPRODUCTION OR REDISTRIBUTION IS EXPRESSLY PROHIBITED.

THIS DEMO/LAB PROVIDES CERTAIN SOFTWARE TECHNOLOGY/PRODUCT FEATURES AND FUNCTIONALITY, INCLUDING POTENTIAL NEW FEATURES AND CONCEPTS, IN A SIMULATED ENVIRONMENT WITHOUT COMPLEX SET-UP OR INSTALLATION FOR THE PURPOSE DESCRIBED ABOVE. THE TECHNOLOGY/CONCEPTS REPRESENTED IN THIS DEMO/LAB MAY NOT REPRESENT FULL FEATURE FUNCTIONALITY AND MAY NOT WORK THE WAY A FINAL VERSION MAY WORK. WE ALSO MAY NOT RELEASE A FINAL VERSION OF SUCH FEATURES OR CONCEPTS. YOUR EXPERIENCE WITH USING SUCH FEATURES AND FUNCITONALITY IN A PHYSICAL ENVIRONMENT MAY ALSO BE DIFFERENT

## Overview

![Task-2.3_1.png](./media/Lab535%20Archi.png)

This lab showcases how Azure Databricks, Microsoft Fabric, Copilot Studio, and Azure AI Foundry work together to deliver a cost-effective, performance-optimized, cloud-native analytics solution pattern. he architecture unifies the enterprise data estate, enabling organizations to accelerate data value creation and unlock actionable insights with Microsoft's latest innovations: Azure Databricks, Microsoft Fabric, Azure AI Foundry, and Copilot Studio.

In today's data-driven world, organizations need solutions that seamlessly integrate analytics and AI to deliver actionable insights at scale. This hands-on lab will guide you through building a modern, cloud-native analytics and AI architecture using Microsoft's latest innovations: Azure Databricks, Microsoft Fabric, Azure AI Foundry, and Copilot Studio. You'll work through a real-world scenario featuring Zava, a global retailer acquiring Litware Inc., which introduces a rich set of curated marketing and sales data. This data is processed in Azure Databricks and stored in the gold layer of ADLS, forming the foundation for advanced analytics and AI-driven decision-making. Throughout the lab, you will:

Set up a Lakehouse architecture with Azure Databricks and orchestrate data pipelines using Lakeflow declarative pipelines.
Transform and enrich data with ETL processes, explore data lineage, and leverage AI-powered column-level insights.
Build AI-driven experiences using Genie and Azure AI Foundry, enabling conversational analytics and business Q&A.
Mirror Unity Catalog tables into Microsoft Fabric's OneLake, create semantic models in Direct Lake mode, and visualize insights in Power BI.
Develop low-code automation with Copilot Studio, creating conversational agents that integrate with Teams and respond to business queries like "What's the top-selling product this week?"
By the end of this immersive session, you'll have implemented a scalable, cost-effective, and performance-optimized solution that demonstrates how AI-powered analytics can reshape business outcomes-from data ingestion to intelligent insights and automation.

## Table of Contents

### Exercise 1: Lakehouse Setup & Data Orchestration with Azure Databricks and Lakeflow declarative pipelines

- Task 1: Set Up Azure Databricks Environment and load data into Unity Catalog

- Task 2: Create ETL pipeline for Data Transformation

- Task 3: Generate column-level insights with AI Suggested Descriptions, then explore data lineage, table update history, and profiling in Azure Databricks.

### Exercise 2: AI-Driven Insights with Azure AI Foundry & Genie

- Task 2.1: Create a Databricks Assistant AI/BI Genie

  - Design an assistant that can respond to business queries using curated datasets

- Task 2.2: Use Agent Created Inside AI Foundry with Custom Web App

  - Chat with you data in an custom webapplication

### Exercise 3: Azure Databricks Mirrored Catalog in Microsoft Fabric

- Task 3.1: Mirror Unity Catalog Table into Fabric's OneLake
  - Setup: Create Microsoft Fabric Workspace
  - Create Fabric's mirrored catalog in Fabric

- Task 3.2: Create a semantic model in Direct Lake mode and use Power BI to visualize and generate insights

### Exercise 4: Copilot Studio for Low-Code Automation(Optional)

- Task 4.1: Create an agent and connect Azure Databricks as its knowledge source to support Business Q&A.

  - Build a conversational agent using Copilot Studio Train it to answer questions like "What's the top-selling product this week?"

- Task 4.2: Publish the agent in Microsoft Teams channels and make it accessible to users.
Test and refine bot responses for accuracy and relevance