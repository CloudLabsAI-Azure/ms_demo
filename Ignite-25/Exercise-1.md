## Exercise 1: Lakehouse Setup & Data Orchestration with Azure Databricks and Lakeflow declarative pipelines

In this exercise, you will build a Lakehouse environment using Azure Databricks and Lakeflow to orchestrate and transform data. You’ll load data into Unity Catalog, create ETL pipelines, and explore AI-driven insights, lineage, and profiling.

### Task 1.1: Set Up Azure Databricks Environment and load data into Unity Catalog

1. Click the following link to open the Databricks workspace: **<inject key="Databricks1" />**

2. On the Databricks workspace page, select the **Catalog**, click on **zava_unity_catalog**, and then choose **schema-1957817**.

   ![Task-2.3_1.png](./media/up1.png)

3. From the left navigation, select **Workspace**, expand **Workspace**,**Shared** click on **Analytics with ADB** folder, and click on **01.1-DLT-fraud-detection-SQL**.

    ![Task-2.3_1.png](./media/up2.png)

4. Explore the notebook review the code cells, markdown explanations, and outputs to understand the workflow and logic.

    ![Task-2.3_1.png](./media/notebook.png)

### Task 1.2: Create ETL pipeline for Data Transformation

1. From the left navigation pane, select **Jobs & Pipelines**, then choose **ETL Pipeline**.

   ![Task-2.3_1.png](./media/ex2.png)

2. View the ETL pipeline explore the pipeline and review the **pipeline graph** to understand the data flow and transformation process.

   ![Task-2.3_1.png](./media/graph.png)


### Task 1.3: Generate column-level insights with AI Suggested Descriptions, then explore data lineage, table update history, and profiling in Azure Databricks.

1. Click on **Catalog** then expand **zava_unity_catalog** and **schema-1957817**, expand **Tables**, and select the **bronze_transactions** table.

![Task-2.3_1.png](./media/up3.png)

2. click on **AI Generate** to automatically generate comments for the table columns.

> Note: If a pop-up appears with the message **Saving comments in bulk could be slow**, click Continue.

![Task-2.3_1.png](./media/up4.png)

> Note : If the AI Generate option is disabled, it means AI generation is already enabled. You can proceed with the next steps.

3. Review the AI-generated comments for the columns, then click on **close** and in Unsaved Changes select **Discard changes**.

 > Note : Don't click on Save all.

 ![Task-2.3_1.png](./media/up5.png)  

4. To view the lineage, select the **Lineage** tab and review the details in that section. Additionally, click on **See Lineage Graph** to view a visual representation of the data flow.

![Task-2.3_1.png](./media/ex1t3i3.png) 

