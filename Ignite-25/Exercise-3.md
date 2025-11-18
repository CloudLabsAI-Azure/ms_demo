## Exercise 3: Azure Databricks Mirrored Catalog in Microsoft Fabric

In this exercise, you will integrate Azure Databricks Unity Catalog with Microsoft Fabric’s OneLake using the Mirrored Catalog feature. This enables real-time access to Databricks data in Fabric without duplication. You’ll then create a semantic model in Direct Lake mode and use Power BI with Copilot to visualize, explore, and generate actionable insights on fraudulent transactions.

### Task 3.1: Mirror Unity Catalog Table into Fabric’s OneLake

Mirroring the Azure Databricks Catalog structure in Fabric allows seamless access to the underlying catalog data through shortcuts. This means that any changes made to the data are instantly reflected in Fabric, without the need for data movement or replication. Let’s step into Data Engineer, Eva’s shoes to create a Mirrored Azure Databricks Catalog and analyze the data using T-SQL. 

1. Navigate to the Microsoft Fabric tab on your browser (https://app.fabric.microsoft.com).

2. On the Fabric login page, enter your username **<inject key="AzureAdUserEmail" />** and click **Submit**.

   ![](./media/ws1.png)

2. Click on **Workspaces** from left navigation, then select **Ignite-25**.

     > **Note**: If the workspace isn’t visible, try refreshing the page.

   ![](./media/wst3.png)

3. select **New item** from menu bar.

   ![](./media/wst31.png)

4. In the **New item** window, scroll down and click on **Microsoft Azure Databricks catalog**.

![Task-2.3_2.png](./media/Task-2.3_2.png)

5. When the **New source** window pops up, click on the **Create new connection** radio button.

![Task-2.3_3.png](./media/Task-2.3_3.png)

6. In the URL field enter **<inject key="Databricks2" />**

7. Now, select **Service principal** from 'Authentication kind' dropdown box, and enter the following details.

- Tenant ID: <inject key="Tenant ID" />
- Service principal client ID: <inject key="Service principal client ID" />
- Service principal Key: <inject key="Service principal Key" />

8. click on the **Connect** button.

![Task-2.3_7.png](./media/Task-2.3_7.png)

9. Click on **Next** button.

![Task-2.3_7.1.png](./media/Task-2.3_7.1.png)

10. In the Choose data screen, select the Catalog name as **zava_unity_catalog** from the dropdown box, and select the **fraud-detection** schema if not selected, scroll down then select the checkbox **Automatically sync future catalog changes for the selected schema** (to mirror future tables) if not ticked and click on **Next** button.

![Task-2.3_8.png](./media/Task-2.3_8.png)

11. Enter Name as **zava_unity_catalog_<inject key= "DeploymentID" enableCopy="false"/>** and click on the **Create** button.

 ![Task-2.3_9.png](./media/ig2i.png)

12. Click on the **Monitor catalog** button to track the mirroring status and then close it.

![Task-2.3_10.1.png](./media/Task-2.3_10.1.png)

13. Click on the **View SQL endpoint** button. You can also select the tables to preview data.

![Task-2.3_10.png](./media/Task-2.3_10.png)

### Task 3.2: Create a semantic model in Direct Lake mode and use Power BI to visualize and generate 

1. Select **Ignite-25** workspace from left navigation pane.

   ![](./media/ig1i.png)

2. Click on the filter option in the top-right corner then select the semantic model.

   ![](./media/ex3i11.png)

3. Click on the Ellipses (3 dots) next to **fraud_detection** Semantic Model to load the dropdown menu. Select **Create report** from the dropdown.

   ![](./media/semantic2.png)

4. When it pops up asking to **upgrade the Power BI license**, click **Try free**.

   ![Task-2.3_1.png](./media/up7.png)

5. Click on the **Copilot** button and click on **Get started**.

   ![](./media/ex3iu2.png)

6. click on **Got it**.

7. Paste the following question into the Copilot chat and on send. What's in my data?

![](./media/ex3iu3.png)

   >Note: If you get the pop-up, After clicking on the Copilot, Click on Get started.

8. Paste the following question into the Copilot chat and take a look at the response.

```
Create a report to analyse in detail only fraudulent transactions.
```
![](./media/semantic6.png)

> **Note**: The responses from Copilot may not match the ones in the screenshot.

9. Paste the following question into the Copilot chat and take a look at the response.
```
Based on the data of this report, what can be done to reduce the fraudulent transactions, and should I focus on.
```
![](./media/semantic8.png)

> **Note**: The responses from Copilot may not match the ones in the screenshot.
