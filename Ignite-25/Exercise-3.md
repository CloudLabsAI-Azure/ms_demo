## Exercise 3: Azure Databricks Mirrored Catalog in Microsoft Fabric

In this exercise, you will integrate Azure Databricks Unity Catalog with Microsoft Fabric’s OneLake using the Mirrored Catalog feature. This enables real-time access to Databricks data in Fabric without duplication. You’ll then create a semantic model in Direct Lake mode and use Power BI with Copilot to visualize, explore, and generate actionable insights on fraudulent transactions.

### Task 3.1: Mirror Unity Catalog Table into Fabric’s OneLake

Mirroring the Azure Databricks Catalog structure in Fabric allows seamless access to the underlying catalog data through shortcuts. This means that any changes made to the data are instantly reflected in Fabric, without the need for data movement or replication. Let’s step into Data Engineer, Eva’s shoes to create a Mirrored Azure Databricks Catalog and analyze the data using T-SQL. 

1. Navigate back to the Microsoft Fabric tab on your browser (https://app.fabric.microsoft.com).

2. Click on the **Ignite-25** and select **New item** from menu bar.

![Task-2.3_1.png](./media/Task-2.3_1.png)

3. In the **New item** window, scroll down and click on **Microsoft Azure Databricks catalog (preview)**.

![Task-2.3_2.png](./media/Task-2.3_2.png)

4. When the **New source** window pops up, click on the **Create new connection** radio button.

![Task-2.3_3.png](./media/Task-2.3_3.png)

5. In the URL field enter **https://adb-689745566023860.0.azuredatabricks.net**

6. Now, select **Service principal** from 'Authentication kind' dropdown box, and enter the following details.

- Tenant ID: ```f94768c8-8714-4abe-8e2d-37a64b18216a```
- Service principal client ID: ```95121828-71fb-4854-a9e6-cb7294eff8a2```
- Service principal Key: 

7. click on the **Connect** button.

![Task-2.3_7.png](./media/Task-2.3_7.png)

8. Click on **Next** button.

![Task-2.3_7.1.png](./media/Task-2.3_7.1.png)

9. In the Choose data screen, select the Catalog name as **zava_unity_catalog** from the dropdown box, and select the **fraud-detection** schema if not selected, scroll down then select the checkbox **Automatically sync future catalog changes for the selected schema** (to mirror future tables) if not ticked and click on **Next** button.

![Task-2.3_8.png](./media/Task-2.3_8.png)

10. Enter the **Name** for your mirrored Databricks Catalog and click on the **Create** button.

![Task-2.3_9.png](./media/Task-2.3_9.png)

11. Click on the **Monitor catalog** button to track the mirroring status and then close it.

![Task-2.3_10.1.png](./media/Task-2.3_10.1.png)

12. Click on the **View SQL endpoint** button. You can also select the tables to preview data.

![Task-2.3_10.png](./media/Task-2.3_10.png)

### Task 3.2: Create a semantic model in Direct Lake mode and use Power BI to visualize and generate insights

1. Click on **New Semantic model**.

![](./media/semantic.png)

2. Paste the semantic model name as **fraud_detection**, expand tables and select **anomaly_transactions** and then click on Confirm.

![](./media/adb53.png)

3. Click on the Ellipses (3 dots) next to **fraud_detection** Semantic Model to load the dropdown menu. Select **Create report** from the dropdown.

![](./media/semantic2.png)

4. Click on the **Copilot** button, select the ‘Inspire’ button (The Glitter icon at the bottom left of the chat window). Select the option **What’s in my data?** under the Inspire pane.

![](./media/semantic3.png)

5. Paste the following question into the Copilot chat and take a look at the response.

```
Create a report to analyse in detail only fraudulent transactions.
```
![](./media/semantic6.png)

6. Paste the following question into the Copilot chat and take a look at the response.
```
Based on the data of this report, what can be done to reduce the fraudulent transactions, and should I focus on.
```
![](./media/semantic8.png)

7. Paste the following question into the Copilot chat and take a look at the response.

```
What fraud prevention efforts can be implemented in each country with the highest number of fraud transactions?
```
![](./media/semantic7.png)
